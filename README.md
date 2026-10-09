<div align="center">

<a href="https://pos1.skotechlabs.com"><img src="assets/banner.png" alt="SKO POS by SKO TechLabs" width="100%"></a>

<h3>Subscription point-of-sale and inventory platform with a database per shop</h3>

<p>A point-of-sale and inventory platform sold as a subscription. Every shop runs on its own database, so no query anywhere can return another shop’s rows.</p>

<a href="https://pos1.skotechlabs.com"><img src="https://img.shields.io/badge/Live_Demo-Online-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo: Online"></a> <img src="https://img.shields.io/badge/Category-Software_Platform-7C3AED?style=for-the-badge" alt="Category: Software Platform"> <img src="https://img.shields.io/badge/Status-In_Production-16A34A?style=for-the-badge" alt="Status: In Production"> <a href="https://skotechlabs.com"><img src="https://img.shields.io/badge/Built_by-SKO_TechLabs-0F172A?style=for-the-badge" alt="Built by: SKO TechLabs"></a>

<p><a href="https://pos1.skotechlabs.com"><b>Live Demo</b></a> &nbsp;·&nbsp; <a href="https://skotechlabs.com/projects/sko-techlabs-pos"><b>Case Study</b></a> &nbsp;·&nbsp; <a href="https://skotechlabs.com/contact"><b>Request a Demo</b></a> &nbsp;·&nbsp; <a href="https://github.com/skotechlabs"><b>All Products</b></a></p>

</div>

---

## Overview

A complete retail system built from scratch — selling, stock, purchasing, accounting and staff in one place. It is sold as a subscription: one deployment serves many shops, and each shop is given a database of its own rather than a tenant column on shared tables.

That choice costs something — a schema change has to run against every shop — and it buys the thing that matters most to a shop owner: their figures cannot leak into someone else’s report because of one forgotten condition in one query.

Every sale writes its own double-entry journal as it happens, so the accounts are never a separate reconciliation job at month end.

<table>
<tr>
<td width="50%" valign="top">

### The Challenge

A shop owner will not accept “your data is separated in software” as an answer. One shared database with a tenant column puts a data leak one forgotten WHERE clause away — across 45 reports of hand-written SQL, that is not a risk worth carrying.

</td>
<td width="50%" valign="top">

### Our Solution

Each shop is provisioned its own database, resolved from the subdomain on the way in. A small registry database holds only the list of shops, their plans and the operator logins. Nothing is shared, so there is no query that could cross a shop boundary even by mistake.

</td>
</tr>
</table>

## Key Features

- Point of sale with barcode scanning, held sales and exchanges
- Stock control with batch tracking and low-stock alerts
- Purchasing, suppliers and supplier ledgers
- Double-entry accounting posted automatically on every sale
- Customer accounts, dues, advances and instalments
- Quotations that convert to sales at the quoted price
- Staff, attendance and commission
- 45 reports covering sales, stock, accounts and parties
- Multi-branch, with figures filterable per branch

## Business Impact

- Adding a shop is one command and needs no code change
- Accounts are always current, because every sale posts its own journal
- A shop's data cannot appear in another shop's report by construction

## Screenshots

<table>
<tr>
<td width="50%" valign="top"><img src="assets/cover.webp" alt="SKO POS: Subscription point-of-sale and inventory platform with a database per shop" width="100%"><br><sub>SKO POS: Subscription point-of-sale and inventory platform with a database per shop</sub></td>
<td width="50%"></td>
</tr>
</table>

> See it running: **[pos1.skotechlabs.com](https://pos1.skotechlabs.com)**

## Technology Stack

<p>
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=white" alt="React">
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

## Source Code & Licensing

This repository is the public showcase for **SKO POS**. The production source code is proprietary and is maintained privately by SKO TechLabs.

Interested in this product for your business? We offer:

- **Ready-to-launch deployment** of SKO POS under your own brand and domain
- **Customisation** of features, workflows, languages and integrations to fit how you work
- **Custom development** of a new product built on the same foundations
- **Ongoing support**, hosting, maintenance and feature roll-outs after launch

## Get in Touch

<p>
<a href="https://skotechlabs.com"><img src="https://img.shields.io/badge/Website-skotechlabs.com-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website: skotechlabs.com"></a>
<a href="mailto:sko.techlabs@gmail.com"><img src="https://img.shields.io/badge/Email-sko.techlabs%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email: sko.techlabs@gmail.com"></a>
<a href="https://wa.me/8801954547101"><img src="https://img.shields.io/badge/WhatsApp-%2B8801954547101-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp: +8801954547101"></a>
<a href="https://linkedin.com/company/skotechlabs"><img src="https://img.shields.io/badge/LinkedIn-SKO_TechLabs-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn: SKO TechLabs"></a>
</p>

---

<div align="center"><sub>© 2026 <a href="https://skotechlabs.com">SKO TechLabs</a> · Dhaka, Bangladesh · Building intelligent digital solutions</sub></div>
