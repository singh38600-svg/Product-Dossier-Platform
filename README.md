# The Product Dossier — Automated Publisher

This repository is designed for phone-first publishing. There are no folders to create or maintain.

## One-time setup

Upload the root files in this package to a new GitHub repository and connect it to Vercel.

## Every future edition

1. Complete the research in ChatGPT.
2. Receive one file such as `edition-002-company-name-r1.zip`.
3. Upload that single ZIP to the **repository root** and commit it.
4. Vercel rebuilds automatically.

The platform automatically creates:

- the homepage card
- the editions archive
- the company edition page
- the evidence library
- download cards for PDF, DOCX, PPTX, XLSX and other files
- clean URLs and redirects
- sitemap and metadata

## Updating an edition

Upload a new ZIP with the same slug and a higher revision, for example:

- `edition-001-delta-exchange-r1.zip`
- `edition-001-delta-exchange-r2.zip`

The highest revision is published automatically. Older revisions remain as history and do not need to be deleted.

## Guardrails

The build rejects public Product Manager, job-seeking, interview, candidate, résumé and portfolio framing. It also rejects recruitment-style filenames and unsafe ZIP paths.

## Optional browser builder

After deployment, open `/publisher/` to generate a valid edition ZIP from a phone or computer.
