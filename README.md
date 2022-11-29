# The National Archives: Find Case Law

This repository is part of the [Find Case Law](https://caselaw.nationalarchives.gov.uk/) project at [The National Archives](https://www.nationalarchives.gov.uk/). For more information on the project, check [the documentation](https://github.com/nationalarchives/ds-find-caselaw-docs).

# Custom PDFs

A number of PDF documents are not being generated correctly by LibreOffice. Here, we manually provide versions printed from Word with corrected formatting.

The scripts `script/upload-staging` and `script/upload-prod` will upload the files to both unpublished and published buckets. A metadata flag of `pdfsource=custom-pdfs` is set for future use to not overwrite these files.
