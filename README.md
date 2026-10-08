# Blossom School ERP V2

Deploy-ready Next.js prototype for Blossom Kindergarten Senior Secondary School, Banswara, Rajasthan.

## Included in V2
- Responsive desktop/mobile dashboard
- Student master data
- Fee demand, paid and pending calculations
- Pending-fee command center
- Payment entry with receipt number generation
- Payment history
- CSV export
- Class/student search
- Academic year label (2026–27)
- Foundation for class-wise fee heads and installments

## Run locally
```bash
npm install
npm run dev
```

Open http://localhost:3000

## Important
This V2 is a front-end prototype with demo data in React state. It is NOT production-ready for real student/financial information.

Before real use, add:
- PostgreSQL database
- Authentication and role permissions
- Server-side validation
- Encrypted secrets
- Audit logs
- Automated backups
- Class/student-specific fee assignments and installments
- Payment allocation against invoices/installments
- Receipt persistence
- Secure production deployment

## Vercel
This project is structured for Vercel/Next.js deployment. Connect the GitHub repository to Vercel and use the default Next.js build settings.
