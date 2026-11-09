# My Money

Offline-first personal finance and loan tracker for Maldives (MVR). Responsive installable web app, deployable through GitHub Pages.

## Features
- Salary cycle and budget allocations (15th default)
- Income, paid expenses, reports and CSV export
- Permanent lender profiles with mobile, bank, account holder and account number
- Loan principal balances, repayment history, interest/fees, cleared-loan archive
- Local-only browser persistence and JSON backup/restore

## Deploy
In GitHub Settings → Pages, choose **GitHub Actions** as the build/deploy source. Pushes to main run the Pages workflow.

## Important limitations
This is an initial web MVP, **not yet an Android APK**. Android packaging and cross-device sync remain future work. Browser localStorage is not encrypted and can be lost when site data is cleared; do not use it for sensitive financial account details until encrypted storage and security hardening are implemented. Export backups and store them securely. This app does not transfer money or connect to banks. The financial engine is an MVP, not a full double-entry accounting ledger.
