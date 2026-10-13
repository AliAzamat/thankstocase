# RealEst — Support Case Thank-You Page

**The confirmation page shown after a customer submits the RealEst Salesforce Web-to-Case support form.**

This is one of three small repos that make up a Salesforce web-form demo for a fictional real-estate company:

| Repo | Role |
|---|---|
| [webservice](https://github.com/AliAzamat/webservice) | The Web-to-Lead and Web-to-Case forms |
| [thankslead](https://github.com/AliAzamat/thankslead) | Thank-you page after a lead submission |
| **thankstocase** | Thank-you page after a support case submission (this repo) |

The case form's `retURL` points here (`aliazamat.github.io/thankstocase/`), so Salesforce redirects customers to this page after creating the Case. It confirms the issue was received, sets a 24-hour resolution expectation, reminds the customer to watch for an email from support, and links back to the form.

## Files

- `index.html` — the page
- `thanks-to-case.css` — styles
- `logo.png` — RealEst logo

Open `index.html` in a browser to view it, or host the folder on GitHub Pages.
