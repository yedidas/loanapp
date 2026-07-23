# Loan Application Form (Public)

This repo hosts only the public-facing loan application form via GitHub Pages:
`https://yedidas.github.io/loanapp/Loan_Form_Final_Fixed.html`

It contains **no backend code and no configuration secrets** — the form's
Google Apps Script URL, Agent ID, and Email FROM address are entered by each
user at runtime and stored only in their own browser's `localStorage`.

The Apps Script backend (`Code.gs`) that this form talks to lives in a
**separate, private** repository (`loanapp-backend`), since it contains
real Google Sheet/Drive resource IDs that should not be public.
