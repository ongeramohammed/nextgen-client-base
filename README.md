# NextGen Client Base

Professional web-based client management dashboard inspired by ClientBase Pro, rebuilt for NextGen with original code and improved UI.

Live site: https://ongeramohammed.github.io/nextgen-client-base/

## Current features

- Dashboard, clients, payments, invoices, services, reminders, VAT and reports
- Mobile-friendly layout
- Browser localStorage demo records
- M-Pesa & Bank integration-readiness page with setup plan download
- Adobe Photoshop & InDesign Studio page with Adobe launch links and design brief download

## Payment automation note

GitHub Pages is static hosting, so it cannot safely receive M-Pesa or bank callbacks by itself. Real automatic payment updates require a secure backend that keeps API keys private and exposes HTTPS callback endpoints.

### M-Pesa Daraja requirements

- Safaricom developer app Consumer Key and Consumer Secret
- Business Paybill/Till shortcode
- STK Push passkey or C2B confirmation/validation setup
- Public HTTPS callback URL
- Backend/database to verify callbacks and update invoices/payments

### Bank update options

- Official business bank API where available
- CSV/Excel bank statement import
- Email/SMS statement parser through a backend

Never place bank or Daraja secrets inside browser JavaScript.

## Adobe Photoshop and InDesign note

The site can launch Adobe web tools, organize client design jobs and generate briefs. Adobe Photoshop/InDesign desktop files still need to be opened in Adobe software by the designer. A deeper Adobe OAuth/API or cloud-file workflow would require an Adobe developer project and backend hosting.
