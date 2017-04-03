
# wh-financial-disclosures

This project focuses on data collection and analysis of United States Office of Government Ethics (OGE) Public Financial Disclosures (PFDs) submitted via OGE Form 278e.

## Background

The Ethics in Government Act of 1978 ([5 U.S.C. Appendix](https://www.gpo.gov/fdsys/granule/USCODE-2010-title5/USCODE-2010-title5-app-ethicsing), [Wikipedia](https://en.wikipedia.org/wiki/Ethics_in_Government_Act)) codified public transparency into the financial interests and employment ties of senior United States Government officials.  The [United States Office of Government Ethics](https://www.oge.gov/) created OGE Form 278e ([XLS](https://www.oge.gov/web/oge.nsf/All%20Documents/3DE621AB3A93CB9885257EC1005CAA01/$FILE/OGE%20Form%20278e_Excel%20ver.xls?open), [PDF](https://www.oge.gov/web/oge.nsf/All%20Documents/48EAF45DA952AAB685257FFD006CCE93/$FILE/OGE%20Form%20278e_PDF%20ver.pdf?open)) and OGE Form 278-T to collect required information from filers ([User Guide](https://www.oge.gov/Web/278eGuide.nsf/Chapters/Public%20Financial%20Disclosure%20Guide?opendocument)).

For White House and Executive branch officials, individuals can request a copy of the public financial disclosures of a specific named individual using [this web form](https://www.whitehouse.gov/financial-disclosures).  @stevenrich created [a Python script](https://gist.github.com/stevenrich/36b0a1efe30f46f849db16a517e4bebe) to automate this process.


## Resources

### Source Files

* [U.S. Office of Government Ethics](https://www.oge.gov/Web/OGE.nsf/Presidential+Appointee+&+Nominee+Records) - copies of certain public financial disclosure reports, ethics agreements, and ethics pledge waivers are available while some must be requested via [OGE Form 201](https://extapps2.oge.gov/201/Presiden.nsf/201+Request?OpenForm).
* [ProPublica](https://drive.google.com/drive/u/0/folders/0BwDYM_Qm5fLWVXgzMVZMLVA0Ync) - public Google Drive folder containing released PFDs as PDF files.
* [Open Secrets](https://www.opensecrets.org/trump/financial-disclosures) - previously requested PFDs and Ethics Agreement Files for White House officials and Senate-confirmed Cabinet positions.
* The [`/disclosures` directory](https://github.com/Data4Democracy/wh-financial-disclosures/tree/master/disclosures) in this project aggregates actionable PFDs from all sources.

### Parsers

* Center for Public Integrity [pfd-parser](https://github.com/PublicI/pfd-parser) project.  NodeJS script used to generate the parsed files posted to data.world.

### Parsed Files

* [D4D Hack Financial Disclosures](https://data.world/rflprr/d-4-d-hack-financial-disclosures) dataset on data.world.  9 CSV files mapping the tabular data from the actionable source files.
