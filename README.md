# ChitFlow V2.2 - GitHub Pages demo

Static frontend-only chit fund manager prototype. Data is stored in browser localStorage.

## V2.2 additions
- Expanded read-only group member login/dashboard.
- Member can see all group members and who lifted/received the chit each month.
- Shows months paid, total paid, remaining months and current payment status.
- Configurable pre-lift premium, post-lift premium, first-month payout and monthly payout increment.
- Automatic 20-month payout schedule similar to the supplied reference (e.g. 95,000 -> 1,14,000).
- Calculates expected lifetime contribution based on lift month and displays Net Gain or Net Cost versus payout.
- Manager auction form now records the scheduled payout and lift month.
- Payment popup from V2.1 remains available with actual amount/date/mode/reference/notes.

## Demo accounts
Manager: manager@demo.com / demo123
Member: nowshath@demo.com / demo123

## Deploy
Upload index.html, styles.css and app.js to a GitHub repository, then enable GitHub Pages for the repository root.

## Important
This is a prototype. GitHub Pages cannot provide a secure backend or shared database. localStorage is per browser/device. Do not use it for real financial records until authentication and persistent server-side storage are added.
