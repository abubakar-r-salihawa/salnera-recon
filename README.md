# SALNERA Recon

SALNERA Recon is an offline Python application that helps streamline financial reconciliation, PAYE tax calculation and balance analysis in one workflow. It is designed for small organisations and finance teams that perform frequent reconciliations between bank statements, ledgers and payroll data.

## Features

- **Reconciliation:** Import bank transactions and ledger entries in CSV or Excel format, match them automatically, and identify unmatched transactions. The tool generates a reconciliation summary that highlights outstanding items.
- **PAYE calculation:** Calculate employee PAYE tax obligations based on salary and deductions using up-to-date tax rules. Results are exportable for payroll processing.
- **Balance analysis:** Analyse account balances, compare beginning and ending balances, and generate variance reports for management review.
- **Offline and private:** SALNERA Recon runs completely offline and does not send your data anywhere. Sample data files are included to demonstrate functionality without exposing real financial information.
- **Extensible:** The application is built with Python and uses a modular architecture. You can adapt it to your organisation’s chart of accounts, tax rules or reporting needs.

## Getting started

1. Clone or download this repository.
2. Install the dependencies from `requirements.txt` using `pip install -r requirements.txt`.
3. Run the application with `python src/main.py`.
4. Load your bank statement and ledger files via the interface.
5. Review the reconciliation and balance reports.

## Project structure

```
salnera-recon/
├── README.md               # project overview and usage
├── requirements.txt        # Python dependencies
├── src/                    # source code for the application
│   ├── main.py             # application entry point
│   ├── recon/              # reconciliation logic
│   ├── paye/               # PAYE calculation logic
│   └── analysis/           # balance analysis logic
├── data/                   # sample anonymised data
├── docs/                   # documentation and user guide
├── tests/                  # automated tests
└── CHANGELOG.md            # release history and future roadmap
```

## Licence

This project is licensed under the MIT Licence – see the `LICENSE` file for details.

## Security and privacy

The repository does not contain any real financial data. Please use sample data or anonymise sensitive information when sharing examples or issues. See `SECURITY.md` for guidelines on responsible disclosure of vulnerabilities.
