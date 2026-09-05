# Materia

**Beauty · Inventory Intelligence**

Materia is a vertical SaaS platform for hair and beauty salons in Japan, built and operated by Materia Inc. (株式会社Materia).

Salons run on consumables: hair color, perm solutions, treatments, and retail products. Most still track them on paper or in spreadsheets. Materia replaces that with a cloud platform that turns supplier delivery slips into structured data and keeps inventory, purchasing, and sales in one place.

## What the product does

- **Delivery slip OCR:** photograph a supplier's delivery slip and the product names, quantities, and unit prices are extracted automatically.
- **AI reorder suggestions:** recommended order quantities based on each salon's historical consumption.
- **Inventory, purchasing, and sales in one place:** stock levels, purchase orders, and sales data managed together, with product and price history maintained automatically.
- **Dashboards and analytics:** cost-of-goods and usage analysis, including side-by-side comparison across locations for multi-salon operators.

## Technology

Materia is a multi-tenant web application built with Ruby on Rails and Hotwire, backed by PostgreSQL and Redis. Infrastructure is defined in Terraform, runs on AWS, and is served through Cloudflare.

Our application code is private. This organization hosts our public profile and our [security policy](https://github.com/okonomiyaki-matsuri/.github/blob/main/SECURITY.md).

## Links

- Website: https://www.themateria.jp/
- Service: https://themateria.net/
- Contact: info@themateria.jp
