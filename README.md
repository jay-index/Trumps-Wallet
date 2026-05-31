# Trump's-Wallet
Open-source project covering Donald J. Trump's personal finances.


To update the site after any data changes:
Edit the Google Sheet
Re-upload the sheet here → Claude.ai regenerates trump_assets.json and trump_liabilities.json
Upload both JSONs to GitHub → all three pages update automatically

Files in GitHub and what they do:
trump_assets.json → powers asset browser table, filing card stats, trends charts, asset tracker search
trump_liabilities.json → powers liabilities page, filing card net worth, trends liability charts
trumps-wallet.html → asset browser (no hardcoded numbers)
trumps-wallet-trends.html → trends/charts (no hardcoded numbers)
trumps-wallet-liabilities.html → liability browser (no hardcoded numbers)


HOW THIS DATA WORKS
Trump’s Wallet · Hunter Index
What is Trump’s Wallet?
A database tracking Donald Trump’s personal finances across five public OGE Form 278 filings, from his first presidential campaign through his return to the White House. Every asset, every income line, every liability — processed by hand, assigned a unique ID, and cross-referenced across years so you can see how the portfolio changed over time.


The database does not currently include Trump’s Periodic Transaction Reports (OGE Form 278-T), which disclose individual securities trades. 
Those are referenced in related reporting but have not yet been incorporated here.

Why do some filings cover more than 12 months?
Annual forms cover the preceding calendar year — a clean 12 months. 
Candidate forms are different: per OGE’s rules, they cover the preceding full calendar year plus the current year up to the filing date. 
Trump’s 2024 candidate form, filed August 13, covers all of 2023 plus January through August 2024 — about 19.5 months. 
Raw income totals from candidate forms aren’t directly comparable to annual forms or to each other. Where this database makes year-over-year comparisons, income has been annualized to a 12-month equivalent.

Are the values exact?
Sometimes. The form requires asset values to be reported in broad dollar ranges — “$1,001 to $15,000,” for example — rather than exact figures. 
For the filer’s own assets, the top open-ended category is “Over $50,000,000”; for a spouse’s or dependent child’s assets, the form uses a lower ceiling of “Over $1,000,000.” 
Where a range is reported, the database records the midpoint as a median estimate. For open-ended ranges, it uses the stated minimum as the floor — so an “Over $50,000,000” asset is recorded as $50,000,000, which almost certainly understates the true value.

Income is different. While some income lines use the same range structure, Trump’s filings frequently report exact dollar amounts for individual income items — particularly business income and speaking fees. Where an exact amount is disclosed, the database uses that figure directly rather than a range midpoint.
These are also self-reported figures, not audited ones. A New York state court found that Trump and the Trump Organization fraudulently inflated property values in financial statements used with lenders and insurers. When this database records a value, it reflects what Trump disclosed to OGE.

How are income figures calculated?
Where income is reported as a range, the database records the midpoint. Where the ceiling is open-ended (“Over $5,000,000”), it uses the stated minimum. Where an exact amount is disclosed, that figure is used directly. All original figures are transcribed exactly as reported — we do not interpret, adjust, or correct reported values or income types.

What is the “asset type” field?
The OGE form does not assign asset types — filers describe each asset in plain text. The asset type field in this database is a Hunter Index–created classification, applied to the best of our ability based on each asset’s description. It allows filtering and comparison across filing years but represents our editorial judgment, not an official OGE category. All underlying data is transcribed directly from the forms as filed.

What’s not in the database?
The 2023 annual form — covering calendar year 2022 — was not processed; OGE attached a litigation note to that filing. The 2017, 2018, and 2021 termination report have also not yet been processed. That means calendar years 2016, 2017, 2018, and 2022 are not represented.

Who made this?
Hunter Index, a nonprofit news organization (EIN 33-3157569) covering the personal finances of politicians. Any use of this data must be attributed to Hunter Index with a link to hunterindex.org.



See the Elevator Pitch overview here: https://drive.google.com/file/d/1tFGGLYkx3qeobauS3RWu1Cw3pGJYcePq/view?usp=sharing
