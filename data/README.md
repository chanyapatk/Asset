# Data

This project uses the **2024 Enterprise Public Use Database (PUDB)** published by the **Federal Housing Finance Agency (FHFA)**.

The raw data files are not stored in this repository because of their large file size. They can be downloaded directly from the official FHFA source.

## Source

- **FHFA Public Use Database (PUDB):** https://www.fhfa.gov/data/pudb
- **2024 Enterprise PUDB Data Dictionary:** https://www.fhfa.gov/document/2024-enterprise-pudb-data-dictionary.pdf

## Files Used in This Project

The analysis uses the 2024 **Single-Family Census Tract File** for both Enterprises:

- `2024_pudb_sf_ctf_fnma.csv` — Fannie Mae
- `2024_pudb_sf_ctf_fhlmc.csv` — Freddie Mac

These files contain mortgage-level records for single-family properties and include variables used in this project such as borrower income, Debt-to-Income Ratio (DTI), property location, loan characteristics, and other borrower/mortgage attributes.

## How to Download the Raw Data

1. Open the [FHFA Public Use Database](https://www.fhfa.gov/data/pudb).
2. Go to **2024 Enterprise PUDB Data**.
3. Find **Single-Family Census Tract File**.
4. Download the **CSV** version.
5. Use the Fannie Mae and Freddie Mac files listed above for the analysis.

## Repository Data Policy

To keep this repository lightweight and reproducible:

- Large raw files are kept outside GitHub and downloaded from the official FHFA source.
- Only smaller cleaned, sampled, or processed datasets may be added to this folder when needed.
- Any processed file added later should include a short description of how it was created from the original FHFA data.

