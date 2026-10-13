# Bindushree Biomedicals — blueoak.cloud

Static website for Bindushree Biomedicals: clinical lab analyzer sales and service, plus Bindushree-brand reagents, rapid tests and consumables (India).

- `index.html` — the whole site (no build step)
- `amplify.yml` — AWS Amplify build settings (serves `index.html` as-is)

## Before going live
- Fill the placeholders marked with the `todo` class (CDSCO licence, phone, address, GSTIN, founder/year).
- Set the enquiry form endpoint: `data-endpoint=""` on `#enquiry-form` (Formspree, Web3Forms, etc.).

## Deploy
Connected to AWS Amplify: every push to `main` redeploys blueoak.cloud.
