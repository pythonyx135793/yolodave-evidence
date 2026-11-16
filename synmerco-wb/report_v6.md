# External-sector scorecard, every country 1995-2024 (World Bank)

Escrow esc_379d14f823434fa18ba47212, job job_8d4d75dfb9aa4068. All scorecard figures, rankings and lists below are computed from **macro-external-pull3.csv** (the last good pull; pull 2's three indicator requests failed after one retry, see PROOF). Periods 1995-2004, 2005-2014, 2015-2024; mean over years with a value, n = years used, n/a = no value in the period; change = last-period mean minus first-period mean (n/a if either is n/a). Units: percent (growth) / percent of GDP (shares). Figures rounded to 2 decimals, half away from zero, from unrounded values. Aggregates (region id NA) excluded.

Data files: macro-external-pull1.csv rows=6510 sha256=3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2; macro-external-pull2.csv rows=6510 sha256=b07e30751f8563a9840b4a2c414786bcd03ffce01056bfa16e302f8211f5f737; macro-external-pull3.csv rows=6510 sha256=3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2. 217 countries x 30 years = 6510 rows. Changes data files (key,column,earlier,later; one row per changed cell): changes-pull2-vs-pull1.csv rows=14854 sha256=2a69325527465012a0084fd0dae28f0c95d71af7bdc7a9453d9ad229fffbe00e; changes-pull3-vs-pull2.csv rows=14854 sha256=6a45f1dd43fe8e05c31ac060b48b180425146a51e071202fde601935b085aecb.


```synmerco-data
3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2 macro-external-pull1.csv
b07e30751f8563a9840b4a2c414786bcd03ffce01056bfa16e302f8211f5f737 macro-external-pull2.csv
3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2 macro-external-pull3.csv
2a69325527465012a0084fd0dae28f0c95d71af7bdc7a9453d9ad229fffbe00e changes-pull2-vs-pull1.csv
6a45f1dd43fe8e05c31ac060b48b180425146a51e071202fde601935b085aecb changes-pull3-vs-pull2.csv
```


## ACCEPTANCE checklist (each item with where it is proven)

1. CSV files attached with exactly the listed columns, one row per country (aggregates excluded) and year. Proof: the synmerco-data block above (three verified files, 6510 rows each = 217 countries x 30 years); header of each file: `countryiso3code,country,region,incomeLevel,date,export growth,investment share,current account`; key countryiso3code|date, sorted by key.
2. Every country in a top-10 or list has its observations in the PROOF, matching the CSV. Proof: PROOF > "Observations behind each list" (iso3|date|value lines taken from macro-external-pull3.csv, which every figure in this report uses).
3. Period means, years used, changes, rankings and lists follow the TASK and agree with the CSV they use (macro-external-pull3.csv). Proof: the ranking, list and scorecard sections below; definitions repeated in the intro paragraph.
4. Each response's paging element and rows received vs total. Proof: PROOF > "Paging elements PULL 1/2/3", e.g. PULL 3 `NE.GDI.TOTL.ZS: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, ...}` with rows received=7980 (aggregates included), match=yes; PULL 2 indicator requests failed after one retry (no response).
5. Platform record and Changes. Proving excerpt:
   - PULL 1 note 2026-11-13 15:17:04 UTC: macro-external-pull1.csv, 6510 rows, SHA-256 3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2
   - PULL 2 note 2026-11-14 17:10:59 UTC (+25.9 h): macro-external-pull2.csv, 6510 rows, SHA-256 b07e30751f8563a9840b4a2c414786bcd03ffce01056bfa16e302f8211f5f737
   - PULL 3 note 2026-11-15 17:52:11 UTC (+24.7 h): macro-external-pull3.csv, 6510 rows, SHA-256 3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2
   - Source times (HTTP Date of each pull's first request) increase: Fri, 13 Nov 2026 15:14:15 GMT < Sat, 14 Nov 2026 17:04:40 GMT < Sun, 15 Nov 2026 17:52:07 GMT
   - Changes PULL 2 vs PULL 1 (matched by key): rows 6510 and 6510, new 0, gone 0, changed 14854 cells in 5859 keys, every cell listed in data file changes-pull2-vs-pull1.csv (14854 rows, SHA-256 2a69325527465012a0084fd0dae28f0c95d71af7bdc7a9453d9ad229fffbe00e)
   - Changes PULL 3 vs PULL 2 (matched by key): rows 6510 and 6510, new 0, gone 0, changed 14854 cells in 5859 keys, every cell listed in data file changes-pull3-vs-pull2.csv (14854 rows, SHA-256 6a45f1dd43fe8e05c31ac060b48b180425146a51e071202fde601935b085aecb)
   - TASK rule applied: "A failed pull: write pull k failed for its Changes; compare the next with the last good one." pull 2 failed (its three indicator requests failed after one retry; the country request alone succeeded). Changes PULL 3 vs PULL 1 (the last good pull, matched by key countryiso3code|date, columns export growth, investment share, current account): no change. Rows PULL 1 = 6510, PULL 3 = 6510 (6510 = 6510 + 0 - 0); new = 0, gone = 0, changed = 0. Both files have the identical SHA-256 3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2.
   - For completeness the cell-by-cell lists against the failed pull 2 are still attached (changes-pull2-vs-pull1.csv, changes-pull3-vs-pull2.csv); every listed cell is a value present in pull 1/pull 3 and empty in pull 2 because of the failed requests.

## Ranking: change in mean investment share (gross capital formation, % of GDP), 1995-2004 to 2015-2024, highest first (ties: code ascending)

Ranked: 159 countries. Overall rank kept; shown grouped by incomeLevel.

### High income

| overall rank | code | country | mean 1995-2004 | mean 2015-2024 | change |
|---|---|---|---|---|---|
| 10 | BHR | Bahrain | 16.65 | 30.57 | 13.92 |
| 17 | GRL | Greenland | 17.84 | 29.90 | 12.06 |
| 19 | BRN | Brunei Darussalam | 22.91 | 33.97 | 11.06 |
| 22 | QAT | Qatar | 30.54 | 40.83 | 10.28 |
| 25 | PAN | Panama | 27.53 | 36.54 | 9.01 |
| 33 | IRL | Ireland | 23.62 | 31.10 | 7.49 |
| 35 | SAU | Saudi Arabia | 20.01 | 27.16 | 7.15 |
| 39 | KWT | Kuwait | 15.34 | 21.42 | 6.08 |
| 41 | OMN | Oman | 24.21 | 29.91 | 5.70 |
| 46 | MAC | Macao SAR, China | 15.57 | 20.02 | 4.45 |
| 48 | SWE | Sweden | 21.15 | 25.00 | 3.85 |
| 53 | ROU | Romania | 21.38 | 24.96 | 3.59 |
| 57 | RUS | Russian Federation | 20.33 | 23.69 | 3.35 |
| 58 | NCL | New Caledonia | 24.29 | 27.62 | 3.33 |
| 59 | CAN | Canada | 20.31 | 23.54 | 3.22 |
| 60 | BGR | Bulgaria | 17.36 | 20.54 | 3.18 |
| 61 | NOR | Norway | 22.12 | 25.23 | 3.11 |
| 64 | BEL | Belgium | 22.16 | 24.78 | 2.62 |
| 66 | FRO | Faroe Islands | 25.38 | 27.59 | 2.21 |
| 68 | FRA | France | 20.52 | 22.58 | 2.06 |
| 69 | FIN | Finland | 22.20 | 24.25 | 2.05 |
| 76 | URY | Uruguay | 15.44 | 16.86 | 1.42 |
| 78 | ARE | United Arab Emirates | 21.79 | 23.16 | 1.37 |
| 79 | DNK | Denmark | 21.39 | 22.69 | 1.30 |
| 80 | NZL | New Zealand | 23.09 | 24.06 | 0.97 |
| 84 | HRV | Croatia | 21.85 | 22.51 | 0.66 |
| 88 | HUN | Hungary | 26.36 | 26.75 | 0.39 |
| 89 | ISL | Iceland | 22.02 | 22.38 | 0.36 |
| 91 | GBR | United Kingdom | 18.65 | 18.73 | 0.07 |
| 92 | AUT | Austria | 25.63 | 25.70 | 0.07 |
| 95 | CHE | Switzerland | 27.81 | 27.63 | -0.18 |
| 96 | LTU | Lithuania | 21.85 | 21.47 | -0.37 |
| 100 | NLD | Netherlands | 21.86 | 21.06 | -0.81 |
| 101 | TTO | Trinidad and Tobago | 21.59 | 20.76 | -0.83 |
| 102 | USA | United States | 22.37 | 21.47 | -0.91 |
| 103 | ITA | Italy | 20.93 | 20.00 | -0.92 |
| 104 | DEU | Germany | 22.46 | 21.41 | -1.05 |
| 106 | AUS | Australia | 25.41 | 24.06 | -1.35 |
| 110 | ISR | Israel | 26.03 | 24.56 | -1.47 |
| 111 | CHL | Chile | 25.50 | 23.85 | -1.65 |
| 112 | LVA | Latvia | 25.29 | 23.45 | -1.83 |
| 113 | POL | Poland | 21.95 | 20.11 | -1.84 |
| 114 | CYP | Cyprus | 21.34 | 19.22 | -2.12 |
| 118 | KOR | Korea, Rep. | 33.71 | 31.29 | -2.42 |
| 119 | JPN | Japan | 29.78 | 27.19 | -2.59 |
| 120 | CRI | Costa Rica | 19.97 | 17.34 | -2.63 |
| 122 | BHS | Bahamas, The | 27.68 | 25.00 | -2.69 |
| 124 | MLT | Malta | 24.14 | 21.36 | -2.78 |
| 126 | EST | Estonia | 30.30 | 26.77 | -3.53 |
| 127 | LUX | Luxembourg | 21.53 | 17.73 | -3.79 |
| 130 | ESP | Spain | 25.25 | 20.71 | -4.54 |
| 133 | CZE | Czechia | 31.66 | 26.74 | -4.92 |
| 137 | PRI | Puerto Rico (US) | 17.48 | 12.06 | -5.42 |
| 139 | SVN | Slovenia | 27.03 | 21.16 | -5.88 |
| 140 | SGP | Singapore | 29.92 | 23.98 | -5.95 |
| 143 | ABW | Aruba | 28.59 | 21.56 | -7.02 |
| 145 | PRT | Portugal | 26.22 | 18.93 | -7.30 |
| 147 | SVK | Slovak Republic | 30.32 | 22.82 | -7.50 |
| 148 | SYC | Seychelles | 29.91 | 22.26 | -7.65 |
| 153 | HKG | Hong Kong SAR, China | 27.53 | 18.85 | -8.68 |
| 154 | GRC | Greece | 23.69 | 14.57 | -9.11 |

### Low income

| overall rank | code | country | mean 1995-2004 | mean 2015-2024 | change |
|---|---|---|---|---|---|
| 1 | ETH | Ethiopia | 0.00 | 31.26 | 31.26 |
| 5 | COD | Congo, Dem. Rep. | 9.52 | 28.91 | 19.38 |
| 6 | GMB | Gambia, The | 7.59 | 26.25 | 18.66 |
| 7 | NER | Niger | 13.41 | 31.04 | 17.63 |
| 9 | CAF | Central African Republic | 9.96 | 24.49 | 14.53 |
| 20 | SLE | Sierra Leone | 6.54 | 17.10 | 10.55 |
| 38 | MDG | Madagascar | 12.54 | 19.12 | 6.59 |
| 43 | UGA | Uganda | 18.69 | 24.15 | 5.46 |
| 56 | MOZ | Mozambique | 33.90 | 37.31 | 3.41 |
| 62 | MLI | Mali | 20.73 | 23.67 | 2.93 |
| 85 | BFA | Burkina Faso | 19.03 | 19.65 | 0.63 |
| 132 | GNB | Guinea-Bissau | 26.30 | 21.40 | -4.90 |
| 149 | TCD | Chad | 28.36 | 20.56 | -7.81 |
| 152 | SDN | Sudan | 15.98 | 7.37 | -8.61 |
| 156 | RWA | Rwanda | 38.03 | 27.95 | -10.08 |
| 159 | YEM | Yemen, Rep. | 20.98 | 2.83 | -18.14 |

### Lower middle income

| overall rank | code | country | mean 1995-2004 | mean 2015-2024 | change |
|---|---|---|---|---|---|
| 2 | MRT | Mauritania | 14.81 | 41.00 | 26.19 |
| 3 | TZA | Tanzania | 17.36 | 37.55 | 20.18 |
| 4 | TJK | Tajikistan | 15.94 | 35.57 | 19.62 |
| 11 | SEN | Senegal | 20.69 | 34.15 | 13.46 |
| 12 | KGZ | Kyrgyz Republic | 18.06 | 31.51 | 13.45 |
| 13 | KHM | Cambodia | 18.55 | 31.48 | 12.93 |
| 14 | SLB | Solomon Islands | 7.21 | 19.53 | 12.32 |
| 16 | GIN | Guinea | 13.47 | 25.55 | 12.08 |
| 18 | UZB | Uzbekistan | 21.13 | 32.25 | 11.12 |
| 21 | NPL | Nepal | 23.59 | 34.08 | 10.49 |
| 23 | COG | Congo, Rep. | 26.71 | 36.81 | 10.11 |
| 24 | BEN | Benin | 17.29 | 27.22 | 9.93 |
| 28 | BGD | Bangladesh | 22.85 | 31.01 | 8.16 |
| 30 | VEN | Venezuela, RB | 0.00 | 8.03 | 8.03 |
| 31 | CIV | Cote d'Ivoire | 15.09 | 22.99 | 7.90 |
| 34 | LAO | Lao PDR | 23.11 | 30.28 | 7.18 |
| 42 | MAR | Morocco | 25.01 | 30.55 | 5.55 |
| 49 | VUT | Vanuatu | 19.14 | 22.98 | 3.84 |
| 52 | BOL | Bolivia | 16.65 | 20.25 | 3.60 |
| 55 | IND | India | 28.53 | 32.00 | 3.47 |
| 65 | KEN | Kenya | 16.90 | 19.30 | 2.40 |
| 81 | NAM | Namibia | 19.67 | 20.61 | 0.94 |
| 83 | CMR | Cameroon | 18.11 | 18.91 | 0.80 |
| 87 | TLS | Timor-Leste | 26.21 | 26.72 | 0.51 |
| 90 | NIC | Nicaragua | 24.60 | 24.93 | 0.33 |
| 94 | BTN | Bhutan | 49.45 | 49.42 | -0.03 |
| 105 | EGY | Egypt, Arab Rep. | 18.86 | 17.57 | -1.29 |
| 108 | PAK | Pakistan | 16.70 | 15.27 | -1.42 |
| 116 | HTI | Haiti | 18.64 | 16.32 | -2.32 |
| 125 | ZWE | Zimbabwe | 13.28 | 9.92 | -3.37 |
| 129 | HND | Honduras | 27.79 | 23.85 | -3.95 |
| 131 | GHA | Ghana | 23.18 | 18.48 | -4.70 |
| 134 | COM | Comoros | 18.04 | 13.12 | -4.93 |
| 142 | PSE | West Bank and Gaza | 32.80 | 25.80 | -6.99 |
| 150 | TUN | Tunisia | 24.62 | 16.75 | -7.87 |
| 151 | TGO | Togo | 28.98 | 20.90 | -8.08 |
| 155 | AGO | Angola | 30.76 | 20.96 | -9.80 |
| 158 | LBN | Lebanon | 25.59 | 12.00 | -13.59 |

### Upper middle income

| overall rank | code | country | mean 1995-2004 | mean 2015-2024 | change |
|---|---|---|---|---|---|
| 8 | DZA | Algeria | 28.28 | 43.87 | 15.59 |
| 15 | MKD | North Macedonia | 19.77 | 32.02 | 12.24 |
| 26 | SRB | Serbia | 14.10 | 22.89 | 8.79 |
| 27 | LKA | Sri Lanka | 24.74 | 33.01 | 8.27 |
| 29 | TUR | Turkiye | 24.35 | 32.40 | 8.05 |
| 32 | MNE | Montenegro | 19.33 | 27.01 | 7.68 |
| 36 | IDN | Indonesia | 25.78 | 32.53 | 6.75 |
| 37 | MHL | Marshall Islands | 17.70 | 24.39 | 6.69 |
| 40 | KAZ | Kazakhstan | 21.30 | 27.07 | 5.77 |
| 44 | CHN | China | 36.81 | 42.26 | 5.45 |
| 45 | TON | Tonga | 21.75 | 26.74 | 5.00 |
| 47 | ECU | Ecuador | 17.07 | 21.00 | 3.92 |
| 50 | MNG | Mongolia | 28.24 | 32.04 | 3.80 |
| 51 | CUB | Cuba | 11.34 | 15.04 | 3.70 |
| 54 | PHL | Philippines | 20.07 | 23.54 | 3.47 |
| 63 | IRN | Iran, Islamic Rep. | 36.74 | 39.59 | 2.84 |
| 67 | PRY | Paraguay | 20.03 | 22.19 | 2.17 |
| 70 | MEX | Mexico | 21.11 | 22.95 | 1.84 |
| 71 | DOM | Dominican Republic | 23.90 | 25.71 | 1.80 |
| 72 | SLV | El Salvador | 17.64 | 19.20 | 1.57 |
| 73 | VNM | Viet Nam | 30.51 | 31.95 | 1.44 |
| 74 | BLR | Belarus | 25.05 | 26.48 | 1.43 |
| 75 | GEO | Georgia | 24.06 | 25.48 | 1.43 |
| 77 | COL | Colombia | 18.78 | 20.18 | 1.40 |
| 82 | LBY | Libya | 12.86 | 13.71 | 0.85 |
| 86 | PER | Peru | 20.51 | 21.13 | 0.62 |
| 93 | MDA | Moldova | 24.01 | 24.01 | 0.00 |
| 97 | BWA | Botswana | 28.93 | 28.55 | -0.38 |
| 98 | ARG | Argentina | 17.35 | 16.89 | -0.46 |
| 99 | ZAF | South Africa | 15.99 | 15.45 | -0.54 |
| 107 | BRA | Brazil | 17.77 | 16.41 | -1.37 |
| 109 | BLZ | Belize | 19.66 | 18.21 | -1.44 |
| 115 | FJI | Fiji | 22.63 | 20.42 | -2.21 |
| 117 | ALB | Albania | 28.83 | 26.48 | -2.35 |
| 121 | GTM | Guatemala | 17.67 | 15.02 | -2.64 |
| 123 | ARM | Armenia | 23.63 | 20.86 | -2.77 |
| 128 | THA | Thailand | 27.76 | 23.95 | -3.80 |
| 135 | GAB | Gabon | 25.85 | 20.92 | -4.93 |
| 136 | UKR | Ukraine | 21.40 | 16.39 | -5.01 |
| 138 | MUS | Mauritius | 24.57 | 18.84 | -5.72 |
| 141 | MYS | Malaysia | 29.90 | 23.20 | -6.70 |
| 144 | BIH | Bosnia and Herzegovina | 32.34 | 25.27 | -7.07 |
| 146 | IRQ | Iraq | 27.78 | 20.39 | -7.39 |
| 157 | AZE | Azerbaijan | 33.40 | 20.96 | -12.44 |

### Left out of the ranking (n/a in the first or last period of investment share): 58

- High income: AND (Andorra; n first=0, n last=0), ASM (American Samoa; n first=0, n last=0), ATG (Antigua and Barbuda; n first=0, n last=0), BMU (Bermuda; n first=0, n last=10), BRB (Barbados; n first=0, n last=0), CHI (Channel Islands; n first=0, n last=0), CUW (Curacao; n first=0, n last=4), CYM (Cayman Islands; n first=0, n last=0), GIB (Gibraltar; n first=0, n last=0), GUM (Guam; n first=0, n last=0), GUY (Guyana; n first=10, n last=0), IMN (Isle of Man; n first=0, n last=0), KNA (St. Kitts and Nevis; n first=0, n last=0), LIE (Liechtenstein; n first=0, n last=0), MAF (St. Martin (French part); n first=0, n last=0), MCO (Monaco; n first=0, n last=0), MNP (Northern Mariana Islands; n first=0, n last=0), NRU (Naoero; n first=0, n last=0), PLW (Palau; n first=0, n last=10), PYF (French Polynesia; n first=0, n last=10), SMR (San Marino; n first=0, n last=9), SXM (Sint Maarten (Dutch part); n first=0, n last=0), TCA (Turks and Caicos Islands; n first=0, n last=0), VGB (British Virgin Islands; n first=0, n last=0), VIR (Virgin Islands (U.S.); n first=0, n last=0)
- Low income: AFG (Afghanistan; n first=0, n last=5), BDI (Burundi; n first=0, n last=0), ERI (Eritrea; n first=10, n last=0), LBR (Liberia; n first=0, n last=0), MWI (Malawi; n first=0, n last=8), PRK (Korea, Dem. People's Rep.; n first=0, n last=0), SOM (Somalia, Fed. Rep.; n first=0, n last=10), SSD (South Sudan; n first=0, n last=1), SYR (Syrian Arab Republic; n first=0, n last=0)
- Lower middle income: DJI (Djibouti; n first=0, n last=10), KIR (Kiribati; n first=0, n last=10), LSO (Lesotho; n first=0, n last=10), MMR (Myanmar; n first=0, n last=0), NGA (Nigeria; n first=0, n last=0), PNG (Papua New Guinea; n first=10, n last=0), STP (Sao Tome and Principe; n first=0, n last=10), SWZ (Eswatini; n first=0, n last=10), ZMB (Zambia; n first=0, n last=10)
- Upper middle income: CPV (Cabo Verde; n first=0, n last=10), DMA (Dominica; n first=0, n last=0), FSM (Micronesia, Fed. Sts.; n first=0, n last=0), GNQ (Equatorial Guinea; n first=0, n last=10), GRD (Grenada; n first=0, n last=0), JAM (Jamaica; n first=0, n last=0), JOR (Jordan; n first=10, n last=0), LCA (St. Lucia; n first=0, n last=0), MDV (Maldives; n first=0, n last=10), SUR (Suriname; n first=0, n last=0), TKM (Turkmenistan; n first=9, n last=0), TUV (Tuvalu; n first=0, n last=0), VCT (St. Vincent and the Grenadines; n first=0, n last=0), WSM (Samoa; n first=0, n last=10), XKX (Kosovo; n first=0, n last=10)

## List: current account mean below 0 in all three periods: 84 countries

### High income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| ATG | Antigua and Barbuda | -7.16 (n=10) | -12.62 (n=10) | -9.71 (n=10) |
| AUS | Australia | -4.42 (n=10) | -4.80 (n=10) | -1.20 (n=10) |
| BHS | Bahamas, The | -6.69 (n=10) | -11.83 (n=10) | -10.49 (n=10) |
| BRB | Barbados | -3.57 (n=10) | -8.06 (n=10) | -4.92 (n=3) |
| CHL | Chile | -1.47 (n=10) | -0.79 (n=10) | -4.02 (n=10) |
| CRI | Costa Rica | -3.93 (n=10) | -4.72 (n=10) | -2.25 (n=10) |
| CYP | Cyprus | -2.80 (n=10) | -6.26 (n=10) | -5.84 (n=10) |
| EST | Estonia | -8.22 (n=10) | -4.30 (n=10) | -0.59 (n=10) |
| GBR | United Kingdom | -1.39 (n=10) | -3.28 (n=10) | -3.27 (n=10) |
| GRC | Greece | -5.30 (n=9) | -8.48 (n=10) | -5.09 (n=10) |
| GUY | Guyana | -9.10 (n=10) | -8.98 (n=10) | -7.74 (n=9) |
| HUN | Hungary | -6.69 (n=10) | -2.79 (n=10) | -0.43 (n=10) |
| KNA | St. Kitts and Nevis | -17.21 (n=10) | -9.89 (n=10) | -9.15 (n=10) |
| LVA | Latvia | -6.40 (n=10) | -7.14 (n=10) | -1.85 (n=10) |
| NZL | New Zealand | -2.62 (n=5) | -4.63 (n=10) | -4.09 (n=10) |
| PAN | Panama | -5.06 (n=10) | -7.76 (n=10) | -3.90 (n=10) |
| POL | Poland | -3.66 (n=10) | -4.47 (n=10) | -0.52 (n=10) |
| ROU | Romania | -5.49 (n=10) | -6.53 (n=10) | -5.22 (n=10) |
| SVK | Slovak Republic | -6.18 (n=10) | -3.98 (n=10) | -3.28 (n=10) |
| SYC | Seychelles | -10.59 (n=10) | -19.67 (n=10) | -7.28 (n=10) |
| URY | Uruguay | -1.02 (n=10) | -2.38 (n=10) | -0.89 (n=10) |
| USA | United States | -3.09 (n=10) | -3.54 (n=10) | -2.74 (n=10) |

### Low income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| BDI | Burundi | -2.79 (n=10) | -10.95 (n=10) | -13.71 (n=10) |
| ETH | Ethiopia | -2.34 (n=10) | -7.12 (n=10) | -5.96 (n=10) |
| GMB | Gambia, The | -2.41 (n=5) | -4.21 (n=10) | -4.79 (n=10) |
| GNB | Guinea-Bissau | -1.89 (n=7) | -4.12 (n=10) | -3.40 (n=10) |
| LBR | Liberia | -17.81 (n=1) | -29.52 (n=10) | -8.97 (n=10) |
| MDG | Madagascar | -5.70 (n=10) | -9.57 (n=10) | -2.54 (n=10) |
| MLI | Mali | -6.13 (n=10) | -5.11 (n=10) | -5.32 (n=10) |
| MWI | Malawi | -4.37 (n=10) | -9.23 (n=10) | -14.33 (n=10) |
| NER | Niger | -5.51 (n=10) | -11.18 (n=10) | -12.67 (n=10) |
| SDN | Sudan | -5.28 (n=10) | -8.76 (n=10) | -10.86 (n=10) |
| SLE | Sierra Leone | -9.13 (n=10) | -11.39 (n=10) | -8.99 (n=10) |
| UGA | Uganda | -3.79 (n=10) | -5.23 (n=10) | -6.99 (n=10) |

### Lower middle income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| BEN | Benin | -4.48 (n=10) | -5.29 (n=10) | -4.61 (n=9) |
| CMR | Cameroon | -2.76 (n=10) | -2.20 (n=10) | -3.57 (n=10) |
| COM | Comoros | -3.84 (n=3) | -4.54 (n=9) | -1.90 (n=9) |
| GHA | Ghana | -5.48 (n=10) | -8.91 (n=10) | -2.70 (n=10) |
| HND | Honduras | -5.37 (n=10) | -7.28 (n=10) | -3.63 (n=10) |
| HTI | Haiti | -1.70 (n=10) | -2.02 (n=10) | -1.54 (n=10) |
| IND | India | -0.39 (n=10) | -2.31 (n=10) | -1.05 (n=10) |
| KEN | Kenya | -8.10 (n=10) | -5.41 (n=10) | -4.60 (n=10) |
| KGZ | Kyrgyz Republic | -9.15 (n=10) | -10.01 (n=10) | -17.08 (n=10) |
| KHM | Cambodia | -4.36 (n=10) | -5.74 (n=10) | -8.37 (n=10) |
| LAO | Lao PDR | -5.20 (n=10) | -3.21 (n=10) | -4.45 (n=10) |
| LBN | Lebanon | -23.37 (n=3) | -16.61 (n=10) | -21.98 (n=9) |
| LSO | Lesotho | -9.80 (n=10) | -1.22 (n=10) | -6.99 (n=10) |
| NIC | Nicaragua | -16.34 (n=10) | -12.04 (n=10) | -1.09 (n=10) |
| PAK | Pakistan | -1.20 (n=10) | -2.67 (n=10) | -2.31 (n=10) |
| PSE | West Bank and Gaza | -28.20 (n=10) | -14.11 (n=10) | -13.09 (n=10) |
| SEN | Senegal | -4.26 (n=10) | -7.32 (n=10) | -10.79 (n=9) |
| SLB | Solomon Islands | -5.51 (n=10) | -7.46 (n=10) | -6.06 (n=10) |
| STP | Sao Tome and Principe | -24.61 (n=8) | -40.08 (n=10) | -17.80 (n=10) |
| TGO | Togo | -6.40 (n=10) | -5.78 (n=10) | -3.40 (n=6) |
| TUN | Tunisia | -2.96 (n=10) | -4.80 (n=10) | -7.06 (n=10) |
| TZA | Tanzania | -3.96 (n=10) | -8.50 (n=10) | -3.65 (n=10) |
| VUT | Vanuatu | -4.45 (n=10) | -6.79 (n=10) | -5.27 (n=8) |

### Upper middle income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| ALB | Albania | -5.34 (n=10) | -10.91 (n=10) | -6.44 (n=10) |
| ARM | Armenia | -13.54 (n=10) | -9.21 (n=10) | -3.68 (n=10) |
| BIH | Bosnia and Herzegovina | -13.15 (n=7) | -9.04 (n=10) | -3.51 (n=10) |
| BLR | Belarus | -3.90 (n=10) | -7.12 (n=10) | -0.65 (n=10) |
| BLZ | Belize | -8.91 (n=10) | -4.35 (n=10) | -5.99 (n=10) |
| BRA | Brazil | -2.59 (n=10) | -2.07 (n=10) | -2.30 (n=10) |
| COL | Colombia | -2.24 (n=10) | -2.82 (n=10) | -4.19 (n=10) |
| CPV | Cabo Verde | -10.73 (n=10) | -10.07 (n=10) | -4.89 (n=10) |
| DMA | Dominica | -11.89 (n=10) | -15.46 (n=10) | -27.57 (n=10) |
| DOM | Dominican Republic | -0.71 (n=10) | -5.27 (n=10) | -2.29 (n=10) |
| FJI | Fiji | -2.60 (n=10) | -8.09 (n=10) | -8.32 (n=10) |
| GEO | Georgia | -8.02 (n=8) | -12.65 (n=10) | -8.06 (n=10) |
| GRD | Grenada | -19.51 (n=10) | -22.33 (n=10) | -13.88 (n=10) |
| JAM | Jamaica | -5.01 (n=10) | -11.36 (n=10) | -0.41 (n=10) |
| LCA | St. Lucia | -13.08 (n=10) | -14.19 (n=10) | -3.99 (n=10) |
| LKA | Sri Lanka | -3.10 (n=10) | -4.24 (n=10) | -1.58 (n=10) |
| MDA | Moldova | -7.49 (n=10) | -9.48 (n=10) | -10.04 (n=10) |
| MDV | Maldives | -6.24 (n=10) | -12.82 (n=10) | -20.65 (n=10) |
| MEX | Mexico | -1.48 (n=10) | -1.08 (n=10) | -0.95 (n=10) |
| MKD | North Macedonia | -5.84 (n=9) | -3.92 (n=10) | -2.14 (n=10) |
| MNG | Mongolia | -2.81 (n=10) | -15.42 (n=10) | -9.63 (n=10) |
| PER | Peru | -3.87 (n=10) | -1.53 (n=10) | -1.32 (n=10) |
| SLV | El Salvador | -2.67 (n=10) | -5.29 (n=10) | -2.55 (n=10) |
| TON | Tonga | -5.08 (n=4) | -15.68 (n=10) | -6.35 (n=10) |
| TUR | Turkiye | -1.05 (n=10) | -4.97 (n=10) | -2.37 (n=10) |
| VCT | St. Vincent and the Grenadines | -12.57 (n=10) | -23.28 (n=10) | -14.69 (n=10) |
| ZAF | South Africa | -0.81 (n=10) | -3.74 (n=10) | -1.12 (n=10) |

## List: current account mean below 0 in 1995-2004 and above 0 in 2015-2024: 22 countries

### High income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| ABW | Aruba | -3.03 (n=10) | -0.82 (n=10) | 1.53 (n=9) |
| BGR | Bulgaria | -2.56 (n=10) | -8.30 (n=10) | 0.73 (n=10) |
| CZE | Czechia | -4.21 (n=10) | -2.10 (n=10) | 0.11 (n=10) |
| ESP | Spain | -2.67 (n=10) | -4.04 (n=10) | 1.99 (n=10) |
| HRV | Croatia | -5.80 (n=10) | -4.59 (n=10) | 0.82 (n=10) |
| ISL | Iceland | -4.60 (n=10) | -8.51 (n=10) | 2.48 (n=10) |
| ISR | Israel | -2.50 (n=10) | 2.00 (n=10) | 3.02 (n=10) |
| LTU | Lithuania | -7.85 (n=10) | -4.45 (n=10) | 0.85 (n=10) |
| MLT | Malta | -5.62 (n=10) | -1.59 (n=10) | 8.87 (n=10) |
| PRT | Portugal | -6.96 (n=10) | -6.77 (n=10) | 0.47 (n=10) |
| SVN | Slovenia | -0.83 (n=10) | -0.54 (n=10) | 4.82 (n=10) |

### Lower middle income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| AGO | Angola | -3.92 (n=10) | 7.41 (n=10) | 3.01 (n=10) |
| GIN | Guinea | -3.18 (n=10) | -8.94 (n=10) | 2.75 (n=10) |
| SWZ | Eswatini | -0.61 (n=10) | -1.72 (n=10) | 4.33 (n=10) |
| TJK | Tajikistan | -1.43 (n=3) | -13.25 (n=10) | 2.30 (n=10) |
| ZMB | Zambia | -13.07 (n=8) | 1.88 (n=10) | 0.94 (n=10) |

### Upper middle income

| code | country | mean 1995-2004 | mean 2005-2014 | mean 2015-2024 |
|---|---|---|---|---|
| AZE | Azerbaijan | -18.68 (n=10) | 20.89 (n=10) | 8.33 (n=10) |
| ECU | Ecuador | -1.19 (n=10) | 0.76 (n=10) | 1.05 (n=10) |
| GTM | Guatemala | -4.93 (n=10) | -3.54 (n=10) | 1.85 (n=10) |
| PRY | Paraguay | -0.01 (n=10) | 0.34 (n=10) | 0.05 (n=10) |
| TUV | Tuvalu | -29.51 (n=4) | -16.40 (n=10) | 13.44 (n=9) |
| VNM | Viet Nam | -1.87 (n=9) | -1.77 (n=10) | 2.03 (n=10) |

## Top 10 mean export volume growth per period (ties: code ascending)

### 1995-2004

| # | code | country | incomeLevel | mean | n |
|---|---|---|---|---|---|
| 1 | SRB | Serbia | Upper middle income | 31.86 | 9 |
| 2 | ZMB | Zambia | Lower middle income | 27.94 | 10 |
| 3 | LSO | Lesotho | Lower middle income | 23.62 | 10 |
| 4 | SDN | Sudan | Low income | 23.45 | 10 |
| 5 | MOZ | Mozambique | Low income | 23.28 | 10 |
| 6 | RWA | Rwanda | Low income | 22.06 | 10 |
| 7 | ALB | Albania | Upper middle income | 21.38 | 9 |
| 8 | KHM | Cambodia | Lower middle income | 21.08 | 10 |
| 9 | VNM | Viet Nam | Upper middle income | 19.62 | 10 |
| 10 | LBN | Lebanon | Lower middle income | 18.46 | 10 |

- Low income: #4 SDN, #5 MOZ, #6 RWA
- Lower middle income: #2 ZMB, #3 LSO, #8 KHM, #10 LBN
- Upper middle income: #1 SRB, #7 ALB, #9 VNM

### 2005-2014

| # | code | country | incomeLevel | mean | n |
|---|---|---|---|---|---|
| 1 | ERI | Eritrea | Low income | 87.00 | 7 |
| 2 | LBY | Libya | Upper middle income | 39.41 | 10 |
| 3 | TKM | Turkmenistan | Upper middle income | 33.77 | 2 |
| 4 | STP | Sao Tome and Principe | Lower middle income | 27.04 | 6 |
| 5 | MNG | Mongolia | Upper middle income | 23.14 | 4 |
| 6 | ZMB | Zambia | Lower middle income | 22.31 | 6 |
| 7 | HTI | Haiti | Lower middle income | 21.87 | 10 |
| 8 | SLE | Sierra Leone | Low income | 20.21 | 10 |
| 9 | AZE | Azerbaijan | Upper middle income | 17.71 | 10 |
| 10 | COD | Congo, Dem. Rep. | Low income | 17.36 | 10 |

- Low income: #1 ERI, #8 SLE, #10 COD
- Lower middle income: #4 STP, #6 ZMB, #7 HTI
- Upper middle income: #2 LBY, #3 TKM, #5 MNG, #9 AZE

### 2015-2024

| # | code | country | incomeLevel | mean | n |
|---|---|---|---|---|---|
| 1 | TLS | Timor-Leste | Lower middle income | 104.70 | 10 |
| 2 | MNP | Northern Mariana Islands | High income | 29.25 | 8 |
| 3 | GIN | Guinea | Lower middle income | 19.72 | 10 |
| 4 | LBY | Libya | Upper middle income | 19.53 | 10 |
| 5 | RWA | Rwanda | Low income | 18.59 | 10 |
| 6 | SLE | Sierra Leone | Low income | 17.95 | 10 |
| 7 | ARM | Armenia | Upper middle income | 17.86 | 10 |
| 8 | EGY | Egypt, Arab Rep. | Lower middle income | 14.05 | 10 |
| 9 | SYR | Syrian Arab Republic | Low income | 13.87 | 8 |
| 10 | XKX | Kosovo | Upper middle income | 13.21 | 10 |

- High income: #2 MNP
- Low income: #5 RWA, #6 SLE, #9 SYR
- Lower middle income: #1 TLS, #3 GIN, #8 EGY
- Upper middle income: #4 LBY, #7 ARM, #10 XKX

## Scorecard per country (pull 3)

Each cell: mean (n). Grouped by incomeLevel; code ascending within a group.

### High income

| code | country | region | EXP 95-04 | EXP 05-14 | EXP 15-24 | EXP change | INV 95-04 | INV 05-14 | INV 15-24 | INV change | CA 95-04 | CA 05-14 | CA 15-24 | CA change |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| ABW | Aruba | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | 28.59 (10) | 28.73 (10) | 21.56 (10) | -7.02 | -3.03 (10) | -0.82 (10) | 1.53 (9) | 4.56 |
| AND | Andorra | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | 15.08 (6) | n/a |
| ARE | United Arab Emirates | Middle East, North Africa, Afghanistan & Pakistan | 16.87 (3) | 8.92 (10) | 3.70 (9) | -13.17 | 21.79 (4) | 24.17 (10) | 23.16 (9) | 1.37 | n/a (0) | n/a (0) | 14.83 (2) | n/a |
| ASM | American Samoa | East Asia & Pacific | -9.15 (2) | -4.07 (10) | -2.69 (8) | 6.46 | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| ATG | Antigua and Barbuda | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -7.16 (10) | -12.62 (10) | -9.71 (10) | -2.55 |
| AUS | Australia | East Asia & Pacific | 5.16 (10) | 3.86 (10) | 2.68 (10) | -2.48 | 25.41 (10) | 27.32 (10) | 24.06 (10) | -1.35 | -4.42 (10) | -4.80 (10) | -1.20 (10) | 3.22 |
| AUT | Austria | Europe & Central Asia | 6.99 (10) | 3.36 (10) | 2.56 (10) | -4.43 | 25.63 (10) | 23.95 (10) | 25.70 (10) | 0.07 | n/a (0) | 2.63 (10) | 1.58 (10) | n/a |
| BEL | Belgium | Europe & Central Asia | 5.25 (10) | 2.73 (10) | 2.27 (10) | -2.98 | 22.16 (10) | 23.66 (10) | 24.78 (10) | 2.62 | 3.66 (3) | 0.76 (10) | 0.39 (10) | -3.27 |
| BGR | Bulgaria | Europe & Central Asia | 7.34 (10) | 6.28 (10) | 3.38 (10) | -3.96 | 17.36 (10) | 26.71 (10) | 20.54 (10) | 3.18 | -2.56 (10) | -8.30 (10) | 0.73 (10) | 3.29 |
| BHR | Bahrain | Middle East, North Africa, Afghanistan & Pakistan | 4.25 (4) | 5.72 (10) | 3.27 (10) | -0.98 | 16.65 (10) | 28.55 (10) | 30.57 (10) | 13.92 | 1.19 (10) | 7.89 (10) | 0.36 (10) | -0.83 |
| BHS | Bahamas, The | Latin America & Caribbean | 1.22 (10) | 4.54 (10) | 3.97 (10) | 2.75 | 27.68 (10) | 29.90 (10) | 25.00 (10) | -2.69 | -6.69 (10) | -11.83 (10) | -10.49 (10) | -3.80 |
| BMU | Bermuda | North America | n/a (0) | n/a (0) | 2.55 (10) | n/a | n/a (0) | 11.93 (5) | 12.67 (10) | n/a | n/a (0) | 13.84 (9) | 13.70 (10) | n/a |
| BRB | Barbados | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -3.57 (10) | -8.06 (10) | -4.92 (3) | -1.36 |
| BRN | Brunei Darussalam | East Asia & Pacific | 3.04 (10) | -1.66 (10) | 2.74 (10) | -0.30 | 22.91 (10) | 24.75 (10) | 33.97 (10) | 11.06 | 31.96 (4) | 34.52 (10) | 12.18 (10) | -19.77 |
| CAN | Canada | North America | 5.51 (10) | 0.98 (10) | 1.83 (10) | -3.68 | 20.31 (10) | 23.84 (10) | 23.54 (10) | 3.22 | 0.66 (10) | -1.41 (10) | -1.74 (10) | -2.40 |
| CHE | Switzerland | Europe & Central Asia | 4.61 (10) | 4.66 (10) | 2.67 (10) | -1.94 | 27.81 (10) | 27.35 (10) | 27.63 (10) | -0.18 | 8.67 (10) | 8.73 (10) | 6.30 (10) | -2.37 |
| CHI | Channel Islands | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| CHL | Chile | Latin America & Caribbean | 8.77 (10) | 2.14 (10) | 0.55 (10) | -8.22 | 25.50 (10) | 25.25 (10) | 23.85 (10) | -1.65 | -1.47 (10) | -0.79 (10) | -4.02 (10) | -2.55 |
| CRI | Costa Rica | Latin America & Caribbean | 6.82 (10) | 4.55 (10) | 6.61 (10) | -0.21 | 19.97 (10) | 20.50 (10) | 17.34 (10) | -2.63 | -3.93 (10) | -4.72 (10) | -2.25 (10) | 1.68 |
| CUW | Curacao | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | 34.31 (10) | 31.74 (4) | n/a | n/a (0) | -25.36 (4) | -21.75 (9) | n/a |
| CYM | Cayman Islands | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | -13.13 (9) | n/a |
| CYP | Cyprus | Europe & Central Asia | 4.05 (10) | 2.57 (10) | 10.38 (10) | 6.33 | 21.34 (10) | 20.56 (10) | 19.22 (10) | -2.12 | -2.80 (10) | -6.26 (10) | -5.84 (10) | -3.04 |
| CZE | Czechia | Europe & Central Asia | 10.73 (10) | 7.49 (10) | 3.06 (10) | -7.67 | 31.66 (10) | 27.76 (10) | 26.74 (10) | -4.92 | -4.21 (10) | -2.10 (10) | 0.11 (10) | 4.32 |
| DEU | Germany | Europe & Central Asia | 7.28 (10) | 4.35 (10) | 1.65 (10) | -5.63 | 22.46 (10) | 19.85 (10) | 21.41 (10) | -1.05 | 0.01 (10) | 6.00 (10) | 7.02 (10) | 7.01 |
| DNK | Denmark | Europe & Central Asia | 4.94 (10) | 3.27 (10) | 4.24 (10) | -0.70 | 21.39 (10) | 21.03 (10) | 22.69 (10) | 1.30 | 1.56 (10) | 5.01 (10) | 8.47 (10) | 6.91 |
| ESP | Spain | Europe & Central Asia | 7.35 (10) | 2.94 (10) | 3.21 (10) | -4.14 | 25.25 (10) | 23.95 (10) | 20.71 (10) | -4.54 | -2.67 (10) | -4.04 (10) | 1.99 (10) | 4.65 |
| EST | Estonia | Europe & Central Asia | 7.67 (10) | 8.13 (10) | 3.04 (10) | -4.63 | 30.30 (10) | 29.56 (10) | 26.77 (10) | -3.53 | -8.22 (10) | -4.30 (10) | -0.59 (10) | 7.63 |
| FIN | Finland | Europe & Central Asia | 7.84 (10) | 2.00 (10) | 2.43 (10) | -5.41 | 22.20 (10) | 23.63 (10) | 24.25 (10) | 2.05 | 6.20 (10) | 1.07 (10) | -0.85 (10) | -7.05 |
| FRA | France | Europe & Central Asia | 6.06 (10) | 2.56 (10) | 2.57 (10) | -3.49 | 20.52 (10) | 22.14 (10) | 22.58 (10) | 2.06 | 1.57 (10) | -0.67 (10) | -0.59 (10) | -2.17 |
| FRO | Faroe Islands | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | 25.38 (7) | 23.19 (10) | 27.59 (10) | 2.21 | 10.68 (7) | 1.57 (7) | n/a (0) | n/a |
| GBR | United Kingdom | Europe & Central Asia | 5.41 (10) | 2.76 (10) | 2.46 (10) | -2.95 | 18.65 (10) | 17.60 (10) | 18.73 (10) | 0.07 | -1.39 (10) | -3.28 (10) | -3.27 (10) | -1.88 |
| GIB | Gibraltar | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| GRC | Greece | Europe & Central Asia | 9.04 (10) | 2.13 (10) | 3.95 (10) | -5.10 | 23.69 (10) | 18.77 (10) | 14.57 (10) | -9.11 | -5.30 (9) | -8.48 (10) | -5.09 (10) | 0.21 |
| GRL | Greenland | Europe & Central Asia | 9.99 (1) | 2.50 (10) | 0.73 (9) | -9.27 | 17.84 (2) | 35.70 (10) | 29.90 (9) | 12.06 | n/a (0) | n/a (0) | n/a (0) | n/a |
| GUM | Guam | East Asia & Pacific | 4.86 (2) | -0.48 (10) | 6.83 (8) | 1.98 | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| GUY | Guyana | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | 26.16 (10) | 32.33 (1) | n/a (0) | n/a | -9.10 (10) | -8.98 (10) | -7.74 (9) | 1.36 |
| HKG | Hong Kong SAR, China | East Asia & Pacific | 7.39 (10) | 5.94 (10) | -0.09 (10) | -7.48 | 27.53 (10) | 22.87 (10) | 18.85 (10) | -8.68 | 6.76 (7) | 7.95 (10) | 7.20 (10) | 0.44 |
| HRV | Croatia | Europe & Central Asia | 7.47 (9) | 2.00 (10) | 7.14 (10) | -0.34 | 21.85 (10) | 23.04 (10) | 22.51 (10) | 0.66 | -5.80 (10) | -4.59 (10) | 0.82 (10) | 6.62 |
| HUN | Hungary | Europe & Central Asia | 15.91 (10) | 7.35 (10) | 4.22 (10) | -11.69 | 26.36 (10) | 23.24 (10) | 26.75 (10) | 0.39 | -6.69 (10) | -2.79 (10) | -0.43 (10) | 6.26 |
| IMN | Isle of Man | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| IRL | Ireland | Europe & Central Asia | 13.50 (10) | 5.46 (10) | 11.50 (10) | -2.00 | 23.62 (10) | 23.10 (10) | 31.10 (10) | 7.49 | n/a (0) | -1.63 (10) | 3.00 (10) | n/a |
| ISL | Iceland | Europe & Central Asia | 3.87 (10) | 5.47 (10) | 3.30 (10) | -0.56 | 22.02 (10) | 21.25 (10) | 22.38 (10) | 0.36 | -4.60 (10) | -8.51 (10) | 2.48 (10) | 7.08 |
| ISR | Israel | Middle East, North Africa, Afghanistan & Pakistan | 8.39 (10) | 4.42 (10) | 2.91 (10) | -5.47 | 26.03 (10) | 23.04 (10) | 24.56 (10) | -1.47 | -2.50 (10) | 2.00 (10) | 3.02 (10) | 5.52 |
| ITA | Italy | Europe & Central Asia | 3.73 (10) | 1.76 (10) | 2.47 (10) | -1.27 | 20.93 (10) | 20.18 (10) | 20.00 (10) | -0.92 | 0.83 (10) | -1.16 (10) | 1.75 (10) | 0.92 |
| JPN | Japan | East Asia & Pacific | 5.80 (10) | 3.95 (10) | 2.32 (10) | -3.48 | 29.78 (10) | 25.62 (10) | 27.19 (10) | -2.59 | 2.50 (9) | 2.57 (10) | 3.46 (10) | 0.96 |
| KNA | St. Kitts and Nevis | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -17.21 (10) | -9.89 (10) | -9.15 (10) | 8.06 |
| KOR | Korea, Rep. | East Asia & Pacific | 14.14 (10) | 8.12 (10) | 3.19 (10) | -10.95 | 33.71 (10) | 31.92 (10) | 31.29 (10) | -2.42 | 1.47 (10) | 2.38 (10) | 4.22 (10) | 2.75 |
| KWT | Kuwait | Middle East, North Africa, Afghanistan & Pakistan | n/a (0) | 4.83 (4) | -0.36 (10) | n/a | 15.34 (10) | 16.33 (10) | 21.42 (10) | 6.08 | 21.20 (10) | 37.96 (10) | 19.12 (10) | -2.09 |
| LIE | Liechtenstein | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| LTU | Lithuania | Europe & Central Asia | 12.15 (9) | 8.10 (10) | 6.54 (10) | -5.61 | 21.85 (10) | 22.62 (10) | 21.47 (10) | -0.37 | -7.85 (10) | -4.45 (10) | 0.85 (10) | 8.70 |
| LUX | Luxembourg | Europe & Central Asia | 8.78 (10) | 4.55 (10) | 2.29 (10) | -6.49 | 21.53 (10) | 19.01 (10) | 17.73 (10) | -3.79 | 8.11 (6) | 5.87 (10) | 5.95 (10) | -2.16 |
| LVA | Latvia | Europe & Central Asia | 8.41 (9) | 7.73 (10) | 3.05 (10) | -5.36 | 25.29 (10) | 30.84 (10) | 23.45 (10) | -1.83 | -6.40 (10) | -7.14 (10) | -1.85 (10) | 4.55 |
| MAC | Macao SAR, China | East Asia & Pacific | 7.88 (10) | 11.69 (10) | 8.44 (10) | 0.56 | 15.57 (10) | 22.00 (10) | 20.02 (10) | 4.45 | 31.70 (3) | 29.35 (10) | 23.94 (10) | -7.76 |
| MAF | St. Martin (French part) | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| MCO | Monaco | Europe & Central Asia | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| MLT | Malta | Middle East, North Africa, Afghanistan & Pakistan | -2.27 (4) | 6.88 (10) | 9.99 (10) | 12.26 | 24.14 (10) | 20.53 (10) | 21.36 (10) | -2.78 | -5.62 (10) | -1.59 (10) | 8.87 (10) | 14.49 |
| MNP | Northern Mariana Islands | East Asia & Pacific | 2.02 (2) | -11.60 (10) | 29.25 (8) | 27.23 | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| NCL | New Caledonia | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | 24.29 (7) | 37.66 (10) | 27.62 (10) | 3.33 | 0.24 (3) | -11.42 (10) | -10.15 (2) | -10.40 |
| NLD | Netherlands | Europe & Central Asia | 6.26 (10) | 3.86 (10) | 2.92 (10) | -3.34 | 21.86 (10) | 20.19 (10) | 21.06 (10) | -0.81 | 4.11 (10) | 6.48 (10) | 7.65 (10) | 3.54 |
| NOR | Norway | Europe & Central Asia | 3.62 (10) | 0.25 (10) | 2.15 (10) | -1.47 | 22.12 (10) | 24.41 (10) | 25.23 (10) | 3.11 | 8.95 (10) | 12.81 (10) | 10.28 (10) | 1.33 |
| NRU | Naoero | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | 43.83 (7) | 2.28 (10) | n/a |
| NZL | New Zealand | East Asia & Pacific | 4.58 (10) | 2.12 (10) | 1.56 (10) | -3.02 | 23.09 (10) | 22.45 (10) | 24.06 (10) | 0.97 | -2.62 (5) | -4.63 (10) | -4.09 (10) | -1.48 |
| OMN | Oman | Middle East, North Africa, Afghanistan & Pakistan | 2.77 (6) | 4.17 (10) | 2.75 (10) | -0.02 | 24.21 (10) | 32.61 (10) | 29.91 (10) | 5.70 | 1.39 (10) | 7.80 (10) | -6.67 (10) | -8.06 |
| PAN | Panama | Latin America & Caribbean | 1.89 (8) | 8.67 (10) | 4.50 (10) | 2.61 | 27.53 (10) | 36.74 (10) | 36.54 (10) | 9.01 | -5.06 (10) | -7.76 (10) | -3.90 (10) | 1.17 |
| PLW | Palau | East Asia & Pacific | n/a (0) | 1.69 (9) | 10.64 (10) | n/a | n/a (0) | 31.68 (10) | 34.84 (10) | n/a | n/a (0) | -15.77 (10) | -30.79 (9) | n/a |
| POL | Poland | Europe & Central Asia | 9.51 (9) | 7.13 (10) | 6.11 (10) | -3.39 | 21.95 (10) | 21.70 (10) | 20.11 (10) | -1.84 | -3.66 (10) | -4.47 (10) | -0.52 (10) | 3.14 |
| PRI | Puerto Rico (US) | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | 17.48 (10) | 11.26 (10) | 12.06 (10) | -5.42 | n/a (0) | n/a (0) | n/a (0) | n/a |
| PRT | Portugal | Europe & Central Asia | 5.62 (10) | 3.94 (10) | 4.61 (10) | -1.01 | 26.22 (10) | 19.94 (10) | 18.93 (10) | -7.30 | -6.96 (10) | -6.77 (10) | 0.47 (10) | 7.44 |
| PYF | French Polynesia | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | 20.98 (10) | 22.11 (10) | n/a | 0.36 (3) | 0.98 (10) | 6.48 (2) | 6.12 |
| QAT | Qatar | Middle East, North Africa, Afghanistan & Pakistan | 13.96 (8) | 11.99 (10) | -1.48 (6) | -15.44 | 30.54 (10) | 35.34 (10) | 40.83 (8) | 10.28 | n/a (0) | 29.66 (4) | 9.25 (10) | n/a |
| ROU | Romania | Europe & Central Asia | 9.10 (10) | 10.80 (10) | 4.79 (10) | -4.30 | 21.38 (10) | 27.42 (10) | 24.96 (10) | 3.59 | -5.49 (10) | -6.53 (10) | -5.22 (10) | 0.27 |
| RUS | Russian Federation | Europe & Central Asia | 7.62 (10) | 2.97 (10) | 2.46 (7) | -5.16 | 20.33 (10) | 22.69 (10) | 23.69 (10) | 3.35 | 6.94 (10) | 5.30 (10) | 4.47 (10) | -2.48 |
| SAU | Saudi Arabia | Middle East, North Africa, Afghanistan & Pakistan | 3.89 (4) | 1.27 (10) | 1.57 (10) | -2.33 | 20.01 (10) | 26.69 (10) | 27.16 (10) | 7.15 | 4.02 (10) | 20.12 (10) | 1.35 (10) | -2.66 |
| SGP | Singapore | East Asia & Pacific | 9.56 (10) | 6.70 (10) | 4.40 (10) | -5.16 | 29.92 (10) | 26.75 (10) | 23.98 (10) | -5.95 | 16.97 (10) | 20.52 (10) | 17.58 (10) | 0.61 |
| SMR | San Marino | Europe & Central Asia | n/a (0) | n/a (0) | 3.97 (8) | n/a | n/a (0) | n/a (0) | 19.06 (9) | n/a | n/a (0) | n/a (0) | 6.22 (7) | n/a |
| SVK | Slovak Republic | Europe & Central Asia | 9.15 (10) | 8.26 (10) | 2.86 (10) | -6.29 | 30.32 (10) | 25.78 (10) | 22.82 (10) | -7.50 | -6.18 (10) | -3.98 (10) | -3.28 (10) | 2.90 |
| SVN | Slovenia | Europe & Central Asia | 6.93 (10) | 5.34 (10) | 4.70 (10) | -2.23 | 27.03 (10) | 25.23 (10) | 21.16 (10) | -5.88 | -0.83 (10) | -0.54 (10) | 4.82 (10) | 5.66 |
| SWE | Sweden | Europe & Central Asia | 7.47 (10) | 2.88 (10) | 4.01 (10) | -3.46 | 21.15 (10) | 22.46 (10) | 25.00 (10) | 3.85 | 4.12 (10) | 6.13 (10) | 4.38 (10) | 0.26 |
| SXM | Sint Maarten (Dutch part) | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | 0.30 (4) | -6.66 (9) | n/a |
| SYC | Seychelles | Sub-Saharan Africa | 7.29 (10) | 7.68 (10) | 3.58 (10) | -3.71 | 29.91 (10) | 31.63 (10) | 22.26 (10) | -7.65 | -10.59 (10) | -19.67 (10) | -7.28 (10) | 3.31 |
| TCA | Turks and Caicos Islands | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | 11.27 (1) | 12.71 (4) | n/a |
| TTO | Trinidad and Tobago | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | 21.59 (5) | 21.66 (10) | 20.76 (9) | -0.83 | 2.09 (10) | 21.11 (10) | 4.54 (10) | 2.45 |
| URY | Uruguay | Latin America & Caribbean | 5.28 (10) | 5.95 (10) | 2.87 (10) | -2.41 | 15.44 (10) | 20.64 (10) | 16.86 (10) | 1.42 | -1.02 (10) | -2.38 (10) | -0.89 (10) | 0.13 |
| USA | United States | North America | 5.02 (10) | 5.34 (10) | 1.62 (10) | -3.40 | 22.37 (10) | 20.72 (10) | 21.47 (10) | -0.91 | -3.09 (10) | -3.54 (10) | -2.74 (10) | 0.35 |
| VGB | British Virgin Islands | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| VIR | Virgin Islands (U.S.) | Latin America & Caribbean | 11.55 (2) | -11.04 (10) | 7.47 (8) | -4.08 | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |

### Low income

| code | country | region | EXP 95-04 | EXP 05-14 | EXP 15-24 | EXP change | INV 95-04 | INV 05-14 | INV 15-24 | INV change | CA 95-04 | CA 05-14 | CA 15-24 | CA change |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| AFG | Afghanistan | Middle East, North Africa, Afghanistan & Pakistan | n/a (0) | n/a (0) | 3.35 (4) | n/a | n/a (0) | n/a (0) | 14.72 (5) | n/a | n/a (0) | -11.90 (7) | -18.88 (6) | n/a |
| BDI | Burundi | Sub-Saharan Africa | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -2.79 (10) | -10.95 (10) | -13.71 (10) | -10.92 |
| BFA | Burkina Faso | Sub-Saharan Africa | 4.10 (10) | 16.81 (10) | 3.83 (10) | -0.27 | 19.03 (10) | 20.44 (10) | 19.65 (10) | 0.63 | n/a (0) | -6.18 (10) | -3.94 (10) | n/a |
| CAF | Central African Republic | Sub-Saharan Africa | n/a (0) | 16.72 (5) | -2.28 (10) | n/a | 9.96 (10) | 12.76 (10) | 24.49 (10) | 14.53 | n/a (0) | n/a (0) | n/a (0) | n/a |
| COD | Congo, Dem. Rep. | Sub-Saharan Africa | 16.42 (10) | 17.36 (10) | 9.99 (10) | -6.43 | 9.52 (10) | 22.35 (10) | 28.91 (10) | 19.38 | n/a (0) | -3.81 (10) | -3.50 (10) | n/a |
| ERI | Eritrea | Sub-Saharan Africa | -2.27 (10) | 87.00 (7) | n/a (0) | n/a | 29.28 (10) | 13.38 (7) | n/a (0) | n/a | -16.29 (6) | n/a (0) | n/a (0) | n/a |
| ETH | Ethiopia | Sub-Saharan Africa | n/a (0) | -2.42 (3) | 2.67 (10) | n/a | 0.00 (10) | 14.13 (10) | 31.26 (10) | 31.26 | -2.34 (10) | -7.12 (10) | -5.96 (10) | -3.63 |
| GMB | Gambia, The | Sub-Saharan Africa | n/a (0) | 2.90 (10) | 1.29 (10) | n/a | 7.59 (10) | 14.45 (10) | 26.25 (10) | 18.66 | -2.41 (5) | -4.21 (10) | -4.79 (10) | -2.38 |
| GNB | Guinea-Bissau | Sub-Saharan Africa | 10.37 (7) | 7.36 (10) | 0.36 (10) | -10.00 | 26.30 (10) | 19.24 (10) | 21.40 (10) | -4.90 | -1.89 (7) | -4.12 (10) | -3.40 (10) | -1.51 |
| LBR | Liberia | Sub-Saharan Africa | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -17.81 (1) | -29.52 (10) | -8.97 (10) | 8.83 |
| MDG | Madagascar | Sub-Saharan Africa | 4.09 (10) | 9.49 (10) | 7.41 (10) | 3.31 | 12.54 (10) | 24.57 (10) | 19.12 (10) | 6.59 | -5.70 (10) | -9.57 (10) | -2.54 (10) | 3.16 |
| MLI | Mali | Sub-Saharan Africa | 11.08 (10) | -0.37 (10) | 3.93 (10) | -7.15 | 20.73 (10) | 21.89 (10) | 23.67 (10) | 2.93 | -6.13 (10) | -5.11 (10) | -5.32 (10) | 0.81 |
| MOZ | Mozambique | Sub-Saharan Africa | 23.28 (10) | 10.88 (10) | 2.45 (10) | -20.82 | 33.90 (10) | 32.67 (10) | 37.31 (10) | 3.41 | n/a (0) | -18.95 (10) | -23.53 (10) | n/a |
| MWI | Malawi | Sub-Saharan Africa | n/a (0) | n/a (0) | 4.24 (7) | n/a | n/a (0) | n/a (0) | 17.65 (8) | n/a | -4.37 (10) | -9.23 (10) | -14.33 (10) | -9.95 |
| NER | Niger | Sub-Saharan Africa | 2.94 (10) | 9.41 (10) | 0.76 (10) | -2.19 | 13.41 (10) | 26.74 (10) | 31.04 (10) | 17.63 | -5.51 (10) | -11.18 (10) | -12.67 (10) | -7.16 |
| PRK | Korea, Dem. People's Rep. | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| RWA | Rwanda | Sub-Saharan Africa | 22.06 (10) | 10.92 (10) | 18.59 (10) | -3.47 | 38.03 (10) | 23.14 (10) | 27.95 (10) | -10.08 | n/a (0) | -8.50 (5) | -11.43 (10) | n/a |
| SDN | Sudan | Sub-Saharan Africa | 23.45 (10) | 1.49 (10) | -2.29 (10) | -25.74 | 15.98 (10) | 20.40 (10) | 7.37 (10) | -8.61 | -5.28 (10) | -8.76 (10) | -10.86 (10) | -5.58 |
| SLE | Sierra Leone | Sub-Saharan Africa | 14.50 (10) | 20.21 (10) | 17.95 (10) | 3.45 | 6.54 (10) | 19.77 (10) | 17.10 (10) | 10.55 | -9.13 (10) | -11.39 (10) | -8.99 (10) | 0.14 |
| SOM | Somalia, Fed. Rep. | Sub-Saharan Africa | n/a (0) | 10.36 (1) | 12.08 (10) | n/a | n/a (0) | 14.51 (3) | 18.00 (10) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| SSD | South Sudan | Sub-Saharan Africa | n/a (0) | 11.28 (6) | -52.31 (1) | n/a | n/a (0) | 10.52 (7) | 5.75 (1) | n/a | n/a (0) | -5.66 (1) | -5.92 (9) | n/a |
| SYR | Syrian Arab Republic | Middle East, North Africa, Afghanistan & Pakistan | 6.21 (10) | -14.90 (10) | 13.87 (8) | 7.66 | n/a (0) | n/a (0) | n/a (0) | n/a | 3.18 (10) | 0.55 (6) | n/a (0) | n/a |
| TCD | Chad | Sub-Saharan Africa | 15.69 (9) | -2.61 (9) | 5.46 (10) | -10.23 | 28.36 (10) | 21.86 (10) | 20.56 (10) | -7.81 | n/a (0) | n/a (0) | n/a (0) | n/a |
| UGA | Uganda | Sub-Saharan Africa | 14.78 (10) | 12.80 (10) | 7.39 (10) | -7.40 | 18.69 (10) | 25.40 (10) | 24.15 (10) | 5.46 | -3.79 (10) | -5.23 (10) | -6.99 (10) | -3.20 |
| YEM | Yemen, Rep. | Middle East, North Africa, Afghanistan & Pakistan | 5.16 (10) | -2.39 (10) | -21.60 (4) | -26.76 | 20.98 (10) | 12.17 (10) | 2.83 (4) | -18.14 | n/a (0) | -3.01 (10) | -7.43 (2) | n/a |

### Lower middle income

| code | country | region | EXP 95-04 | EXP 05-14 | EXP 15-24 | EXP change | INV 95-04 | INV 05-14 | INV 15-24 | INV change | CA 95-04 | CA 05-14 | CA 15-24 | CA change |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| AGO | Angola | Sub-Saharan Africa | 5.89 (2) | 5.90 (10) | -8.44 (10) | -14.34 | 30.76 (3) | 29.31 (10) | 20.96 (10) | -9.80 | -3.92 (10) | 7.41 (10) | 3.01 (10) | 6.93 |
| BEN | Benin | Sub-Saharan Africa | 3.06 (10) | 10.91 (10) | 2.47 (10) | -0.59 | 17.29 (10) | 15.54 (10) | 27.22 (10) | 9.93 | -4.48 (10) | -5.29 (10) | -4.61 (9) | -0.13 |
| BGD | Bangladesh | South Asia | 18.07 (10) | 13.70 (10) | 2.71 (10) | -15.36 | 22.85 (10) | 26.95 (10) | 31.01 (10) | 8.16 | -0.61 (10) | 1.24 (10) | -1.30 (10) | -0.69 |
| BOL | Bolivia | Latin America & Caribbean | 6.26 (10) | 5.69 (10) | -1.14 (10) | -7.40 | 16.65 (10) | 17.24 (10) | 20.25 (10) | 3.60 | -3.87 (10) | 6.59 (10) | -1.78 (10) | 2.09 |
| BTN | Bhutan | South Asia | 14.08 (10) | 9.65 (10) | 4.66 (10) | -9.41 | 49.45 (10) | 56.74 (10) | 49.42 (10) | -0.03 | n/a (0) | -13.68 (9) | -21.73 (10) | n/a |
| CIV | Cote d'Ivoire | Sub-Saharan Africa | 1.03 (8) | 1.08 (10) | 6.76 (10) | 5.73 | 15.09 (10) | 17.89 (10) | 22.99 (10) | 7.90 | n/a (0) | 1.50 (10) | -3.66 (10) | n/a |
| CMR | Cameroon | Sub-Saharan Africa | 4.14 (10) | 3.65 (10) | 0.66 (10) | -3.48 | 18.11 (10) | 18.65 (10) | 18.91 (10) | 0.80 | -2.76 (10) | -2.20 (10) | -3.57 (10) | -0.80 |
| COG | Congo, Rep. | Sub-Saharan Africa | 3.24 (10) | 1.74 (10) | 0.87 (10) | -2.37 | 26.71 (10) | 43.94 (10) | 36.81 (10) | 10.11 | -3.66 (10) | 2.97 (10) | -6.86 (5) | -3.20 |
| COM | Comoros | Sub-Saharan Africa | 2.63 (10) | 5.60 (10) | 5.06 (10) | 2.43 | 18.04 (10) | 17.21 (10) | 13.12 (10) | -4.93 | -3.84 (3) | -4.54 (9) | -1.90 (9) | 1.94 |
| DJI | Djibouti | Middle East, North Africa, Afghanistan & Pakistan | n/a (0) | 6.89 (1) | 7.14 (10) | n/a | n/a (0) | 30.01 (2) | 1.47 (10) | n/a | 10.46 (10) | -7.60 (10) | 11.33 (10) | 0.86 |
| EGY | Egypt, Arab Rep. | Middle East, North Africa, Afghanistan & Pakistan | 7.31 (10) | 6.85 (10) | 14.05 (10) | 6.74 | 18.86 (10) | 17.96 (10) | 17.57 (10) | -1.29 | 0.26 (10) | -0.76 (10) | -3.99 (10) | -4.25 |
| GHA | Ghana | Sub-Saharan Africa | n/a (0) | 16.46 (8) | 6.41 (10) | n/a | 23.18 (10) | 19.46 (10) | 18.48 (10) | -4.70 | -5.48 (10) | -8.91 (10) | -2.70 (10) | 2.78 |
| GIN | Guinea | Sub-Saharan Africa | n/a (0) | 3.34 (8) | 19.72 (10) | n/a | 13.47 (10) | 22.56 (10) | 25.55 (10) | 12.08 | -3.18 (10) | -8.94 (10) | 2.75 (10) | 5.93 |
| HND | Honduras | Latin America & Caribbean | 14.42 (10) | 3.03 (10) | 0.80 (10) | -13.61 | 27.79 (10) | 26.27 (10) | 23.85 (10) | -3.95 | -5.37 (10) | -7.28 (10) | -3.63 (10) | 1.74 |
| HTI | Haiti | Latin America & Caribbean | 13.97 (10) | 21.87 (10) | -6.85 (10) | -20.82 | 18.64 (10) | 15.65 (10) | 16.32 (10) | -2.32 | -1.70 (10) | -2.02 (10) | -1.54 (10) | 0.16 |
| IND | India | South Asia | 14.75 (10) | 11.36 (10) | 5.27 (10) | -9.49 | 28.53 (10) | 38.21 (10) | 32.00 (10) | 3.47 | -0.39 (10) | -2.31 (10) | -1.05 (10) | -0.67 |
| KEN | Kenya | Sub-Saharan Africa | 2.23 (10) | 4.26 (10) | 5.77 (10) | 3.54 | 16.90 (10) | 20.81 (10) | 19.30 (10) | 2.40 | -8.10 (10) | -5.41 (10) | -4.60 (10) | 3.50 |
| KGZ | Kyrgyz Republic | Europe & Central Asia | n/a (0) | 0.65 (4) | 9.77 (10) | n/a | 18.06 (10) | 28.20 (10) | 31.51 (10) | 13.45 | -9.15 (10) | -10.01 (10) | -17.08 (10) | -7.92 |
| KHM | Cambodia | East Asia & Pacific | 21.08 (10) | 13.68 (10) | 7.28 (10) | -13.80 | 18.55 (10) | 25.09 (10) | 31.48 (10) | 12.93 | -4.36 (10) | -5.74 (10) | -8.37 (10) | -4.02 |
| KIR | Kiribati | East Asia & Pacific | 0.78 (10) | 4.04 (10) | 5.78 (10) | 5.00 | n/a (0) | 20.66 (9) | 24.00 (10) | n/a | n/a (0) | -1.09 (9) | 15.15 (10) | n/a |
| LAO | Lao PDR | East Asia & Pacific | -5.53 (4) | 12.46 (10) | 8.56 (2) | 14.08 | 23.11 (5) | 31.05 (10) | 30.28 (2) | 7.18 | -5.20 (10) | -3.21 (10) | -4.45 (10) | 0.75 |
| LBN | Lebanon | Middle East, North Africa, Afghanistan & Pakistan | 18.46 (10) | 2.48 (10) | -4.44 (10) | -22.90 | 25.59 (10) | 25.19 (10) | 12.00 (10) | -13.59 | -23.37 (3) | -16.61 (10) | -21.98 (9) | 1.39 |
| LSO | Lesotho | Sub-Saharan Africa | 23.62 (10) | 2.22 (10) | 2.08 (10) | -21.54 | n/a (0) | 30.32 (8) | 26.85 (10) | n/a | -9.80 (10) | -1.22 (10) | -6.99 (10) | 2.81 |
| MAR | Morocco | Middle East, North Africa, Afghanistan & Pakistan | 5.17 (10) | 5.39 (10) | 6.05 (10) | 0.88 | 25.01 (10) | 31.33 (10) | 30.55 (10) | 5.55 | 0.61 (10) | -3.86 (10) | -2.65 (10) | -3.26 |
| MMR | Myanmar | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -3.16 (10) | 1.78 (10) | -3.88 (5) | -0.72 |
| MRT | Mauritania | Sub-Saharan Africa | -1.20 (10) | 9.09 (10) | 3.56 (10) | 4.76 | 14.81 (10) | 37.19 (10) | 41.00 (10) | 26.19 | 2.86 (4) | -19.31 (3) | -10.97 (10) | -13.83 |
| NAM | Namibia | Sub-Saharan Africa | 4.03 (10) | 3.21 (10) | 1.40 (10) | -2.63 | 19.67 (10) | 25.63 (10) | 20.61 (10) | 0.94 | 3.29 (10) | -1.41 (10) | -8.78 (10) | -12.06 |
| NGA | Nigeria | Sub-Saharan Africa | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | 3.13 (10) | 7.30 (10) | 0.72 (10) | -2.41 |
| NIC | Nicaragua | Latin America & Caribbean | 11.34 (10) | 8.52 (10) | 3.26 (10) | -8.08 | 24.60 (10) | 28.89 (10) | 24.93 (10) | 0.33 | -16.34 (10) | -12.04 (10) | -1.09 (10) | 15.25 |
| NPL | Nepal | South Asia | -5.22 (3) | 3.77 (10) | 1.60 (10) | 6.82 | 23.59 (10) | 29.93 (10) | 34.08 (10) | 10.49 | -2.35 (10) | 2.02 (10) | -2.19 (10) | 0.16 |
| PAK | Pakistan | Middle East, North Africa, Afghanistan & Pakistan | 5.08 (10) | 3.29 (10) | 3.89 (10) | -1.19 | 16.70 (10) | 16.33 (10) | 15.27 (10) | -1.42 | -1.20 (10) | -2.67 (10) | -2.31 (10) | -1.11 |
| PNG | Papua New Guinea | East Asia & Pacific | 2.90 (10) | n/a (0) | n/a (0) | n/a | 20.60 (10) | n/a (0) | n/a (0) | n/a | 5.05 (10) | 0.18 (10) | 13.46 (10) | 8.41 |
| PSE | West Bank and Gaza | Middle East, North Africa, Afghanistan & Pakistan | 5.16 (10) | 10.30 (10) | 2.55 (10) | -2.62 | 32.80 (10) | 20.51 (10) | 25.80 (10) | -6.99 | -28.20 (10) | -14.11 (10) | -13.09 (10) | 15.11 |
| SEN | Senegal | Sub-Saharan Africa | 2.58 (10) | 1.75 (10) | 6.08 (10) | 3.50 | 20.69 (10) | 23.39 (10) | 34.15 (10) | 13.46 | -4.26 (10) | -7.32 (10) | -10.79 (9) | -6.54 |
| SLB | Solomon Islands | East Asia & Pacific | 5.81 (10) | 8.20 (10) | 1.92 (10) | -3.89 | 7.21 (10) | 13.84 (10) | 19.53 (10) | 12.32 | -5.51 (10) | -7.46 (10) | -6.06 (10) | -0.55 |
| STP | Sao Tome and Principe | Sub-Saharan Africa | n/a (0) | 27.04 (6) | -4.80 (10) | n/a | n/a (0) | 19.74 (7) | 11.22 (10) | n/a | -24.61 (8) | -40.08 (10) | -17.80 (10) | 6.81 |
| SWZ | Eswatini | Sub-Saharan Africa | n/a (0) | 13.47 (1) | 4.11 (10) | n/a | n/a (0) | 17.88 (2) | 18.13 (10) | n/a | -0.61 (10) | -1.72 (10) | 4.33 (10) | 4.94 |
| TGO | Togo | Sub-Saharan Africa | 4.33 (10) | 5.32 (10) | 2.61 (9) | -1.71 | 28.98 (10) | 19.24 (10) | 20.90 (9) | -8.08 | -6.40 (10) | -5.78 (10) | -3.40 (6) | 3.00 |
| TJK | Tajikistan | Europe & Central Asia | 4.56 (10) | 3.71 (10) | 7.95 (10) | 3.39 | 15.94 (10) | 23.13 (10) | 35.57 (10) | 19.62 | -1.43 (3) | -13.25 (10) | 2.30 (10) | 3.73 |
| TLS | Timor-Leste | East Asia & Pacific | -0.94 (4) | 6.26 (10) | 104.70 (10) | 105.64 | 26.21 (5) | 38.48 (10) | 26.72 (10) | 0.51 | n/a (0) | 191.39 (9) | 2.10 (10) | n/a |
| TUN | Tunisia | Middle East, North Africa, Afghanistan & Pakistan | 4.84 (10) | 4.46 (10) | 1.78 (10) | -3.06 | 24.62 (10) | 24.33 (10) | 16.75 (10) | -7.87 | -2.96 (10) | -4.80 (10) | -7.06 (10) | -4.11 |
| TZA | Tanzania | Sub-Saharan Africa | 12.65 (10) | 6.55 (10) | 5.09 (10) | -7.56 | 17.36 (10) | 33.89 (10) | 37.55 (10) | 20.18 | -3.96 (10) | -8.50 (10) | -3.65 (10) | 0.31 |
| UZB | Uzbekistan | Europe & Central Asia | 3.87 (9) | 12.20 (10) | 7.08 (10) | 3.21 | 21.13 (10) | 27.77 (10) | 32.25 (10) | 11.12 | n/a (0) | 5.58 (10) | -3.29 (10) | n/a |
| VEN | Venezuela, RB | Latin America & Caribbean | -1.14 (10) | -3.89 (10) | -7.07 (10) | -5.93 | 0.00 (10) | 7.54 (10) | 8.03 (10) | 8.03 | 6.47 (10) | 5.92 (10) | -1.13 (10) | -7.61 |
| VUT | Vanuatu | East Asia & Pacific | 12.60 (2) | 4.91 (10) | 12.86 (10) | 0.26 | 19.14 (10) | 29.65 (10) | 22.98 (10) | 3.84 | -4.45 (10) | -6.79 (10) | -5.27 (8) | -0.81 |
| ZMB | Zambia | Sub-Saharan Africa | 27.94 (10) | 22.31 (6) | n/a (0) | n/a | n/a (0) | 32.43 (5) | 34.57 (10) | n/a | -13.07 (8) | 1.88 (10) | 0.94 (10) | 14.02 |
| ZWE | Zimbabwe | Sub-Saharan Africa | -3.41 (10) | 4.41 (10) | 8.43 (10) | 11.84 | 13.28 (10) | 9.29 (10) | 9.92 (10) | -3.37 | n/a (0) | -13.32 (6) | -0.79 (10) | n/a |

### Upper middle income

| code | country | region | EXP 95-04 | EXP 05-14 | EXP 15-24 | EXP change | INV 95-04 | INV 05-14 | INV 15-24 | INV change | CA 95-04 | CA 05-14 | CA 15-24 | CA change |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| ALB | Albania | Europe & Central Asia | 21.38 (9) | 8.80 (10) | 7.53 (10) | -13.85 | 28.83 (10) | 33.05 (10) | 26.48 (10) | -2.35 | -5.34 (10) | -10.91 (10) | -6.44 (10) | -1.10 |
| ARG | Argentina | Latin America & Caribbean | 7.44 (10) | 2.14 (10) | 2.14 (10) | -5.29 | 17.35 (10) | 18.05 (10) | 16.89 (10) | -0.46 | -0.49 (10) | 0.53 (10) | -1.75 (10) | -1.26 |
| ARM | Armenia | Europe & Central Asia | 7.46 (10) | 4.75 (10) | 17.86 (10) | 10.40 | 23.63 (10) | 35.03 (10) | 20.86 (10) | -2.77 | -13.54 (10) | -9.21 (10) | -3.68 (10) | 9.87 |
| AZE | Azerbaijan | Europe & Central Asia | 12.21 (10) | 17.71 (10) | n/a (0) | n/a | 33.40 (10) | 24.44 (10) | 20.96 (10) | -12.44 | -18.68 (10) | 20.89 (10) | 8.33 (10) | 27.01 |
| BIH | Bosnia and Herzegovina | Europe & Central Asia | 7.80 (4) | 7.55 (10) | 5.82 (10) | -1.97 | 32.34 (10) | 25.39 (10) | 25.27 (10) | -7.07 | -13.15 (7) | -9.04 (10) | -3.51 (10) | 9.63 |
| BLR | Belarus | Europe & Central Asia | 7.47 (10) | 4.46 (10) | 2.41 (10) | -5.05 | 25.05 (10) | 35.58 (10) | 26.48 (10) | 1.43 | -3.90 (10) | -7.12 (10) | -0.65 (10) | 3.25 |
| BLZ | Belize | Latin America & Caribbean | 7.73 (10) | 4.37 (10) | 3.84 (10) | -3.88 | 19.66 (10) | 16.12 (10) | 18.21 (10) | -1.44 | -8.91 (10) | -4.35 (10) | -5.99 (10) | 2.93 |
| BRA | Brazil | Latin America & Caribbean | 5.79 (10) | 2.93 (10) | 3.36 (10) | -2.43 | 17.77 (10) | 20.25 (10) | 16.41 (10) | -1.37 | -2.59 (10) | -2.07 (10) | -2.30 (10) | 0.28 |
| BWA | Botswana | Sub-Saharan Africa | 5.09 (10) | 6.13 (10) | -2.51 (10) | -7.60 | 28.93 (10) | 29.82 (10) | 28.55 (10) | -0.38 | 8.33 (10) | 4.94 (10) | -0.59 (10) | -8.92 |
| CHN | China | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | 36.81 (10) | 43.64 (10) | 42.26 (10) | 5.45 | 2.12 (10) | 4.93 (10) | 1.58 (10) | -0.54 |
| COL | Colombia | Latin America & Caribbean | 5.34 (10) | 4.49 (10) | 1.59 (10) | -3.75 | 18.78 (10) | 22.69 (10) | 20.18 (10) | 1.40 | -2.24 (10) | -2.82 (10) | -4.19 (10) | -1.95 |
| CPV | Cabo Verde | Sub-Saharan Africa | n/a (0) | 2.98 (7) | 8.88 (10) | n/a | n/a (0) | 40.58 (8) | 25.45 (10) | n/a | -10.73 (10) | -10.07 (10) | -4.89 (10) | 5.83 |
| CUB | Cuba | Latin America & Caribbean | 7.41 (10) | 9.59 (10) | -6.57 (10) | -13.98 | 11.34 (10) | 10.26 (10) | 15.04 (10) | 3.70 | n/a (0) | n/a (0) | n/a (0) | n/a |
| DMA | Dominica | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -11.89 (10) | -15.46 (10) | -27.57 (10) | -15.67 |
| DOM | Dominican Republic | Latin America & Caribbean | 5.50 (10) | 3.07 (10) | 4.87 (10) | -0.63 | 23.90 (10) | 25.15 (10) | 25.71 (10) | 1.80 | -0.71 (10) | -5.27 (10) | -2.29 (10) | -1.58 |
| DZA | Algeria | Middle East, North Africa, Afghanistan & Pakistan | 4.53 (10) | -2.03 (10) | -0.61 (10) | -5.14 | 28.28 (10) | 39.15 (10) | 43.87 (10) | 15.59 | n/a (0) | 10.06 (10) | -6.13 (10) | n/a |
| ECU | Ecuador | Latin America & Caribbean | 2.35 (10) | 3.25 (10) | 1.46 (10) | -0.90 | 17.07 (10) | 21.63 (10) | 21.00 (10) | 3.92 | -1.19 (10) | 0.76 (10) | 1.05 (10) | 2.24 |
| FJI | Fiji | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | 22.63 (10) | 20.43 (10) | 20.42 (10) | -2.21 | -2.60 (10) | -8.09 (10) | -8.32 (10) | -5.72 |
| FSM | Micronesia, Fed. Sts. | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | -6.26 (6) | n/a (0) | n/a |
| GAB | Gabon | Sub-Saharan Africa | -2.07 (10) | 1.32 (10) | 6.80 (10) | 8.87 | 25.85 (10) | 27.10 (10) | 20.92 (10) | -4.93 | 9.10 (10) | 14.59 (9) | 0.98 (1) | -8.12 |
| GEO | Georgia | Europe & Central Asia | n/a (0) | 8.64 (4) | 8.02 (10) | n/a | 24.06 (10) | 25.56 (10) | 25.48 (10) | 1.43 | -8.02 (8) | -12.65 (10) | -8.06 (10) | -0.04 |
| GNQ | Equatorial Guinea | Sub-Saharan Africa | n/a (0) | 2.13 (9) | -5.77 (10) | n/a | n/a (0) | 33.28 (10) | 11.17 (10) | n/a | -117.50 (2) | n/a (0) | n/a (0) | n/a |
| GRD | Grenada | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -19.51 (10) | -22.33 (10) | -13.88 (10) | 5.63 |
| GTM | Guatemala | Latin America & Caribbean | 4.46 (10) | 3.38 (10) | 1.66 (10) | -2.80 | 17.67 (10) | 16.81 (10) | 15.02 (10) | -2.64 | -4.93 (10) | -3.54 (10) | 1.85 (10) | 6.79 |
| IDN | Indonesia | East Asia & Pacific | 4.78 (10) | 7.13 (10) | 4.55 (10) | -0.23 | 25.78 (10) | 30.36 (10) | 32.53 (10) | 6.75 | 1.68 (10) | -0.06 (10) | -1.10 (10) | -2.78 |
| IRN | Iran, Islamic Rep. | Middle East, North Africa, Afghanistan & Pakistan | 0.70 (10) | -0.27 (10) | 5.30 (10) | 4.60 | 36.74 (10) | 38.43 (10) | 39.59 (10) | 2.84 | 4.16 (6) | n/a (0) | n/a (0) | n/a |
| IRQ | Iraq | Middle East, North Africa, Afghanistan & Pakistan | n/a (0) | 7.54 (7) | 4.45 (10) | n/a | 27.78 (10) | 16.15 (10) | 20.39 (10) | -7.39 | n/a (0) | 8.16 (10) | 7.14 (10) | n/a |
| JAM | Jamaica | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -5.01 (10) | -11.36 (10) | -0.41 (10) | 4.60 |
| JOR | Jordan | Middle East, North Africa, Afghanistan & Pakistan | n/a (0) | n/a (0) | n/a (0) | n/a | 24.43 (10) | 30.92 (3) | n/a (0) | n/a | 1.59 (10) | -10.33 (10) | -6.30 (10) | -7.89 |
| KAZ | Kazakhstan | Europe & Central Asia | 6.07 (10) | 1.38 (10) | 1.37 (10) | -4.70 | 21.30 (10) | 28.13 (10) | 27.07 (10) | 5.77 | -2.33 (10) | 0.69 (10) | -2.78 (10) | -0.45 |
| LBY | Libya | Middle East, North Africa, Afghanistan & Pakistan | -9.87 (1) | 39.41 (10) | 19.53 (10) | 29.40 | 12.86 (10) | 18.87 (10) | 13.71 (10) | 0.85 | 7.77 (10) | 18.85 (10) | 3.56 (9) | -4.21 |
| LCA | St. Lucia | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -13.08 (10) | -14.19 (10) | -3.99 (10) | 9.09 |
| LKA | Sri Lanka | South Asia | 5.35 (10) | 1.18 (5) | 3.90 (9) | -1.45 | 24.74 (10) | 26.95 (5) | 33.01 (10) | 8.27 | -3.10 (10) | -4.24 (10) | -1.58 (10) | 1.52 |
| MDA | Moldova | Europe & Central Asia | 5.10 (9) | 7.46 (10) | 6.81 (10) | 1.71 | 24.01 (10) | 28.49 (10) | 24.01 (10) | 0.00 | -7.49 (10) | -9.48 (10) | -10.04 (10) | -2.55 |
| MDV | Maldives | South Asia | n/a (0) | n/a (0) | 12.80 (10) | n/a | n/a (0) | 27.86 (1) | 36.42 (10) | n/a | -6.24 (10) | -12.82 (10) | -20.65 (10) | -14.41 |
| MEX | Mexico | Latin America & Caribbean | 9.03 (10) | 5.60 (10) | 2.69 (10) | -6.34 | 21.11 (10) | 23.15 (10) | 22.95 (10) | 1.84 | -1.48 (10) | -1.08 (10) | -0.95 (10) | 0.53 |
| MHL | Marshall Islands | East Asia & Pacific | n/a (0) | 4.91 (10) | 1.74 (10) | n/a | 17.70 (1) | 25.49 (10) | 24.39 (10) | 6.69 | n/a (0) | -7.41 (10) | 16.62 (10) | n/a |
| MKD | North Macedonia | Europe & Central Asia | 4.55 (10) | 8.96 (10) | 5.46 (10) | 0.91 | 19.77 (10) | 25.81 (10) | 32.02 (10) | 12.24 | -5.84 (9) | -3.92 (10) | -2.14 (10) | 3.70 |
| MNE | Montenegro | Europe & Central Asia | n/a (0) | 4.66 (8) | 7.90 (10) | n/a | 19.33 (5) | 24.32 (10) | 27.01 (10) | 7.68 | n/a (0) | -24.00 (8) | -15.16 (10) | n/a |
| MNG | Mongolia | East Asia & Pacific | n/a (0) | 23.14 (4) | 8.37 (10) | n/a | 28.24 (10) | 43.46 (10) | 32.04 (10) | 3.80 | -2.81 (10) | -15.42 (10) | -9.63 (10) | -6.82 |
| MUS | Mauritius | Sub-Saharan Africa | 3.41 (10) | 4.32 (10) | 3.97 (10) | 0.56 | 24.57 (10) | 23.61 (10) | 18.84 (10) | -5.72 | 0.55 (10) | -7.69 (10) | -6.49 (10) | -7.04 |
| MYS | Malaysia | East Asia & Pacific | 8.32 (10) | 2.83 (10) | 3.61 (10) | -4.71 | 29.90 (10) | 23.10 (10) | 23.20 (10) | -6.70 | 5.73 (10) | 11.20 (10) | 2.76 (10) | -2.97 |
| PER | Peru | Latin America & Caribbean | 8.44 (10) | 3.40 (10) | 4.24 (10) | -4.20 | 20.51 (10) | 22.79 (10) | 21.13 (10) | 0.62 | -3.87 (10) | -1.53 (10) | -1.32 (10) | 2.56 |
| PHL | Philippines | East Asia & Pacific | 6.48 (10) | 5.46 (10) | 5.84 (10) | -0.64 | 20.07 (10) | 18.94 (10) | 23.54 (10) | 3.47 | -1.56 (10) | 3.35 (10) | -1.17 (10) | 0.39 |
| PRY | Paraguay | Latin America & Caribbean | 1.94 (10) | 4.68 (10) | 3.86 (10) | 1.92 | 20.03 (10) | 21.98 (10) | 22.19 (10) | 2.17 | -0.01 (10) | 0.34 (10) | 0.05 (10) | 0.05 |
| SLV | El Salvador | Latin America & Caribbean | 8.45 (10) | 3.10 (10) | 3.63 (10) | -4.82 | 17.64 (10) | 17.93 (10) | 19.20 (10) | 1.57 | -2.67 (10) | -5.29 (10) | -2.55 (10) | 0.12 |
| SRB | Serbia | Europe & Central Asia | 31.86 (9) | 7.72 (10) | 8.49 (10) | -23.38 | 14.10 (10) | 20.08 (10) | 22.89 (10) | 8.79 | n/a (0) | -9.96 (8) | -4.39 (10) | n/a |
| SUR | Suriname | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | 43.41 (5) | n/a (0) | n/a | n/a (0) | 3.95 (10) | -4.18 (10) | n/a |
| THA | Thailand | East Asia & Pacific | 8.48 (10) | 5.18 (10) | 1.73 (10) | -6.75 | 27.76 (10) | 26.33 (10) | 23.95 (10) | -3.80 | 2.41 (10) | 1.66 (10) | 4.21 (10) | 1.80 |
| TKM | Turkmenistan | Europe & Central Asia | 12.94 (10) | 33.77 (2) | n/a (0) | n/a | 35.08 (9) | 27.86 (5) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a |
| TON | Tonga | East Asia & Pacific | 2.79 (10) | 0.03 (10) | 6.39 (10) | 3.60 | 21.75 (10) | 25.53 (10) | 26.74 (10) | 5.00 | -5.08 (4) | -15.68 (10) | -6.35 (10) | -1.26 |
| TUR | Turkiye | Europe & Central Asia | 9.92 (10) | 6.48 (10) | 4.65 (10) | -5.27 | 24.35 (10) | 29.21 (10) | 32.40 (10) | 8.05 | -1.05 (10) | -4.97 (10) | -2.37 (10) | -1.33 |
| TUV | Tuvalu | East Asia & Pacific | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -29.51 (4) | -16.40 (10) | 13.44 (9) | 42.95 |
| UKR | Ukraine | Europe & Central Asia | 7.17 (10) | -5.61 (10) | -5.72 (10) | -12.89 | 21.40 (10) | 20.75 (10) | 16.39 (10) | -5.01 | 2.51 (10) | -3.85 (10) | -1.66 (10) | -4.17 |
| VCT | St. Vincent and the Grenadines | Latin America & Caribbean | n/a (0) | n/a (0) | n/a (0) | n/a | n/a (0) | n/a (0) | n/a (0) | n/a | -12.57 (10) | -23.28 (10) | -14.69 (10) | -2.12 |
| VNM | Viet Nam | East Asia & Pacific | 19.62 (10) | 11.46 (10) | 9.64 (10) | -9.98 | 30.51 (10) | 34.20 (10) | 31.95 (10) | 1.44 | -1.87 (9) | -1.77 (10) | 2.03 (10) | 3.90 |
| WSM | Samoa | East Asia & Pacific | n/a (0) | 0.56 (5) | 12.67 (10) | n/a | n/a (0) | 28.36 (6) | 33.60 (10) | n/a | 0.99 (6) | -7.59 (10) | -2.17 (10) | -3.16 |
| XKX | Kosovo | Europe & Central Asia | n/a (0) | 13.69 (6) | 13.21 (10) | n/a | n/a (0) | 32.69 (7) | 34.20 (10) | n/a | n/a (0) | -9.46 (7) | -7.58 (10) | n/a |
| ZAF | South Africa | Sub-Saharan Africa | 4.26 (10) | 2.76 (10) | 1.04 (10) | -3.22 | 15.99 (10) | 18.74 (10) | 15.45 (10) | -0.54 | -0.81 (10) | -3.74 (10) | -1.12 (10) | -0.31 |

## Changes: PULL 2 vs PULL 1

pull 2 failed (TASK wording: "A failed pull: write pull k failed for its Changes"). Its cell-by-cell difference from PULL 1 is still given below for completeness.

PULL 2: the country-list request succeeded and a full-row CSV is attached; its three indicator requests failed after one retry (error excerpts in PROOF), so their cells are empty in macro-external-pull2.csv. Every changed cell below is a value present in PULL 1 and empty in PULL 2.

Matched by key countryiso3code|date between macro-external-pull1.csv (earlier) and macro-external-pull2.csv (later); compared columns (all after date): export growth, investment share, current account.

Rows: PULL 1 = 6510, PULL 2 = 6510 (6510 = 6510 + 0 - 0). new = 0, gone = 0, changed = 14854 cells in 5859 keys.

new (key only in the later pull): none

gone (key only in the earlier pull): none

changed: the full list, one line per changed cell (key, column, earlier value, later value; empty = empty cell), is attached under Rule 25 as the data file changes-pull2-vs-pull1.csv: 14854 data rows plus header, 637654 bytes, SHA-256 2a69325527465012a0084fd0dae28f0c95d71af7bdc7a9453d9ad229fffbe00e. Its first 15 lines and last line, verbatim:

```
key,column,earlier,later
ABW|1995,investment share,31.1336717428088,
ABW|1995,current account,-0.0211505922165815,
ABW|1996,investment share,28.4615384615385,
ABW|1996,current account,-5.0080971659919,
ABW|1997,investment share,30.2334062727936,
ABW|1997,current account,-12.7826404084609,
ABW|1998,investment share,31.7007715531701,
ABW|1998,current account,-1.12713854411271,
ABW|1999,investment share,30.8690012970169,
ABW|1999,current account,-25.2778858625162,
ABW|2000,investment share,25.4941135775374,
ABW|2000,current account,11.0568722640362,
ABW|2001,investment share,23.9991775312859,
ABW|2001,current account,16.2808742441801,
ABW|2002,investment share,26.629979781872,
...
ZWE|2024,current account,1.2070735013076,
```

## Changes: PULL 3 vs PULL 1 (last good pull, per TASK)

pull 2 failed (indicator requests failed after one retry; see PROOF > PULL 2 requests), so PULL 3 is compared with the last good one, PULL 1, as the TASK requires.

Matched by key countryiso3code|date between macro-external-pull1.csv (earlier) and macro-external-pull3.csv (later); compared columns (all after date): export growth, investment share, current account.

Rows: PULL 1 = 6510, PULL 3 = 6510 (6510 = 6510 + 0 - 0). new = 0, gone = 0, changed = 0: no change. The two files are byte-identical (SHA-256 3e3dd84d4713f4d155c33c62a69447d320a48bebd30230e0eff3297ff81ce1c2 for both, see the synmerco-data block).

## Changes: PULL 3 vs PULL 2 (failed pull, for completeness)

PULL 3 is compared with PULL 2 (the previous pull). Every changed cell below is a value empty in PULL 2 and present again in PULL 3.

Matched by key countryiso3code|date between macro-external-pull2.csv (earlier) and macro-external-pull3.csv (later); compared columns (all after date): export growth, investment share, current account.

Rows: PULL 2 = 6510, PULL 3 = 6510 (6510 = 6510 + 0 - 0). new = 0, gone = 0, changed = 14854 cells in 5859 keys.

new (key only in the later pull): none

gone (key only in the earlier pull): none

changed: the full list, one line per changed cell (key, column, earlier value, later value; empty = empty cell), is attached under Rule 25 as the data file changes-pull3-vs-pull2.csv: 14854 data rows plus header, 637654 bytes, SHA-256 6a45f1dd43fe8e05c31ac060b48b180425146a51e071202fde601935b085aecb. Its first 15 lines and last line, verbatim:

```
key,column,earlier,later
ABW|1995,investment share,,31.1336717428088
ABW|1995,current account,,-0.0211505922165815
ABW|1996,investment share,,28.4615384615385
ABW|1996,current account,,-5.0080971659919
ABW|1997,investment share,,30.2334062727936
ABW|1997,current account,,-12.7826404084609
ABW|1998,investment share,,31.7007715531701
ABW|1998,current account,,-1.12713854411271
ABW|1999,investment share,,30.8690012970169
ABW|1999,current account,,-25.2778858625162
ABW|2000,investment share,,25.4941135775374
ABW|2000,current account,,11.0568722640362
ABW|2001,investment share,,23.9991775312859
ABW|2001,current account,,16.2808742441801
ABW|2002,investment share,,26.629979781872
...
ZWE|2024,current account,,1.2070735013076
```

## PROOF

### PULL 1 requests (UTC time, HTTP Date header line)

```
2026-11-13T15:14:15Z GET https://api.worldbank.org/v2/country?format=json&per_page=400 -> HTTP 200 | Date: Fri, 13 Nov 2026 15:14:15 GMT
2026-11-13T15:14:15Z GET https://api.worldbank.org/v2/country/all/indicator/NE.EXP.GNFS.KD.ZG?format=json&date=1995:2024&per_page=20000&page=1 -> HTTP 200 | Date: Fri, 13 Nov 2026 15:14:15 GMT
2026-11-13T15:14:15Z GET https://api.worldbank.org/v2/country/all/indicator/NE.GDI.TOTL.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> HTTP 200 | Date: Fri, 13 Nov 2026 15:15:03 GMT
2026-11-13T15:15:03Z GET https://api.worldbank.org/v2/country/all/indicator/BN.CAB.XOKA.GD.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
2026-11-13T15:16:06Z GET https://api.worldbank.org/v2/country/all/indicator/BN.CAB.XOKA.GD.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> HTTP 200 | Date: Fri, 13 Nov 2026 15:16:47 GMT
```

Paging elements PULL 1 (verbatim, element [0] of each response):

```
country: {"page": 1, "pages": 1, "per_page": "400", "total": 296}  rows received=296
NE.EXP.GNFS.KD.ZG: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, "sourceid": "2", "lastupdated": "2026-11-11"}
NE.EXP.GNFS.KD.ZG: rows received=7980 (aggregates included), total=7980, match=yes
NE.GDI.TOTL.ZS: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, "sourceid": "2", "lastupdated": "2026-11-11"}
NE.GDI.TOTL.ZS: rows received=7980 (aggregates included), total=7980, match=yes
BN.CAB.XOKA.GD.ZS: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, "sourceid": "2", "lastupdated": "2026-11-11"}
BN.CAB.XOKA.GD.ZS: rows received=7980 (aggregates included), total=7980, match=yes
```

### PULL 2 requests (UTC time, HTTP Date header line)

```
2026-11-14T17:04:40Z GET https://api.worldbank.org/v2/country?format=json&per_page=400 -> HTTP 200 | Date: Sat, 14 Nov 2026 17:04:40 GMT
2026-11-14T17:04:40Z GET https://api.worldbank.org/v2/country/all/indicator/NE.EXP.GNFS.KD.ZG?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
2026-11-14T17:05:43Z GET https://api.worldbank.org/v2/country/all/indicator/NE.EXP.GNFS.KD.ZG?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
2026-11-14T17:06:46Z GET https://api.worldbank.org/v2/country/all/indicator/NE.GDI.TOTL.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
2026-11-14T17:07:49Z GET https://api.worldbank.org/v2/country/all/indicator/NE.GDI.TOTL.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
2026-11-14T17:08:53Z GET https://api.worldbank.org/v2/country/all/indicator/BN.CAB.XOKA.GD.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
2026-11-14T17:09:56Z GET https://api.worldbank.org/v2/country/all/indicator/BN.CAB.XOKA.GD.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> FAILED TimeoutError('The read operation timed out')
```

Paging elements PULL 2 (verbatim, element [0] of each response):

```
country: {"page": 1, "pages": 1, "per_page": "400", "total": 296}  rows received=296
NE.EXP.GNFS.KD.ZG: no response (request failed after one retry)
NE.GDI.TOTL.ZS: no response (request failed after one retry)
BN.CAB.XOKA.GD.ZS: no response (request failed after one retry)
```

### PULL 3 requests (UTC time, HTTP Date header line)

```
2026-11-15T17:52:07Z GET https://api.worldbank.org/v2/country?format=json&per_page=400 -> HTTP 200 | Date: Sun, 15 Nov 2026 17:52:07 GMT
2026-11-15T17:52:07Z GET https://api.worldbank.org/v2/country/all/indicator/NE.EXP.GNFS.KD.ZG?format=json&date=1995:2024&per_page=20000&page=1 -> HTTP 200 | Date: Sun, 15 Nov 2026 17:52:08 GMT
2026-11-15T17:52:08Z GET https://api.worldbank.org/v2/country/all/indicator/NE.GDI.TOTL.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> HTTP 200 | Date: Sun, 15 Nov 2026 17:52:09 GMT
2026-11-15T17:52:10Z GET https://api.worldbank.org/v2/country/all/indicator/BN.CAB.XOKA.GD.ZS?format=json&date=1995:2024&per_page=20000&page=1 -> HTTP 200 | Date: Sun, 15 Nov 2026 17:52:11 GMT
```

Paging elements PULL 3 (verbatim, element [0] of each response):

```
country: {"page": 1, "pages": 1, "per_page": "400", "total": 296}  rows received=296
NE.EXP.GNFS.KD.ZG: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, "sourceid": "2", "lastupdated": "2026-11-11"}
NE.EXP.GNFS.KD.ZG: rows received=7980 (aggregates included), total=7980, match=yes
NE.GDI.TOTL.ZS: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, "sourceid": "2", "lastupdated": "2026-11-11"}
NE.GDI.TOTL.ZS: rows received=7980 (aggregates included), total=7980, match=yes
BN.CAB.XOKA.GD.ZS: {"page": 1, "pages": 1, "per_page": 20000, "total": 7980, "sourceid": "2", "lastupdated": "2026-11-11"}
BN.CAB.XOKA.GD.ZS: rows received=7980 (aggregates included), total=7980, match=yes
```

### Observations behind each list (from PULL 3; iso3|date|value, empty = null)

Current account (BN.CAB.XOKA.GD.ZS), countries in either current-account list:

```
ABW|2024|
ABW|2023|5.19136770255524
ABW|2022|6.93052521983244
ABW|2021|2.74311870112242
ABW|2020|-12.8585246783433
ABW|2019|2.53309209414144
ABW|2018|-0.59136646769686
ABW|2017|1.1197958543778
ABW|2016|4.7317741972835
ABW|2015|3.99414243924537
ABW|2014|-4.65857687581843
ABW|2013|-11.813208837986
ABW|2012|3.47345127544661
ABW|2011|-9.8776559966521
ABW|2010|-18.7525373189382
ABW|2009|6.72239127248544
ABW|2008|0.00393003438387262
ABW|2007|9.64536035842434
ABW|2006|12.5742113280132
ABW|2005|4.44757292760025
ABW|2004|12.0136853291022
ABW|2003|-8.09902267310928
ABW|2002|-17.3434518893983
ABW|2001|16.2808742441801
ABW|2000|11.0568722640362
ABW|1999|-25.2778858625162
ABW|1998|-1.12713854411271
ABW|1997|-12.7826404084609
ABW|1996|-5.0080971659919
ABW|1995|-0.0211505922165815
AGO|2024|6.12127885547185
AGO|2023|3.94653061969793
AGO|2022|9.17298316440326
AGO|2021|10.7294719893933
AGO|2020|1.49015129809424
AGO|2019|6.32732303026131
AGO|2018|8.1791278570017
AGO|2017|-0.739075223812658
AGO|2016|-5.07683550702313
AGO|2015|-10.0180754476355
AGO|2014|-2.44217725848603
AGO|2013|5.47217516828594
AGO|2012|9.64052717140429
AGO|2011|10.4217171191447
AGO|2010|7.85577834888099
AGO|2009|-9.26704056113806
AGO|2008|7.28233163407397
AGO|2007|14.4873579548048
AGO|2006|18.2253229198946
AGO|2005|12.4113529511059
AGO|2004|2.52329142814654
AGO|2003|-3.53728418452752
AGO|2002|-0.867014859846704
AGO|2001|-16.0129513307541
AGO|2000|8.71506351159262
AGO|1999|-27.7983311948052
AGO|1998|-28.6976083856327
AGO|1997|-11.5519884917384
AGO|1996|43.3988183053598
AGO|1995|-5.32696076591876
ALB|2024|-2.39633981728727
ALB|2023|-1.66286217786128
ALB|2022|-6.18049276219024
ALB|2021|-7.69043385149861
ALB|2020|-8.62504716716646
ALB|2019|-7.82064355473536
ALB|2018|-6.60766481105068
ALB|2017|-7.40849329663264
ALB|2016|-7.51011690016649
ALB|2015|-8.5423750766982
ALB|2014|-10.7201496577808
ALB|2013|-9.25914166645898
ALB|2012|-10.2612568930744
ALB|2011|-12.8503659661776
ALB|2010|-11.2157643683259
ALB|2009|-15.0172385106345
ALB|2008|-15.1839581650837
ALB|2007|-10.3518884224487
ALB|2006|-7.33186374631583
ALB|2005|-6.92138800420102
ALB|2004|-4.83249013532297
ALB|2003|-7.01197673066681
ALB|2002|-9.02590739072684
ALB|2001|-5.35591452180558
ALB|2000|-4.36035543487417
ALB|1999|-4.73211838588308
ALB|1998|-2.50234871672871
ALB|1997|-11.8688813645991
ALB|1996|-3.31737383628298
ALB|1995|-0.395856545631387
ARM|2024|-6.22302426078588
ARM|2023|-3.54461951215664
ARM|2022|-0.439705814290672
ARM|2021|-3.39629418665849
ARM|2020|-3.99777390668492
ARM|2019|-7.05686573000043
ARM|2018|-7.2281230237955
ARM|2017|-1.26072402014699
ARM|2016|-0.956577968660225
ARM|2015|-2.66180705584757
ARM|2014|-7.76786633240123
ARM|2013|-7.31624657065382
ARM|2012|-9.96233164214969
ARM|2011|-10.4403281934473
ARM|2010|-13.6219482985733
ARM|2009|-16.4837116405483
ARM|2008|-14.2246479360543
ARM|2007|-7.35660133782848
ARM|2006|-2.39537289745615
ARM|2005|-2.52832414562151
ARM|2004|-2.20435917633131
ARM|2003|-6.18119850537565
ARM|2002|-6.2201045971038
ARM|2001|-10.4398165717153
ARM|2000|-15.7812102966465
ARM|1999|-16.9355704119467
ARM|1998|-21.9751034634071
ARM|1997|-20.4782136117306
ARM|1996|-20.1762879448727
ARM|1995|-15.0292437935751
ATG|2024|-7.45715824054234
ATG|2023|-12.9053183160658
ATG|2022|-15.0826967558199
ATG|2021|-17.5774816563177
ATG|2020|-15.5663867272565
ATG|2019|-6.50528434529466
ATG|2018|-13.9937660480859
ATG|2017|-7.6968559845244
ATG|2016|-2.38761069740834
ATG|2015|2.03393623440556
ATG|2014|-0.0378965310947221
ATG|2013|-8.78062787514537
ATG|2012|-8.11026781449488
ATG|2011|-5.07303916439276
ATG|2010|-10.8739141545735
ATG|2009|-13.0521618835596
ATG|2008|-21.6400619803907
ATG|2007|-28.7521784338138
ATG|2006|-19.8432206578823
ATG|2005|-10.0007541423498
ATG|2004|-6.31005255823087
ATG|2003|-9.15813030793044
ATG|2002|-9.42082349224046
ATG|2001|-10.3865694462064
ATG|2000|-7.92911790133271
ATG|1999|-7.23191944041809
ATG|1998|-5.92188254714105
ATG|1997|-6.45052296085609
ATG|1996|-8.75234501112516
ATG|1995|-0.0841679993266559
AUS|2024|-2.31463737253711
AUS|2023|-0.433071259302466
AUS|2022|0.254202501603949
AUS|2021|2.44729769999573
AUS|2020|1.64272242623868
AUS|2019|-0.0757460083721138
AUS|2018|-2.58947975974168
AUS|2017|-3.00525814878871
AUS|2016|-3.60213104879026
AUS|2015|-4.2950643949091
AUS|2014|-3.07921525285017
AUS|2013|-3.24439256531684
AUS|2012|-4.42917293903347
AUS|2011|-3.25393708127954
AUS|2010|-3.99211276270473
AUS|2009|-5.21460357172589
AUS|2008|-4.87128797048566
AUS|2007|-7.5509404049246
AUS|2006|-6.1743242864652
AUS|2005|-6.2201820658335
AUS|2004|-6.70631316237641
AUS|2003|-6.25542304141098
AUS|2002|-4.03651427027563
AUS|2001|-2.09983536268172
AUS|2000|-3.71484792517268
AUS|1999|-5.58366414929506
AUS|1998|-4.44111787888724
AUS|1997|-2.72974894003095
AUS|1996|-3.58360337747536
AUS|1995|-5.06318585541185
AZE|2024|6.27617767984307
AZE|2023|11.5001296207861
AZE|2022|29.7916946512237
AZE|2021|14.9620003998682
AZE|2020|-0.740874280795446
AZE|2019|8.70455620187564
AZE|2018|12.6823769245212
AZE|2017|4.12208960991814
AZE|2016|-3.60050733417184
AZE|2015|-0.419198909856565
AZE|2014|13.5683574038086
AZE|2013|16.4935876692396
AZE|2012|21.4925357741895
AZE|2011|25.9957665612112
AZE|2010|28.4268313519369
AZE|2009|22.9720443124812
AZE|2008|33.6793638921001
AZE|2007|27.289087539853
AZE|2006|17.670467343915
AZE|2005|1.26319117280894
AZE|2004|-29.8282485551101
AZE|2003|-27.7726673572238
AZE|2002|-12.3213949554144
AZE|2001|-0.906770850609527
AZE|2000|-3.18196904183888
AZE|1999|-13.0903833593547
AZE|1998|-30.6884366040807
AZE|1997|-23.1113389046322
AZE|1996|-29.3146493832248
AZE|1995|-16.5740632135158
BDI|2024|-15.6376698795971
BDI|2023|-18.3607341751646
BDI|2022|-15.3007531318327
BDI|2021|-11.3663437249219
BDI|2020|-10.8615271645188
BDI|2019|-13.689181364132
BDI|2018|-13.366968151704
BDI|2017|-13.1912710345622
BDI|2016|-12.518429325456
BDI|2015|-12.7716902710485
BDI|2014|-15.847519265777
BDI|2013|-10.5411437462372
BDI|2012|-11.2209754829117
BDI|2011|-12.6836763902514
BDI|2010|-14.8111210984708
BDI|2009|-9.07806464648821
BDI|2008|-16.090734369062
BDI|2007|-8.20727615108639
BDI|2006|-10.4870448125811
BDI|2005|-0.510079090142337
BDI|2004|-3.53655815425186
BDI|2003|-3.04630146043227
BDI|2002|-0.397990063033963
BDI|2001|-4.1872020116794
BDI|2000|-5.76258887448881
BDI|1999|-2.61184612113877
BDI|1998|-5.44160419385011
BDI|1997|0.630045184343134
BDI|1996|-4.60400356055959
BDI|1995|1.04416596056391
BEN|2024|
BEN|2023|-8.17628006592928
BEN|2022|-5.68712530548323
BEN|2021|-4.15352071063382
BEN|2020|-1.74648575797682
BEN|2019|-3.99948140400368
BEN|2018|-4.5491953448839
BEN|2017|-4.18078964014056
BEN|2016|-2.99669454869691
BEN|2015|-5.964093171322
BEN|2014|-6.66790663182434
BEN|2013|-5.37925541995638
BEN|2012|-5.17832684259519
BEN|2011|-4.83328627198861
BEN|2010|-5.56723414629172
BEN|2009|-6.69033181086781
BEN|2008|-5.49862209196275
BEN|2007|-6.54621938784527
BEN|2006|-3.08778709107343
BEN|2005|-3.44376642481128
BEN|2004|-4.66878856732409
BEN|2003|-6.20555050861218
BEN|2002|-3.74152919965986
BEN|2001|-2.04549532483075
BEN|2000|-2.2949879315414
BEN|1999|-4.2321738931756
BEN|1998|-5.39739989943454
BEN|1997|-6.78725035015034
BEN|1996|-1.73457487701647
BEN|1995|-7.69564346950043
BGR|2024|-0.516395583295193
BGR|2023|-1.15394184437216
BGR|2022|-1.36184875982261
BGR|2021|0.247490706249255
BGR|2020|1.46731874723096
BGR|2019|1.65784486644031
BGR|2018|0.57450304784286
BGR|2017|3.2462873346343
BGR|2016|3.10210131284369
BGR|2015|0.0183972300944813
BGR|2014|2.19237265570796
BGR|2013|1.21571887688313
BGR|2012|-0.973520622135055
BGR|2011|0.472382025310572
BGR|2010|-1.90291712885645
BGR|2009|-8.18108400485089
BGR|2008|-21.7962184298018
BGR|2007|-25.7395900882888
BGR|2006|-17.053054521676
BGR|2005|-11.2051503131429
BGR|2004|-6.38831487911216
BGR|2003|-4.83379022036454
BGR|2002|-1.94489971800466
BGR|2001|-5.67286092377739
BGR|2000|-5.3121707536827
BGR|1999|-4.78179914055499
BGR|1998|-0.411875963679224
BGR|1997|3.7722989749992
BGR|1996|0.127688068438994
BGR|1995|-0.135843892423199
BHS|2024|-6.64860795366669
BHS|2023|-7.00069253380099
BHS|2022|-8.86961547540973
BHS|2021|-20.2208763533214
BHS|2020|-22.0443509738872
BHS|2019|-2.60210078588536
BHS|2018|-8.70002668448312
BHS|2017|-12.6509094143141
BHS|2016|-5.98258988449718
BHS|2015|-10.1639297057562
BHS|2014|-16.9249150364207
BHS|2013|-14.2614149475433
BHS|2012|-14.0368120592515
BHS|2011|-11.9472714724764
BHS|2010|-8.0632166374795
BHS|2009|-8.10442037435534
BHS|2008|-11.6100892944233
BHS|2007|-12.3851568041165
BHS|2006|-13.8061914480317
BHS|2005|-7.12305028440183
BHS|2004|-3.39160866189817
BHS|2003|-5.33827728918196
BHS|2002|-4.76646866689711
BHS|2001|-7.75394544009676
BHS|2000|-7.8368767543246
BHS|1999|-4.22180125379529
BHS|1998|-14.5670708684925
BHS|1997|-7.45535629686247
BHS|1996|-7.29564976447769
BHS|1995|-4.25488480606591
BIH|2024|-3.62214741545808
BIH|2023|-2.34490478185558
BIH|2022|-4.49353630208696
BIH|2021|-1.47256667780382
BIH|2020|-2.83951836354719
BIH|2019|-2.59691879205514
BIH|2018|-3.23062992301101
BIH|2017|-4.77878216555827
BIH|2016|-4.69867088432468
BIH|2015|-5.03540535932256
BIH|2014|-7.27125694651233
BIH|2013|-5.32585810441448
BIH|2012|-8.62595020271331
BIH|2011|-9.47919944225313
BIH|2010|-6.00046399403906
BIH|2009|-6.44520702910113
BIH|2008|-13.8327998426086
BIH|2007|-9.1904275912974
BIH|2006|-7.75838583374484
BIH|2005|-16.4343905974533
BIH|2004|-16.1406064974205
BIH|2003|-19.1912783102526
BIH|2002|-17.6964510993081
BIH|2001|-12.8061436346752
BIH|2000|-7.10679339873963
BIH|1999|-10.6978182461914
BIH|1998|-8.38303905254982
BIH|1997|
BIH|1996|
BIH|1995|
BLR|2024|-2.09981390446491
BLR|2023|-1.03659609651183
BLR|2022|3.81254519379628
BLR|2021|3.33503209952537
BLR|2020|-0.290687853658269
BLR|2019|-1.93416658791779
BLR|2018|0.0381469405173492
BLR|2017|-1.74032515049902
BLR|2016|-3.37736852773592
BLR|2015|-3.24348147204402
BLR|2014|-6.63303695478997
BLR|2013|-10.0192566839897
BLR|2012|-2.83500762120658
BLR|2011|-8.18054584289411
BLR|2010|-14.4678043936086
BLR|2009|-12.0546848610717
BLR|2008|-8.1620215300314
BLR|2007|-6.6536778047307
BLR|2006|-3.75494824327904
BLR|2005|1.518035769229
BLR|2004|-5.15047246548434
BLR|2003|-2.55870194011727
BLR|2002|-2.23160130536418
BLR|2001|-4.28011087042602
BLR|2000|-3.60449996573167
BLR|1999|-1.59575083342586
BLR|1998|-6.67782915883964
BLR|1997|-6.08136433770411
BLR|1996|-3.55782368148984
BLR|1995|-3.279971291319
BLZ|2024|-1.61559738392131
BLZ|2023|-0.64704639580141
BLZ|2022|-8.2753170919124
BLZ|2021|-6.5003688908631
BLZ|2020|-6.24826598310846
BLZ|2019|-7.7543527144913
BLZ|2018|-6.59667558600347
BLZ|2017|-6.97409797709737
BLZ|2016|-7.29844356817201
BLZ|2015|-7.9675315662087
BLZ|2014|-6.35388372737354
BLZ|2013|-3.56655574064554
BLZ|2012|-1.72726539315554
BLZ|2011|-1.0891636773691
BLZ|2010|-2.61503524197613
BLZ|2009|-4.90747054418946
BLZ|2008|-8.33368485730916
BLZ|2007|-3.05300014756492
BLZ|2006|-1.59601197898101
BLZ|2005|-10.2571610027522
BLZ|2004|-11.0643857808538
BLZ|2003|-14.0861625835692
BLZ|2002|-13.2906443598953
BLZ|2001|-16.2421438938367
BLZ|2000|-14.1961321823555
BLZ|1999|-7.28129885720708
BLZ|1998|-6.4418161836807
BLZ|1997|-3.65785461270875
BLZ|1996|-0.781452952122277
BLZ|1995|-2.10685382583044
BRA|2024|-2.98801427062079
BRA|2023|-1.23139445763703
BRA|2022|-2.14967698505073
BRA|2021|-2.35822097223117
BRA|2020|-1.64103541830151
BRA|2019|-3.41429103072781
BRA|2018|-2.80752008594698
BRA|2017|-1.22429925769002
BRA|2016|-1.700113396765
BRA|2015|-3.51839166799859
BRA|2014|-4.4988303801852
BRA|2013|-3.57422079622864
BRA|2012|-3.75941611687375
BRA|2011|-3.19461831905473
BRA|2010|-3.92594604454763
BRA|2009|-1.7593578735281
BRA|2008|-2.09933784786717
BRA|2007|-0.19709696108555
BRA|2006|0.972710523034594
BRA|2005|1.30988466560485
BRA|2004|1.33863064799445
BRA|2003|0.392877183707378
BRA|2002|-1.84525901678299
BRA|2001|-4.44478653179818
BRA|2000|-4.0477413019387
BRA|1999|-4.46660530392098
BRA|1998|-4.05145818781602
BRA|1997|-3.63826290528202
BRA|1996|-2.73368737119507
BRA|1995|-2.35736654973227
BRB|2024|
BRB|2023|
BRB|2022|
BRB|2021|
BRB|2020|
BRB|2019|
BRB|2018|
BRB|2017|-5.06886376225887
BRB|2016|-7.96597920809368
BRB|2015|-1.73226401768809
BRB|2014|-11.3557393726686
BRB|2013|-4.46082570308174
BRB|2012|-8.17455835698894
BRB|2011|-3.12073431018442
BRB|2010|-5.01692524307779
BRB|2009|-8.53071833117839
BRB|2008|-9.01616589623384
BRB|2007|-7.42918018711688
BRB|2006|-10.4893661741424
BRB|2005|-12.9792521453765
BRB|2004|-12.6937325840461
BRB|2003|-5.86397699078632
BRB|2002|-4.66106017866377
BRB|2001|-3.64191735837973
BRB|2000|-3.33993473383023
BRB|1999|-4.48134518357529
BRB|1998|-3.76918641701839
BRB|1997|-3.20811236581199
BRB|1996|5.95962010341529
BRB|1995|0.0422416324366867
CHL|2024|-1.16817210444884
CHL|2023|-3.10428872521174
CHL|2022|-8.87430060140152
CHL|2021|-7.29452522459608
CHL|2020|-1.96248572878056
CHL|2019|-5.21201190646597
CHL|2018|-4.48367554777815
CHL|2017|-2.75779980852367
CHL|2016|-2.62065852365988
CHL|2015|-2.73506821605392
CHL|2014|-3.46029991877659
CHL|2013|-4.77606541666957
CHL|2012|-5.32849119001729
CHL|2011|-4.91713901662884
CHL|2010|0.896881680744073
CHL|2009|1.43974883336493
CHL|2008|-4.18826982519764
CHL|2007|5.05557874807609
CHL|2006|5.49643732024025
CHL|2005|1.91109059952903
CHL|2004|3.26056295397732
CHL|2003|0.21460039582268
CHL|2002|-0.825565731667287
CHL|2001|-1.53703377110131
CHL|2000|-1.14568457860136
CHL|1999|0.131436581248041
CHL|1998|-4.77915592737757
CHL|1997|-4.26887262850026
CHL|1996|-3.92274308347759
CHL|1995|-1.82822028885922
CMR|2024|-3.28354247246706
CMR|2023|-4.13580101370032
CMR|2022|-3.39397488391441
CMR|2021|-3.98670897608131
CMR|2020|-3.70931267651989
CMR|2019|-4.27316997253141
CMR|2018|-3.52725517847681
CMR|2017|-2.63102845264373
CMR|2016|-3.06806029650276
CMR|2015|-3.64384590025673
CMR|2014|-3.8530031990371
CMR|2013|-3.34459990547818
CMR|2012|-3.17006037197893
CMR|2011|-2.44588511307823
CMR|2010|-3.11602303510796
CMR|2009|-4.02097111334696
CMR|2008|-1.62929165447174
CMR|2007|1.19555212022133
CMR|2006|0.925460105397848
CMR|2005|-2.54005821725892
CMR|2004|-2.21065060210036
CMR|2003|-3.74372948027078
CMR|2002|-3.53790565581225
CMR|2001|-3.17394469214094
CMR|2000|-2.06689776396929
CMR|1999|-4.40566906646215
CMR|1998|-1.33456243682873
CMR|1997|-5.39597096870369
CMR|1996|-2.58405802001495
CMR|1995|0.827012560749537
COL|2024|-1.68848908954638
COL|2023|-2.26827872213775
COL|2022|-6.04138373706159
COL|2021|-5.63516948895365
COL|2020|-3.42772945914236
COL|2019|-4.58427517266059
COL|2018|-4.20138344687968
COL|2017|-3.18224191114871
COL|2016|-4.45195067751588
COL|2015|-6.37230442230879
COL|2014|-5.19843119341789
COL|2013|-3.23615067105019
COL|2012|-3.14008013112592
COL|2011|-2.90611447190462
COL|2010|-2.99583091222973
COL|2009|-1.90692601755576
COL|2008|-2.67924104556952
COL|2007|-2.9819266093631
COL|2006|-1.8486662357596
COL|2005|-1.33773107053945
COL|2004|-0.66148309595793
COL|2003|-0.963598625978888
COL|2002|-1.31623163816019
COL|2001|-1.05937674050926
COL|2000|0.846461525527854
COL|1999|0.778526882820605
COL|1998|-4.93441634428213
COL|1997|-5.39146862906034
COL|1996|-4.77689886981533
COL|1995|-4.8816442586875
COM|2024|
COM|2023|-1.67952222045727
COM|2022|-0.410149391838584
COM|2021|-0.313759475099584
COM|2020|-1.79978941327918
COM|2019|-3.33166140326131
COM|2018|-2.83225012492641
COM|2017|-2.13204216493526
COM|2016|-4.34858918733341
COM|2015|-0.256465657736018
COM|2014|-3.78032970112087
COM|2013|
COM|2012|-4.04970661419344
COM|2011|-5.42472388252803
COM|2010|-4.33221929296756
COM|2009|-4.35030280964664
COM|2008|-7.53469626604502
COM|2007|-3.97385796874896
COM|2006|-3.27357312325321
COM|2005|-4.09701964792287
COM|2004|-3.330057820404
COM|2003|-3.37217076421928
COM|2002|
COM|2001|
COM|2000|
COM|1999|
COM|1998|
COM|1997|
COM|1996|
COM|1995|-4.82800364207231
CPV|2024|3.94169543876696
CPV|2023|-2.76950698565635
CPV|2022|-3.48336678220334
CPV|2021|-12.2149776787505
CPV|2020|-15.6834304999368
CPV|2019|-0.968698566651976
CPV|2018|-4.40170436068748
CPV|2017|-6.99311648831081
CPV|2016|-3.4671600025876
CPV|2015|-2.89127851947954
CPV|2014|-8.2745528647665
CPV|2013|-5.2914571085641
CPV|2012|-12.7312450215892
CPV|2011|-14.8785945210366
CPV|2010|-12.2081961374489
CPV|2009|-13.2225925658414
CPV|2008|-10.4743154022798
CPV|2007|-12.0126265488265
CPV|2006|-7.46948939503442
CPV|2005|-4.18205952542758
CPV|2004|-14.0635896425988
CPV|2003|-11.1255219641803
CPV|2002|-11.5146928529663
CPV|2001|-9.89947075706639
CPV|2000|-11.1544820568204
CPV|1999|-12.6199897709133
CPV|1998|-11.2111308194649
CPV|1997|-6.05813023559705
CPV|1996|-6.98064533689196
CPV|1995|-12.6500359682207
CRI|2024|-0.867937963911081
CRI|2023|-1.42169898873901
CRI|2022|-2.60681841454892
CRI|2021|-3.32104567194295
CRI|2020|-0.995397543119445
CRI|2019|-1.15966110290765
CRI|2018|-2.9844739319841
CRI|2017|-3.61676636323197
CRI|2016|-2.13680341513898
CRI|2015|-3.40396455896801
CRI|2014|-4.71600481576243
CRI|2013|-4.77170631705961
CRI|2012|-5.10481785109759
CRI|2011|-5.32862214746454
CRI|2010|-3.21064002340827
CRI|2009|-1.79834331346225
CRI|2008|-8.3664078910243
CRI|2007|-5.60091744457089
CRI|2006|-4.10181577338671
CRI|2005|-4.24625057843326
CRI|2004|-3.59272712733211
CRI|2003|-5.17492909627053
CRI|2002|-5.15140113581831
CRI|2001|-3.21894998675565
CRI|2000|-4.55955829867216
CRI|1999|-4.67523747786551
CRI|1998|-3.80546812405948
CRI|1997|-3.81205834112802
CRI|1996|-2.25775313168151
CRI|1995|-3.09313885352732
CYP|2024|-8.15906556815551
CYP|2023|-9.70177901040072
CYP|2022|-6.97566849406384
CYP|2021|-5.56660011376222
CYP|2020|-9.70522206715595
CYP|2019|-5.52358914687597
CYP|2018|-3.74116240200316
CYP|2017|-4.91227348737416
CYP|2016|-3.87009444301685
CYP|2015|-0.244186380127821
CYP|2014|-4.07615514734757
CYP|2013|-1.50316994662796
CYP|2012|-3.86860122687542
CYP|2011|-2.0934363510795
CYP|2010|-10.7622755690665
CYP|2009|-6.67074267146988
CYP|2008|-14.3855413757168
CYP|2007|-7.63669144927273
CYP|2006|-6.36794765544154
CYP|2005|-5.26682635799638
CYP|2004|-4.77327486436682
CYP|2003|-2.00767143097125
CYP|2002|-3.32012511756835
CYP|2001|-3.09916834386667
CYP|2000|-4.88747484293358
CYP|1999|-1.62158738894853
CYP|1998|2.84348035393524
CYP|1997|-4.37875893634201
CYP|1996|-4.67156754364255
CYP|1995|-2.06499778344603
CZE|2024|1.69610102238122
CZE|2023|-0.125406557037842
CZE|2022|-4.52048439437013
CZE|2021|-2.04624111898244
CZE|2020|1.7852008079583
CZE|2019|0.356195094422181
CZE|2018|0.451859774047591
CZE|2017|1.35301705500193
CZE|2016|1.74734921729713
CZE|2015|0.446971205922034
CZE|2014|0.217020094001342
CZE|2013|-0.519137991701544
CZE|2012|-1.501449440317
CZE|2011|-2.1691537824734
CZE|2010|-3.48120039690542
CZE|2009|-2.35286468331655
CZE|2008|-1.86377838067906
CZE|2007|-4.70721210136984
CZE|2006|-2.55771892805224
CZE|2005|-2.0469317715426
CZE|2004|-3.70977039606132
CZE|2003|-5.76037419921863
CZE|2002|-5.16274750389644
CZE|2001|-4.80305110479948
CZE|2000|-4.3260595580812
CZE|1999|-2.23483455253069
CZE|1998|-1.94722596154938
CZE|1997|-5.79107713467812
CZE|1996|-6.08746771318312
CZE|1995|-2.26757320329168
DMA|2024|-37.8042228948697
DMA|2023|-40.3731052052085
DMA|2022|-26.5615606888312
DMA|2021|-33.0604505678153
DMA|2020|-35.2351867100794
DMA|2019|-36.1951486634089
DMA|2018|-41.1963949394604
DMA|2017|-10.2099529307271
DMA|2016|-8.45275386663789
DMA|2015|-6.56710220155754
DMA|2014|-6.21279255214796
DMA|2013|-17.0836404533407
DMA|2012|-16.518817887546
DMA|2011|-13.3467421657827
DMA|2010|-16.9329365473543
DMA|2009|-19.6705453623387
DMA|2008|-24.5182774836172
DMA|2007|-17.2068339558123
DMA|2006|-6.98675382958053
DMA|2005|-16.0912002305889
DMA|2004|-8.40775392872234
DMA|2003|-6.04714179505929
DMA|2002|-8.85156806005728
DMA|2001|-11.6177894763262
DMA|2000|-19.9386602693651
DMA|1999|-10.7831426179179
DMA|1998|-7.15327796349265
DMA|1997|-13.9450169300915
DMA|1996|-17.5044667181976
DMA|1995|-14.6584638631427
DOM|2024|-2.98151999182261
DOM|2023|-3.66805408423949
DOM|2022|-5.77106930088549
DOM|2021|-2.83108026347322
DOM|2020|-1.69224227999815
DOM|2019|-1.33253119353171
DOM|2018|-1.55480224260577
DOM|2017|-0.168331272949702
DOM|2016|-1.07831727382895
DOM|2015|-1.8040834790462
DOM|2014|-3.23841188766658
DOM|2013|-4.10500018404706
DOM|2012|-6.55624631595726
DOM|2011|-7.52170967420317
DOM|2010|-7.47847811387321
DOM|2009|-4.77544466541589
DOM|2008|-9.39813947302595
DOM|2007|-4.92727717051081
DOM|2006|-3.39866888826109
DOM|2005|-1.32180615715461
DOM|2004|4.66562998909679
DOM|2003|4.8412459657921
DOM|2002|-2.94021829945032
DOM|2001|-2.89354387031244
DOM|2000|-4.22327517754885
DOM|1999|-1.93887227246899
DOM|1998|-1.56144626408778
DOM|1997|-0.814289530702647
DOM|1996|-1.16601469767881
DOM|1995|-1.09873129454882
ECU|2024|5.73299152089396
ECU|2023|2.03684150140058
ECU|2022|1.888909261189
ECU|2021|2.77781145157727
ECU|2020|2.02223218059056
ECU|2019|-0.574297342930601
ECU|2018|-1.58231661962755
ECU|2017|-0.410411806889765
ECU|2016|0.899463902209004
ECU|2015|-2.28484408591192
ECU|2014|-0.651047970913704
ECU|2013|-0.966037832420015
ECU|2012|-0.166909556494228
ECU|2011|-0.506587087684931
ECU|2010|-2.32172616604527
ECU|2009|0.520924336749102
ECU|2008|2.89405288656368
ECU|2007|3.78442738247702
ECU|2006|3.80804965411109
ECU|2005|1.17661120468016
ECU|2004|-1.36219189560774
ECU|2003|-1.24920361685129
ECU|2002|-4.50586234491732
ECU|2001|-2.38325088255005
ECU|2000|6.34355414802445
ECU|1999|4.67349075269474
ECU|1998|-7.49949156007604
ECU|1997|-1.62196981722165
ECU|1996|-0.217391362976912
ECU|1995|-4.09288556316314
ESP|2024|3.18327391138732
ESP|2023|2.73246084042226
ESP|2022|0.379418337465124
ESP|2021|0.765004613238441
ESP|2020|0.819280213926566
ESP|2019|2.11978917805627
ESP|2018|1.86142647160726
ESP|2017|2.82857699785742
ESP|2016|3.15808866042231
ESP|2015|2.03697429462383
ESP|2014|1.73595007328569
ESP|2013|2.07791536141212
ESP|2012|0.125923054524352
ESP|2011|-2.58929008588059
ESP|2010|-3.57734356702049
ESP|2009|-3.94046083652282
ESP|2008|-8.8166948769233
ESP|2007|-9.36792330694923
ESP|2006|-8.79382150381904
ESP|2005|-7.21356556640438
ESP|2004|-5.42400165587703
ESP|2003|-3.80656644846324
ESP|2002|-3.6345919631106
ESP|2001|-4.3292603031356
ESP|2000|-4.25952269013291
ESP|1999|-3.21736413464958
ESP|1998|-1.17199231308045
ESP|1997|-0.140683569181923
ESP|1996|-0.347834725925519
ESP|1995|-0.320247040380478
EST|2024|-1.66915910318203
EST|2023|-1.51872623402899
EST|2022|-2.89194977179356
EST|2021|-3.78107390163543
EST|2020|-2.7306242700292
EST|2019|2.00905944057614
EST|2018|0.563761631353159
EST|2017|1.69970978175346
EST|2016|0.996247381037251
EST|2015|1.46327360938589
EST|2014|0.518408483980374
EST|2013|-0.133143040301748
EST|2012|-1.85807259126916
EST|2011|1.30548764458293
EST|2010|1.74366049478647
EST|2009|2.6775190631377
EST|2008|-8.85851078522045
EST|2007|-14.8020314240803
EST|2006|-14.9718681033251
EST|2005|-8.63305003795734
EST|2004|-11.9829822415601
EST|2003|-12.9205377766597
EST|2002|-10.5743364533738
EST|2001|-5.19375871381401
EST|2000|-5.25815799294368
EST|1999|-5.11809353076672
EST|1998|-8.43191028086133
EST|1997|-10.898015356172
EST|1996|-8.32080873340359
EST|1995|-3.50447680786974
ETH|2024|-2.53176480495897
ETH|2023|-3.52359702026291
ETH|2022|-4.19066632561125
ETH|2021|-4.13241831248994
ETH|2020|-2.75526110013781
ETH|2019|-5.47194445069538
ETH|2018|-5.53324917435326
ETH|2017|-7.76343039992896
ETH|2016|-11.5449209376397
ETH|2015|-12.1838327178752
ETH|2014|-10.3781721184147
ETH|2013|-6.36626399169653
ETH|2012|-7.1067486808021
ETH|2011|-3.30367964138338
ETH|2010|-2.1222608717343
ETH|2009|-6.75348362103612
ETH|2008|-6.67139557726763
ETH|2007|-4.20144598076542
ETH|2006|-11.6871605564419
ETH|2005|-12.6419842587598
ETH|2004|-6.59189372254429
ETH|2003|-1.58150719828577
ETH|2002|-1.74046524518375
ETH|2001|-4.53620596538169
ETH|2000|0.163268897783397
ETH|1999|-5.89415732214505
ETH|1998|-4.15073883771035
ETH|1997|-0.457223674441712
ETH|1996|0.908197347576536
ETH|1995|0.50129599614824
FJI|2024|-7.78080984551747
FJI|2023|-6.61225780515816
FJI|2022|-15.5083711760819
FJI|2021|-7.20401590434094
FJI|2020|-12.1311588430209
FJI|2019|-11.7772709740163
FJI|2018|-8.44729845329711
FJI|2017|-6.639070882176
FJI|2016|-3.60696936050466
FJI|2015|-3.47299248987541
FJI|2014|-5.77781240557738
FJI|2013|-9.71178073518758
FJI|2012|-1.4340442908102
FJI|2011|-5.16119192694594
FJI|2010|-4.7591968754889
FJI|2009|-4.31924967284106
FJI|2008|-14.9382363262539
FJI|2007|-11.4545752332218
FJI|2006|-16.4488939915362
FJI|2005|-6.89584542628475
FJI|2004|-9.27687175758032
FJI|2003|-2.28236251772105
FJI|2002|0.858878837529476
FJI|2001|-4.09110110593277
FJI|2000|-1.51980018386888
FJI|1999|0.655462625521091
FJI|1998|-3.62307870193135
FJI|1997|-1.63374867444326
FJI|1996|0.636047134440278
FJI|1995|-5.72016176808459
GBR|2024|-2.9506331555927
GBR|2023|-3.57676183842871
GBR|2022|-2.06737101121871
GBR|2021|-0.752836357784011
GBR|2020|-2.92883387550298
GBR|2019|-2.66245642145608
GBR|2018|-3.88728858372976
GBR|2017|-3.47326460218152
GBR|2016|-5.46283821927875
GBR|2015|-4.91700489264854
GBR|2014|-4.97786981840051
GBR|2013|-4.63114682704937
GBR|2012|-3.13257837481106
GBR|2011|-1.6237867474026
GBR|2010|-2.75934253189813
GBR|2009|-3.01852853421921
GBR|2008|-3.86567706212854
GBR|2007|-3.71636602944722
GBR|2006|-3.10941980167091
GBR|2005|-1.97517731781616
GBR|2004|-2.28435751976608
GBR|2003|-1.82204886055783
GBR|2002|-1.96774674220137
GBR|2001|-1.75946787442188
GBR|2000|-1.80322397590519
GBR|1999|-2.10815347133567
GBR|1998|-0.317493408980744
GBR|1997|-0.089379760284927
GBR|1996|-0.724668922297665
GBR|1995|-0.995954431591391
GEO|2024|-5.29948694239513
GEO|2023|-5.52924307584784
GEO|2022|-2.58183727549166
GEO|2021|-10.2864489440195
GEO|2020|-12.4222857463116
GEO|2019|-5.99374849041915
GEO|2018|-6.65935234039703
GEO|2017|-7.95124743463903
GEO|2016|-12.2417329389245
GEO|2015|-11.6071164150782
GEO|2014|-9.93087844279949
GEO|2013|-5.45445307967912
GEO|2012|-11.1441786727056
GEO|2011|-11.9098234516365
GEO|2010|-9.6468391223966
GEO|2009|-10.5986282901093
GEO|2008|-21.9709187774567
GEO|2007|-19.5819311413511
GEO|2006|-15.3810743163939
GEO|2005|-10.8511554489972
GEO|2004|-6.94983213970616
GEO|2003|-9.57586165079388
GEO|2002|-6.3877422128611
GEO|2001|-6.12197073672485
GEO|2000|-5.75310242328275
GEO|1999|-7.08564878719989
GEO|1998|-7.6297275422632
GEO|1997|-14.6474016992689
GEO|1996|
GEO|1995|
GHA|2024|1.91923157284387
GHA|2023|-0.911884130701339
GHA|2022|-2.33126484632355
GHA|2021|-2.8205574143058
GHA|2020|-3.04816313374944
GHA|2019|-2.72699375813964
GHA|2018|-3.03986602950098
GHA|2017|-3.31643027470141
GHA|2016|-5.04424020618629
GHA|2015|-5.7116156025854
GHA|2014|-6.75690272053076
GHA|2013|-9.07624953901069
GHA|2012|-11.9009237632838
GHA|2011|-9.00258173366362
GHA|2010|-8.5327330566748
GHA|2009|-7.28314283327412
GHA|2008|-11.6021635051277
GHA|2007|-9.58130961421888
GHA|2006|-5.05660776463669
GHA|2005|-10.280631865678
GHA|2004|-6.64520344576759
GHA|2003|1.33224533437262
GHA|2002|-1.70668468981884
GHA|2001|-8.04286187367619
GHA|2000|-7.75495051706689
GHA|1999|-12.4939914333473
GHA|1998|-6.9730710672988
GHA|1997|-5.85456469341193
GHA|1996|-4.42593921260815
GHA|1995|-2.22295003676613
GIN|2024|-1.56673613616474
GIN|2023|8.48425837744304
GIN|2022|16.8265386883899
GIN|2021|27.1761588078073
GIN|2020|19.0560604764664
GIN|2019|-2.34042432173531
GIN|2018|-1.60638873400794
GIN|2017|5.03018582642408
GIN|2016|-31.9328390727134
GIN|2015|-11.6007986964145
GIN|2014|-11.1827727004958
GIN|2013|-14.2034724942303
GIN|2012|-13.5979829951241
GIN|2011|-17.1165293375314
GIN|2010|-4.7697025907998
GIN|2009|-6.005146411906
GIN|2008|-6.29234168357033
GIN|2007|-7.23648388311734
GIN|2006|-5.2452359968981
GIN|2005|-3.74410214282105
GIN|2004|-3.06276375818202
GIN|2003|-3.68667076245062
GIN|2002|-4.64074253447312
GIN|2001|-1.44260287136746
GIN|2000|-3.20759051700664
GIN|1999|-3.98363958959634
GIN|1998|-2.95227188360417
GIN|1997|-1.65086793613531
GIN|1996|-3.14235704551243
GIN|1995|-4.01956723410899
GMB|2024|-4.14959872463031
GMB|2023|-5.03989672361148
GMB|2022|-4.09350427164042
GMB|2021|-4.31333160293426
GMB|2020|-4.77621848558059
GMB|2019|-2.04445221575257
GMB|2018|-8.08332529672771
GMB|2017|-6.32875593450885
GMB|2016|-5.12796647463839
GMB|2015|-3.90228061316891
GMB|2014|-6.87758719722138
GMB|2013|-7.05935659160072
GMB|2012|-6.55707152697875
GMB|2011|-7.67135227929092
GMB|2010|1.13391181749086
GMB|2009|1.93110412724461
GMB|2008|-0.402650265042616
GMB|2007|-6.19477968023257
GMB|2006|-6.22324623229531
GMB|2005|-4.22219702002327
GMB|2004|-3.15228070444892
GMB|2003|0.54119657188913
GMB|2002|
GMB|2001|
GMB|2000|
GMB|1999|
GMB|1998|
GMB|1997|-2.85622127623816
GMB|1996|-5.55018808592489
GMB|1995|-1.035486078866
GNB|2024|-7.35889637109663
GNB|2023|-7.7124653882874
GNB|2022|-7.8998258282318
GNB|2021|-0.740601759118054
GNB|2020|-2.26872986569478
GNB|2019|-7.98200773254712
GNB|2018|-3.48324795461301
GNB|2017|0.263885195365577
GNB|2016|1.36293739261607
GNB|2015|1.81726336561494
GNB|2014|0.555849591467734
GNB|2013|-4.73187653933365
GNB|2012|-7.93224654147768
GNB|2011|-1.21431910534762
GNB|2010|-7.52999517168867
GNB|2009|-5.34847492021888
GNB|2008|-3.02102465076755
GNB|2007|-4.06952969493394
GNB|2006|-6.3132458528375
GNB|2005|-1.63867591635847
GNB|2004|2.38148745518108
GNB|2003|-0.0519018620590297
GNB|2002|-0.271719275957978
GNB|2001|-2.69821108512442
GNB|2000|
GNB|1999|
GNB|1998|
GNB|1997|-0.913899727016268
GNB|1996|-6.32606042473747
GNB|1995|-5.32872538837755
GRC|2024|-7.10950344070576
GRC|2023|-6.77841375377555
GRC|2022|-10.8779875356728
GRC|2021|-7.1523233874729
GRC|2020|-7.12181074881181
GRC|2019|-2.11808020939794
GRC|2018|-3.55679128954824
GRC|2017|-2.38344142611836
GRC|2016|-2.30350655253683
GRC|2015|-1.5031156236834
GRC|2014|-1.43786972023484
GRC|2013|-2.13029886404193
GRC|2012|-2.58418506053025
GRC|2011|-10.0976272377955
GRC|2010|-10.2094499511211
GRC|2009|-10.9982860428605
GRC|2008|-14.6094922064777
GRC|2007|-14.1869570945957
GRC|2006|-10.9919390863756
GRC|2005|-7.51860335220303
GRC|2004|-5.74201400267067
GRC|2003|-6.5062606053612
GRC|2002|-6.38625728965696
GRC|2001|-7.1208377005018
GRC|2000|-7.80647954386925
GRC|1999|-5.31917093747904
GRC|1998|
GRC|1997|-3.50229712684898
GRC|1996|-3.19572255088179
GRC|1995|-2.12188049067422
GRD|2024|-21.8875634999164
GRD|2023|-20.295039117819
GRD|2022|-12.127765960022
GRD|2021|-14.3794506270627
GRD|2020|-16.1060034218251
GRD|2019|-10.3282132272823
GRD|2018|-12.7578936321221
GRD|2017|-11.4635306675494
GRD|2016|-8.84957467526885
GRD|2015|-10.6165101004821
GRD|2014|-9.08236900654942
GRD|2013|-17.0640979875268
GRD|2012|-14.9830707473175
GRD|2011|-18.6656495604378
GRD|2010|-19.4482994535286
GRD|2009|-16.922787751426
GRD|2008|-26.310483241865
GRD|2007|-29.2906558652577
GRD|2006|-35.3579767652673
GRD|2005|-36.197096036622
GRD|2004|-21.9094311537962
GRD|2003|-26.3551417555989
GRD|2002|-24.5623129443555
GRD|2001|-25.1924121595876
GRD|2000|-21.9966277175388
GRD|1999|-11.5657809941147
GRD|1998|-18.2799852849773
GRD|1997|-17.6170958451229
GRD|1996|-15.4008298904297
GRD|1995|-12.2182247681427
GTM|2024|2.91516242849223
GTM|2023|3.07965306360278
GTM|2022|1.16742742017368
GTM|2021|2.16690668305723
GTM|2020|5.04131108756311
GTM|2019|2.36029015844232
GTM|2018|0.885829296285522
GTM|2017|1.19614067972898
GTM|2016|0.964776364019979
GTM|2015|-1.24431005683082
GTM|2014|-3.30031992366676
GTM|2013|-4.22440069065832
GTM|2012|-3.7248017027558
GTM|2011|-3.37024214653633
GTM|2010|-1.88548550474234
GTM|2009|0.194641494950958
GTM|2008|-4.03483780515022
GTM|2007|-5.31937540284176
GTM|2006|-5.12367991314268
GTM|2005|-4.63346885034308
GTM|2004|-4.93864901451057
GTM|2003|-4.81631890533668
GTM|2002|-6.04021558283228
GTM|2001|-6.80733057120201
GTM|2000|-5.44146333041507
GTM|1999|-5.60037620030961
GTM|1998|-5.35743048114144
GTM|1997|-3.56098407112146
GTM|1996|-2.87722315607179
GTM|1995|-3.90367937373989
GUY|2024|
GUY|2023|13.9022287975489
GUY|2022|28.8207770246115
GUY|2021|-16.9076142307927
GUY|2020|-11.6095974967976
GUY|2019|-57.1070048116682
GUY|2018|-26.677311081907
GUY|2017|-2.5604255246699
GUY|2016|3.37225553747117
GUY|2015|-0.907095962415786
GUY|2014|-9.33174702245427
GUY|2013|-10.9417365700277
GUY|2012|-9.02441909942374
GUY|2011|-10.0853362607878
GUY|2010|-7.1762463185401
GUY|2009|-7.28409727303008
GUY|2008|-10.6229329472303
GUY|2007|-6.06659550320194
GUY|2006|-7.59053846582146
GUY|2005|-11.6705382324577
GUY|2004|-2.52795588989275
GUY|2003|-6.00217518033652
GUY|2002|-8.57971395005412
GUY|2001|-12.7638520939434
GUY|2000|-11.5341241520002
GUY|1999|-7.12481390368902
GUY|1998|-7.74879755028687
GUY|1997|-8.42301407676256
GUY|1996|-4.63562826712069
GUY|1995|-21.679406848842
HND|2024|-4.31420899094408
HND|2023|-4.21839287405186
HND|2022|-6.86234245630111
HND|2021|-5.4643429246452
HND|2020|2.85135257343249
HND|2019|-2.65600856407128
HND|2018|-6.57234650779592
HND|2017|-1.24589511291671
HND|2016|-3.14341400861299
HND|2015|-4.67090141649466
HND|2014|-6.94516636573265
HND|2013|-9.52729388609888
HND|2012|-8.53140502862293
HND|2011|-7.95391811894244
HND|2010|-5.07642907628294
HND|2009|-3.8159630413154
HND|2008|-15.3428520557685
HND|2007|-9.02947363444763
HND|2006|-3.50496253709121
HND|2005|-3.11914125682689
HND|2004|-7.70512924930615
HND|2003|-6.71681853158575
HND|2002|-3.58312677859623
HND|2001|-6.25613323410572
HND|2000|-7.07233719340069
HND|1999|-3.76754124016949
HND|1998|-2.39628501520551
HND|1997|-4.88761475093091
HND|1996|-6.98919712345692
HND|1995|-4.29976700485183
HRV|2024|-2.07644437837535
HRV|2023|0.742770464300461
HRV|2022|-3.68089506718041
HRV|2021|0.807925529114754
HRV|2020|-0.794765051844059
HRV|2019|2.63941792603541
HRV|2018|1.21879064714283
HRV|2017|4.05062583497585
HRV|2016|2.46277827626192
HRV|2015|2.81601870409877
HRV|2014|0.393645362353837
HRV|2013|-0.859043507575465
HRV|2012|-0.361350846502068
HRV|2011|-1.66262829958419
HRV|2010|-2.51842606374934
HRV|2009|-6.55715378614146
HRV|2008|-10.9283631681248
HRV|2007|-8.0157513023774
HRV|2006|-7.88444049141193
HRV|2005|-7.53592292439689
HRV|2004|-6.14983455198819
HRV|2003|-9.10677009409677
HRV|2002|-6.21034279481766
HRV|2001|-2.23832233480714
HRV|2000|-1.52725198523811
HRV|1999|-6.31892365799792
HRV|1998|-5.28891920168529
HRV|1997|-10.3394186884751
HRV|1996|-4.51908633064761
HRV|1995|-6.3317804259207
HTI|2024|-0.598367468302651
HTI|2023|-3.48716065487915
HTI|2022|-2.44594832666715
HTI|2021|0.422336531055296
HTI|2020|0.355302483558182
HTI|2019|-1.12265260280797
HTI|2018|-2.89019632961826
HTI|2017|-2.15252938271163
HTI|2016|-1.69084789043559
HTI|2015|-1.82345284080223
HTI|2014|-4.95582102756805
HTI|2013|-3.76338389441215
HTI|2012|-3.14501833525928
HTI|2011|-2.48774144631427
HTI|2010|-0.85860185595704
HTI|2009|-1.05359702519351
HTI|2008|-1.96314882897523
HTI|2007|-0.929422111465849
HTI|2006|-1.11312873282486
HTI|2005|0.100253910234458
HTI|2004|-1.02474624447533
HTI|2003|-0.882895522214382
HTI|2002|-1.43332565140445
HTI|2001|-2.08307988263304
HTI|2000|-1.67621475073065
HTI|1999|-1.44015280913738
HTI|1998|0.770965151911996
HTI|1997|-1.42859318409066
HTI|1996|-4.73668671245739
HTI|1995|-3.09492727510262
HUN|2024|1.84213300452467
HUN|2023|-0.00798002024458191
HUN|2022|-8.78389100676718
HUN|2021|-4.28505680487641
HUN|2020|-1.03428088875148
HUN|2019|-0.606737568975118
HUN|2018|0.340906702488933
HUN|2017|1.71954655139941
HUN|2016|4.40234047330024
HUN|2015|2.11856059497338
HUN|2014|0.747477578049868
HUN|2013|2.99109062228032
HUN|2012|1.0790451227521
HUN|2011|0.428842717780173
HUN|2010|-0.188218208390541
HUN|2009|-1.21974951373381
HUN|2008|-7.26832036226062
HUN|2007|-7.28636440088967
HUN|2006|-7.28544270320023
HUN|2005|-9.88681019702465
HUN|2004|-9.08123363089424
HUN|2003|-8.26371787576548
HUN|2002|-6.44836058797406
HUN|2001|-6.11450861059176
HUN|2000|-8.82808863842537
HUN|1999|-8.35837228319571
HUN|1998|-7.62873647734146
HUN|1997|-4.51433363272401
HUN|1996|-3.95886426279274
HUN|1995|-3.67533531615297
IND|2024|-0.851289719084461
IND|2023|-0.912777939495826
IND|2022|-2.43238270956779
IND|2021|-1.05524166809383
IND|2020|1.22362111042791
IND|2019|-1.04961203910072
IND|2018|-2.42697545810527
IND|2017|-1.43948820320988
IND|2016|-0.527880606037518
IND|2015|-1.06754907167964
IND|2014|-1.33950896483452
IND|2013|-2.64566711733892
IND|2012|-5.00488971805303
IND|2011|-3.42928468606061
IND|2010|-3.25348368945179
IND|2009|-1.95146209111801
IND|2008|-2.58337749259837
IND|2007|-0.663717648772608
IND|2006|-0.988988302952292
IND|2005|-1.25350400207393
IND|2004|0.110018010197154
IND|2003|1.44355773291234
IND|2002|1.37093793900847
IND|2001|0.290495460210206
IND|2000|-0.982342580017137
IND|1999|-0.70354723219324
IND|1998|-1.63832533358649
IND|1997|-0.713014326393887
IND|1996|-1.51595497295367
IND|1995|-1.54413181166043
ISL|2024|-3.42802927110367
ISL|2023|-1.38564800497475
ISL|2022|-1.87514597472064
ISL|2021|-2.57256903046463
ISL|2020|1.89912365465565
ISL|2019|7.364158701341
ISL|2018|4.44167966704129
ISL|2017|4.93029350539422
ISL|2016|9.09605366960113
ISL|2015|6.30235309571197
ISL|2014|4.94536463319528
ISL|2013|6.81968727360492
ISL|2012|-2.8528256872604
ISL|2011|-4.48003338933171
ISL|2010|-5.89839823423039
ISL|2009|-8.86751863700179
ISL|2008|-22.9534270277153
ISL|2007|-13.6329211934758
ISL|2006|-22.6640150645583
ISL|2005|-15.5493858867543
ISL|2004|-9.96753224056789
ISL|2003|-4.81453736951882
ISL|2002|1.35331007867555
ISL|2001|-4.46418784541977
ISL|2000|-9.90092821228739
ISL|1999|-6.90314554092756
ISL|1998|-7.0075015498706
ISL|1997|-2.2351221013021
ISL|1996|-2.29207429851172
ISL|1995|0.246166665235896
ISR|2024|3.00888189977143
ISR|2023|2.39188897010142
ISR|2022|2.12119039124757
ISR|2021|2.75199841930662
ISR|2020|3.74263006004638
ISR|2019|2.78644375330205
ISR|2018|2.49947784006567
ISR|2017|3.15238813787445
ISR|2016|3.17038576605094
ISR|2015|4.58316122327641
ISR|2014|3.48320911858055
ISR|2013|2.25546232136474
ISR|2012|-0.263249785684165
ISR|2011|0.959067083330989
ISR|2010|2.69529305304405
ISR|2009|2.83178873308842
ISR|2008|0.42592870301179
ISR|2007|2.15414696320513
ISR|2006|3.28688457879504
ISR|2005|2.22116596590879
ISR|2004|0.838946900869189
ISR|2003|-0.548526889573223
ISR|2002|-2.28341493296422
ISR|2001|-2.59539018083479
ISR|2000|-2.36500425391523
ISR|1999|-2.45653891755964
ISR|1998|-1.67470943283547
ISR|1997|-3.56430592245336
ISR|1996|-5.27300893243401
ISR|1995|-5.07586309660035
JAM|2024|2.9338309393918
JAM|2023|2.65622781756862
JAM|2022|-0.72501369030751
JAM|2021|0.934998829682956
JAM|2020|-1.04604876207357
JAM|2019|-1.77745675976269
JAM|2018|-1.39317798037996
JAM|2017|-2.5183339037553
JAM|2016|-0.291717768383903
JAM|2015|-2.87431658057774
JAM|2014|-8.0173872721953
JAM|2013|-9.51223858387756
JAM|2012|-9.72634702774029
JAM|2011|-14.283409237551
JAM|2010|-7.06479945013375
JAM|2009|-9.3024726659181
JAM|2008|-20.3748078735041
JAM|2007|-15.9234659804591
JAM|2006|-9.91484107251583
JAM|2005|-9.52805454519088
JAM|2004|-4.92950870317959
JAM|2003|-8.20081771864531
JAM|2002|-11.0508689241364
JAM|2001|-8.25255531148696
JAM|2000|-4.07992636835457
JAM|1999|-2.43387631839692
JAM|1998|-3.79870910291059
JAM|1997|-3.95474226120464
JAM|1996|-1.92861894016571
JAM|1995|-1.50360607545815
KEN|2024|-1.75858874840526
KEN|2023|-2.81601276856738
KEN|2022|-4.19995258299619
KEN|2021|-4.5990081153926
KEN|2020|-3.26911007065288
KEN|2019|-5.2385293590781
KEN|2018|-5.4110667914175
KEN|2017|-6.99683322084962
KEN|2016|-5.39700863817028
KEN|2015|-6.30459656347731
KEN|2014|-9.34004850596924
KEN|2013|-7.85152228564966
KEN|2012|-7.47587166159348
KEN|2011|-8.14880935200662
KEN|2010|-5.21669389712651
KEN|2009|-3.98728888063669
KEN|2008|-5.52329630288282
KEN|2007|-3.2293696026957
KEN|2006|-1.97646990538246
KEN|2005|-1.34655849731384
KEN|2004|-0.818703017571567
KEN|2003|0.888450320310784
KEN|2002|-0.894975876340371
KEN|2001|-2.46632258412886
KEN|2000|-1.5693516563302
KEN|1999|-18.3407041847877
KEN|1998|-18.6798241248732
KEN|1997|-13.6528022501099
KEN|1996|-7.97941568440556
KEN|1995|-17.4462157792244
KGZ|2024|-22.6410105179247
KGZ|2023|-44.9281659368624
KGZ|2022|-42.3794795657648
KGZ|2021|-7.97583742281609
KGZ|2020|4.52522127933727
KGZ|2019|-11.3840798908834
KGZ|2018|-11.6275560440075
KGZ|2017|-6.95269622627313
KGZ|2016|-11.628233310749
KGZ|2015|-15.7592478411185
KGZ|2014|-17.4244156605428
KGZ|2013|-13.7754189892495
KGZ|2012|-15.5252325924144
KGZ|2011|-7.69730261933363
KGZ|2010|-9.89833859355209
KGZ|2009|-4.31423765842016
KGZ|2008|-13.8763673181829
KGZ|2007|-5.98595362572476
KGZ|2006|-10.0953913600934
KGZ|2005|-1.52182901572015
KGZ|2004|1.32375512838834
KGZ|2003|-2.19733510264456
KGZ|2002|-1.82590999500266
KGZ|2001|-1.2453482434873
KGZ|2000|-5.55490834350204
KGZ|1999|-14.7114078976095
KGZ|1998|-22.1096826975893
KGZ|1997|-7.83516136995408
KGZ|1996|-23.2415099703837
KGZ|1995|-14.1298148219336
KHM|2024|0.479815694572051
KHM|2023|1.30486018790951
KHM|2022|-18.9521042763782
KHM|2021|-29.5745150389482
KHM|2020|-0.9628790792848
KHM|2019|-7.99991923360397
KHM|2018|-8.7358230451204
KHM|2017|-6.1566420507123
KHM|2016|-6.52773923371676
KHM|2015|-6.61221348694339
KHM|2014|-6.55176399019618
KHM|2013|-6.54160754946616
KHM|2012|-6.802614563021
KHM|2011|-6.3986617266464
KHM|2010|-7.10406918806883
KHM|2009|-5.92994303077878
KHM|2008|-6.73529622284658
KHM|2007|-4.17983206597175
KHM|2006|-2.80064293867027
KHM|2005|-4.34447481248578
KHM|2004|-3.10902285879404
KHM|2003|-4.6255631414654
KHM|2002|-2.38394601973682
KHM|2001|-2.11975415828821
KHM|2000|-3.68398765175244
KHM|1999|-5.33253322476225
KHM|1998|-5.56266216908926
KHM|1997|-6.09569564582159
KHM|1996|-5.27277000305394
KHM|1995|-5.39636443070654
KNA|2024|-12.189028494118
KNA|2023|-13.4429756934454
KNA|2022|-10.6193571735864
KNA|2021|-3.35211367910692
KNA|2020|-10.8380413895977
KNA|2019|-4.78511635759442
KNA|2018|-5.84580153302049
KNA|2017|-10.2532816485857
KNA|2016|-12.0811606049124
KNA|2015|-8.10718614819114
KNA|2014|0.698262924495273
KNA|2013|-2.86459110864067
KNA|2012|-3.12891542335695
KNA|2011|-7.81462598635504
KNA|2010|-15.3287283630879
KNA|2009|-21.1253307397586
KNA|2008|-17.1935240173318
KNA|2007|-13.8968818612708
KNA|2006|-11.0598682210987
KNA|2005|-7.23180980362048
KNA|2004|-7.70263043844735
KNA|2003|-17.7390647418292
KNA|2002|-19.9706256978221
KNA|2001|-22.5205550309293
KNA|2000|-25.4692655371034
KNA|1999|-16.5265722023142
KNA|1998|-12.082588802043
KNA|1997|-16.1260420377627
KNA|1996|-19.4876060555648
KNA|1995|-14.5024279013717
LAO|2024|3.1714612688116
LAO|2023|2.55329592767602
LAO|2022|-2.96567805589964
LAO|2021|2.29262780940357
LAO|2020|-1.60378619154944
LAO|2019|-7.04124343564555
LAO|2018|-9.08923603390851
LAO|2017|-7.37970657985848
LAO|2016|-8.70356040600564
LAO|2015|-15.7184889292204
LAO|2014|-14.4922715355556
LAO|2013|-7.82702813174138
LAO|2012|-7.33751463250306
LAO|2011|-2.35798203498442
LAO|2010|0.410966616116085
LAO|2009|-1.04359478297296
LAO|2008|1.42375423290882
LAO|2007|3.30099767237269
LAO|2006|2.17967841617852
LAO|2005|-6.35287280117623
LAO|2004|-7.53199402235116
LAO|2003|-1.46818009608596
LAO|2002|0.47045153495805
LAO|2001|-3.80683721990308
LAO|2000|-0.489256566266576
LAO|1999|6.16736181031808
LAO|1998|-5.97573225268029
LAO|1997|-11.791562783936
LAO|1996|-14.1486911060263
LAO|1995|-13.4218955056777
LBN|2024|
LBN|2023|-28.103669636709
LBN|2022|-34.606227109401
LBN|2021|-19.6978128626341
LBN|2020|-8.76184199911137
LBN|2019|-21.828092491848
LBN|2018|-24.3470417876755
LBN|2017|-22.8822040339123
LBN|2016|-20.4780237123596
LBN|2015|-17.1077378092157
LBN|2014|-26.2298655609816
LBN|2013|-25.5114319532074
LBN|2012|-23.4382140171445
LBN|2011|-13.8340690487529
LBN|2010|-19.6443379596193
LBN|2009|-19.0424176351022
LBN|2008|-14.0893224912248
LBN|2007|-6.4637503869807
LBN|2006|-5.06914682104357
LBN|2005|-12.7829830371367
LBN|2004|-20.8205658199381
LBN|2003|-25.5858580911917
LBN|2002|-23.7091629307817
LBN|2001|
LBN|2000|
LBN|1999|
LBN|1998|
LBN|1997|
LBN|1996|
LBN|1995|
LBR|2024|2.5063227720412
LBR|2023|-11.5068290648574
LBR|2022|-8.71094478928873
LBR|2021|-2.83280554425972
LBR|2020|-10.3043027389936
LBR|2019|-19.6832166735006
LBR|2018|-19.6944373252366
LBR|2017|-16.6798323783013
LBR|2016|-8.12261279894878
LBR|2015|5.3024253714189
LBR|2014|-19.9198359881725
LBR|2013|-32.8209688370026
LBR|2012|-59.9955509928998
LBR|2011|-52.4853470186802
LBR|2010|-42.7136316998038
LBR|2009|-15.6782479232001
LBR|2008|-20.5275176083252
LBR|2007|-16.2534531227222
LBR|2006|-15.4436442263207
LBR|2005|-19.3410307528499
LBR|2004|-17.8067908816867
LBR|2003|
LBR|2002|
LBR|2001|
LBR|2000|
LBR|1999|
LBR|1998|
LBR|1997|
LBR|1996|
LBR|1995|
LCA|2024|-1.53670013790358
LCA|2023|-2.12025739600085
LCA|2022|-3.32617930296789
LCA|2021|-10.3860164489311
LCA|2020|-18.6599979555577
LCA|2019|3.33404977672243
LCA|2018|1.47239642153267
LCA|2017|-1.90842804054587
LCA|2016|-6.33820254412729
LCA|2015|-0.477234056484728
LCA|2014|-2.42897703597573
LCA|2013|-6.53053409169977
LCA|2012|-10.0247004570207
LCA|2011|-14.3071211652342
LCA|2010|-12.6704280191935
LCA|2009|-8.46949402978313
LCA|2008|-24.2393485824395
LCA|2007|-18.3824804800027
LCA|2006|-29.3295746576677
LCA|2005|-15.5065043802058
LCA|2004|-14.87434137709
LCA|2003|-20.9315483729512
LCA|2002|-17.6189580491341
LCA|2001|-18.8265127326629
LCA|2000|-17.8343762887704
LCA|1999|-12.0397750100441
LCA|1998|-6.85647952722667
LCA|1997|-9.7642463235294
LCA|1996|-7.33239436619718
LCA|1995|-4.74708737864078
LKA|2024|1.21195613729145
LKA|2023|1.71159541534781
LKA|2022|-1.95359411068217
LKA|2021|-3.70866603299244
LKA|2020|-1.40761495020571
LKA|2019|-2.07126631647204
LKA|2018|-2.96352841915886
LKA|2017|-2.44676434907529
LKA|2016|-1.97999493165089
LKA|2015|-2.21267766608825
LKA|2014|-2.4084055719608
LKA|2013|-3.30046822137756
LKA|2012|-5.69099820826854
LKA|2011|-6.81209765681019
LKA|2010|-1.83339431574737
LKA|2009|-0.510385718302903
LKA|2008|-9.54319542329735
LKA|2007|-4.33041626176129
LKA|2006|-5.29942775531871
LKA|2005|-2.66382240513017
LKA|2004|-3.1340311530145
LKA|2003|-0.374541248460878
LKA|2002|-1.42925945944237
LKA|2001|-1.36821186331088
LKA|2000|-6.28823142949348
LKA|1999|-3.57275187551122
LKA|1998|-1.44447657761178
LKA|1997|-2.61516855545627
LKA|1996|-4.91199982756748
LKA|1995|-5.90910994846491
LSO|2024|4.10543411889982
LSO|2023|-7.70531242621207
LSO|2022|-11.2115190789574
LSO|2021|-8.12794748247607
LSO|2020|-4.32125100035934
LSO|2019|-6.24755348705035
LSO|2018|-5.72866233880039
LSO|2017|-13.6498404869595
LSO|2016|-11.2325364601342
LSO|2015|-5.73228396984582
LSO|2014|-8.42016664486878
LSO|2013|-10.7579867652524
LSO|2012|-18.7652520307529
LSO|2011|-11.8566683946226
LSO|2010|-11.0020417569816
LSO|2009|-2.94530645950598
LSO|2008|15.7113939585121
LSO|2007|18.1419183617744
LSO|2006|11.9989367597937
LSO|2005|5.68794455057765
LSO|2004|1.75904831470621
LSO|2003|-1.48520681497293
LSO|2002|8.18759668831338
LSO|2001|3.45948826928832
LSO|2000|-8.6703357592323
LSO|1999|-18.2545264654224
LSO|1998|-21.8944421361771
LSO|1997|-22.9236378981082
LSO|1996|-22.846076502895
LSO|1995|-15.3062508116221
LTU|2024|3.2414405630064
LTU|2023|1.09311288313578
LTU|2022|-6.11893043425314
LTU|2021|1.46864331261859
LTU|2020|7.22470104088843
LTU|2019|3.73752991159912
LTU|2018|0.309996924920129
LTU|2017|1.08697261761581
LTU|2016|-1.01460897973493
LTU|2015|-2.51745557937896
LTU|2014|3.54699194706825
LTU|2013|1.70747298429575
LTU|2012|-1.606838534778
LTU|2011|-3.68690525403636
LTU|2010|0.19796045399168
LTU|2009|2.24459117154569
LTU|2008|-13.5865555459022
LTU|2007|-15.3448035059388
LTU|2006|-10.6838036897227
LTU|2005|-7.33728028606647
LTU|2004|-7.78077111235869
LTU|2003|-6.79642419021809
LTU|2002|-5.04608050801903
LTU|2001|-4.67813526904782
LTU|2000|-5.84291644362833
LTU|1999|-10.8335113412083
LTU|1998|-11.4996358238953
LTU|1997|-9.65097618681177
LTU|1996|-8.57167547493215
LTU|1995|-7.75594856924648
LVA|2024|-3.48962552226411
LVA|2023|-5.60465309312321
LVA|2022|-7.50738214220643
LVA|2021|-5.22321886067179
LVA|2020|2.42434835746322
LVA|2019|-1.04836027771746
LVA|2018|-1.21426803343967
LVA|2017|1.49941243385352
LVA|2016|1.75250981396433
LVA|2015|-0.134828422249822
LVA|2014|-1.55031567006615
LVA|2013|-2.8855289884358
LVA|2012|-3.86974112964083
LVA|2011|-3.55024462389464
LVA|2010|1.75850166439734
LVA|2009|8.01439427957829
LVA|2008|-13.1348906245122
LVA|2007|-21.8446033162048
LVA|2006|-22.1217320133029
LVA|2005|-12.1765171311226
LVA|2004|-12.1485756630769
LVA|2003|-7.55280447496836
LVA|2002|-5.65255950802705
LVA|2001|-6.11482755314462
LVA|2000|-3.74561890268537
LVA|1999|-8.93340754196004
LVA|1998|-9.31305535970457
LVA|1997|-5.43416067620327
LVA|1996|-4.82428958681789
LVA|1995|-0.288220368032761
MDA|2024|-16.5470767102724
MDA|2023|-11.0612264538806
MDA|2022|-17.0894479797469
MDA|2021|-12.4095546577967
MDA|2020|-7.6900486921726
MDA|2019|-9.42148010949479
MDA|2018|-10.7699247852566
MDA|2017|-5.83735984990539
MDA|2016|-3.61387040187984
MDA|2015|-5.93562136370789
MDA|2014|-6.04440067766107
MDA|2013|-5.16294162285185
MDA|2012|-7.39016827021289
MDA|2011|-10.1250094571942
MDA|2010|-6.90279523078091
MDA|2009|-8.91986143699656
MDA|2008|-16.1122760959283
MDA|2007|-15.2482071673217
MDA|2006|-11.3377651882737
MDA|2005|-7.55636173709232
MDA|2004|-1.7754260708042
MDA|2003|-6.56921155001991
MDA|2002|-1.19146609275515
MDA|2001|-1.80863629279978
MDA|2000|-7.62090655684757
MDA|1999|-5.79782952702232
MDA|1998|-19.703688169616
MDA|1997|-14.2424061971689
MDA|1996|-11.3165884413615
MDA|1995|-4.82658473389648
MDG|2024|-3.99926800401841
MDG|2023|-2.57169352318479
MDG|2022|-5.49417886108313
MDG|2021|-5.02937129931558
MDG|2020|-4.77842292738284
MDG|2019|-2.13564971662682
MDG|2018|0.712560880258364
MDG|2017|-0.228589799383037
MDG|2016|0.378142575318559
MDG|2015|-2.25941841339224
MDG|2014|-0.64912376658814
MDG|2013|-6.50549854289754
MDG|2012|-7.46271017824129
MDG|2011|-6.72775114409968
MDG|2010|-8.9485361713351
MDG|2009|-18.1718557648058
MDG|2008|-15.636461385028
MDG|2007|-9.88570197659671
MDG|2006|-9.15517433304636
MDG|2005|-12.5308217712467
MDG|2004|-7.87799247937726
MDG|2003|-5.14632639531452
MDG|2002|-8.91359828774941
MDG|2001|-2.57548758488005
MDG|2000|-5.62675808214078
MDG|1999|-5.24790671715343
MDG|1998|-6.57345320506215
MDG|1997|-4.73438947874968
MDG|1996|-3.09508028987329
MDG|1995|-7.19054123216569
MDV|2024|-18.5306914932865
MDV|2023|-21.1388087335441
MDV|2022|-16.868196658323
MDV|2021|-8.63308174559145
MDV|2020|-35.7483018974442
MDV|2019|-25.8168822522057
MDV|2018|-27.8019976962882
MDV|2017|-21.267761433937
MDV|2016|-23.4109557277276
MDV|2015|-7.30588031911147
MDV|2014|-3.18665825232612
MDV|2013|-3.86626742586717
MDV|2012|-6.3922910977274
MDV|2011|-13.8208553363039
MDV|2010|-7.57604640472633
MDV|2009|-9.41593217957294
MDV|2008|-26.9277527694823
MDV|2007|-14.3948746476646
MDV|2006|-19.1705839350464
MDV|2005|-23.4672692200603
MDV|2004|-9.9708472282721
MDV|2003|-2.97459860769224
MDV|2002|-3.96704001433817
MDV|2001|-6.74959538197381
MDV|2000|-8.24543127431548
MDV|1999|-13.3953146587577
MDV|1998|-4.04791854699075
MDV|1997|-6.8289803723186
MDV|1996|-1.65325346284258
MDV|1995|-4.55205734073564
MEX|2024|-0.91728055860713
MEX|2023|-0.570232624383335
MEX|2022|-1.02305637905876
MEX|2021|-0.340708629738092
MEX|2020|2.39710320563074
MEX|2019|-0.296844402020911
MEX|2018|-2.06414074440499
MEX|2017|-1.79746290782777
MEX|2016|-2.27311198277187
MEX|2015|-2.59917628224106
MEX|2014|-1.82131927652883
MEX|2013|-2.39396960169622
MEX|2012|-1.40984864759126
MEX|2011|-0.857892612318958
MEX|2010|-0.339592498675246
MEX|2009|-0.750921220817887
MEX|2008|-1.40680860932702
MEX|2007|-0.844640815368309
MEX|2006|-0.316555541136008
MEX|2005|-0.62353440164571
MEX|2004|-0.464775659455354
MEX|2003|-0.526761129534336
MEX|2002|-1.52936520808687
MEX|2001|-2.23003398954777
MEX|2000|-2.52707170138346
MEX|1999|-2.21778204046026
MEX|1998|-2.8688383681894
MEX|1997|-1.46431251799993
MEX|1996|-0.580284830782932
MEX|1995|-0.414680790187327
MKD|2024|-2.10020379336309
MKD|2023|0.317585046468375
MKD|2022|-6.23699171036603
MKD|2021|-2.67744223538636
MKD|2020|-2.91596537662612
MKD|2019|-2.98648910497822
MKD|2018|0.143273398779884
MKD|2017|-0.586294696197347
MKD|2016|-2.66389921940311
MKD|2015|-1.71222694530355
MKD|2014|-0.481713137157683
MKD|2013|-1.63764033882168
MKD|2012|-3.27478423718894
MKD|2011|-2.49367551945884
MKD|2010|-2.10791254447936
MKD|2009|-6.48354076815341
MKD|2008|-12.4707536603642
MKD|2007|-7.26623240489014
MKD|2006|-0.416080626106531
MKD|2005|-2.54533490974662
MKD|2004|-7.94691572310684
MKD|2003|-3.75035857468212
MKD|2002|-9.42563749802039
MKD|2001|-6.344343807859
MKD|2000|-2.73306730994392
MKD|1999|-1.69696104187635
MKD|1998|-7.43809653632584
MKD|1997|-7.04040325202006
MKD|1996|-6.20720983576967
MKD|1995|
MLI|2024|-4.32974251221218
MLI|2023|-6.49904215184634
MLI|2022|-6.54582121437751
MLI|2021|-6.3850831125797
MLI|2020|-1.83434524248166
MLI|2019|-6.29353963446866
MLI|2018|-4.10572622720131
MLI|2017|-6.62494382399689
MLI|2016|-6.06695219310335
MLI|2015|-4.47729474332982
MLI|2014|-3.96176216529395
MLI|2013|-2.38005150095351
MLI|2012|-1.84284683487062
MLI|2011|-4.25352174180244
MLI|2010|-9.37082497916747
MLI|2009|-5.40923592964098
MLI|2008|-9.31503755773015
MLI|2007|-5.9996237076332
MLI|2006|-2.66376814254956
MLI|2005|-5.89425017180063
MLI|2004|-6.31694830603582
MLI|2003|-4.84483163511996
MLI|2002|-3.21727063108563
MLI|2001|-7.52403238228262
MLI|2000|-7.24552346571525
MLI|1999|-6.18523088130449
MLI|1998|-5.3457892384856
MLI|1997|-5.22446619584807
MLI|1996|-6.96743484197164
MLI|1995|-8.41376338872914
MLT|2024|7.09956405757706
MLT|2023|6.5390947528711
MLT|2022|-2.8280685577445
MLT|2021|9.34478175130435
MLT|2020|16.0980919347887
MLT|2019|17.8499382404589
MLT|2018|13.3484109482087
MLT|2017|19.1577307077782
MLT|2016|-0.551812533447935
MLT|2015|2.65010210922408
MLT|2014|8.34224109375237
MLT|2013|2.50365414839338
MLT|2012|1.57359500524502
MLT|2011|-0.132890954159099
MLT|2010|-4.61361462818441
MLT|2009|-6.36032965460631
MLT|2008|-0.839063233305962
MLT|2007|-2.01354111543001
MLT|2006|-7.86241508941017
MLT|2005|-6.53614986794795
MLT|2004|-3.79516218183121
MLT|2003|-2.88428116145282
MLT|2002|2.38461506413218
MLT|2001|-3.67648415995638
MLT|2000|-11.9011101567861
MLT|1999|-3.26891416565002
MLT|1998|-5.80881797682119
MLT|1997|-5.98624311349507
MLT|1996|-11.0484047553771
MLT|1995|-10.2409322410242
MNG|2024|-10.4453984769033
MNG|2023|0.596631968292985
MNG|2022|-13.4342448059604
MNG|2021|-13.7928750935516
MNG|2020|-5.06732429872456
MNG|2019|-15.2163324376399
MNG|2018|-14.4368935873351
MNG|2017|-10.0640976839598
MNG|2016|-6.25748206242188
MNG|2015|-8.16234225533352
MNG|2014|-15.8208781709903
MNG|2013|-37.6076656283991
MNG|2012|-43.7712346792978
MNG|2011|-43.34551932851
MNG|2010|-12.3162160595433
MNG|2009|-7.45624740801022
MNG|2008|-12.2837567825614
MNG|2007|4.05637184446513
MNG|2006|10.900689191107
MNG|2005|3.46785355038079
MNG|2004|3.16276343681136
MNG|2003|-6.1849966690847
MNG|2002|-7.52987540545573
MNG|2001|-4.86593852642614
MNG|2000|-6.14547875845517
MNG|1999|-5.46521084754003
MNG|1998|-6.72334550775523
MNG|1997|5.7564595755319
MNG|1996|-2.74202764825275
MNG|1995|2.67875894679157
MWI|2024|-15.0807909745291
MWI|2023|-12.2970660597057
MWI|2022|-16.9658204173891
MWI|2021|-14.1060506823148
MWI|2020|-13.9233232374397
MWI|2019|-11.9532181402648
MWI|2018|-17.2587081882279
MWI|2017|-17.4208707671145
MWI|2016|-12.7134008077219
MWI|2015|-11.5453760878876
MWI|2014|-12.8223513014994
MWI|2013|-15.3915920767631
MWI|2012|-8.48798044395289
MWI|2011|-9.75872117783744
MWI|2010|-9.57007930375054
MWI|2009|-6.0337420383018
MWI|2008|-8.95428978540153
MWI|2007|-6.47983259735382
MWI|2006|-5.26911371178684
MWI|2005|-9.52389293471596
MWI|2004|-7.49180677650097
MWI|2003|-5.33174689192045
MWI|2002|-3.94494805532032
MWI|2001|-2.39994803963788
MWI|2000|-2.89662420047882
MWI|1999|-6.09583135502042
MWI|1998|-0.171765166275472
MWI|1997|-7.12655435902359
MWI|1996|-4.44111037598451
MWI|1995|-3.83729133204214
NER|2024|-6.08945443545421
NER|2023|-13.7627535229343
NER|2022|-16.0965828995126
NER|2021|-14.0537660366173
NER|2020|-13.3037025420106
NER|2019|-12.6596968655614
NER|2018|-12.694596458321
NER|2017|-11.2187529586869
NER|2016|-11.42691224561
NER|2015|-15.3473430526611
NER|2014|-12.0310951996372
NER|2013|-11.2529264462121
NER|2012|-10.8373796125037
NER|2011|-16.3335422488128
NER|2010|-14.4829041887518
NER|2009|-18.0270234730353
NER|2008|-8.96292471931381
NER|2007|-6.13680984428318
NER|2006|-6.60182023558473
NER|2005|-7.10956498131608
NER|2004|-6.15019981758
NER|2003|-6.45750654841095
NER|2002|-5.95095241784039
NER|2001|-3.77103577195078
NER|2000|-4.65677330266078
NER|1999|-5.40711498610087
NER|1998|-5.76469887056396
NER|1997|-5.80368330028339
NER|1996|-4.5218931665648
NER|1995|-6.5867461128755
NIC|2024|4.1511238055786
NIC|2023|8.2298831014672
NIC|2022|-2.93963886099354
NIC|2021|-2.75303205196493
NIC|2020|3.77325208673091
NIC|2019|5.93825181295118
NIC|2018|-1.79728223029998
NIC|2017|-7.1602180538079
NIC|2016|-8.48330631920504
NIC|2015|-9.87324597391166
NIC|2014|-8.02832297774323
NIC|2013|-12.5685284248506
NIC|2012|-11.7242497122842
NIC|2011|-11.9077223652027
NIC|2010|-8.87470374065858
NIC|2009|-8.45312867792372
NIC|2008|-17.0684421646058
NIC|2007|-16.2594506892154
NIC|2006|-13.0801722823838
NIC|2005|-12.3956621334031
NIC|2004|-11.8661827985183
NIC|2003|-13.2557258638297
NIC|2002|-15.0103547636833
NIC|2001|-15.3276907217401
NIC|2000|-18.3126344819719
NIC|1999|-19.1180597152813
NIC|1998|-14.8130429693637
NIC|1997|-19.1519607565273
NIC|1996|-19.1435615894481
NIC|1995|-17.4492145577676
NZL|2024|-4.62952800849338
NZL|2023|-6.14986296247427
NZL|2022|-8.7516189444306
NZL|2021|-5.64905496688554
NZL|2020|-1.08263837857087
NZL|2019|-2.82057766065118
NZL|2018|-4.16442592967999
NZL|2017|-2.92099841298629
NZL|2016|-2.15490580463572
NZL|2015|-2.61733984538523
NZL|2014|-3.08979706201678
NZL|2013|-3.05687316237005
NZL|2012|-3.90197677437136
NZL|2011|-2.86292030978892
NZL|2010|-2.33469330577729
NZL|2009|-2.47419947301186
NZL|2008|-7.69181610885173
NZL|2007|-6.79701754359096
NZL|2006|-7.06517341361543
NZL|2005|-6.99536794869389
NZL|2004|-4.50791009901216
NZL|2003|-2.40599179153862
NZL|2002|-2.09521936295547
NZL|2001|-0.776440240634347
NZL|2000|-3.30284871216651
NZL|1999|
NZL|1998|
NZL|1997|
NZL|1996|
NZL|1995|
PAK|2024|0.124893414067427
PAK|2023|-0.308630136387274
PAK|2022|-3.25858181478804
PAK|2021|-3.52439577565177
PAK|2020|-0.216650637871501
PAK|2019|-2.66677325730292
PAK|2018|-5.29556175645778
PAK|2017|-4.76985760466006
PAK|2016|-2.29279660651385
PAK|2015|-0.934446742353906
PAK|2014|-1.34787339235798
PAK|2013|-1.70727876868057
PAK|2012|-0.936399348037174
PAK|2011|-0.957124213324854
PAK|2010|-0.688324235118166
PAK|2009|-2.13167355660601
PAK|2008|-7.74194351471585
PAK|2007|-4.50796175781862
PAK|2006|-4.16812395772995
PAK|2005|-2.48346235681318
PAK|2004|-0.617928012719509
PAK|2003|3.17962013910419
PAK|2002|3.93573326208505
PAK|2001|1.93318034244488
PAK|2000|-0.0854401858342493
PAK|1999|-1.46092369568391
PAK|1998|-3.61461538001894
PAK|1997|-2.74152798261064
PAK|1996|-7.00574971079086
PAK|1995|-5.52270880088959
PAN|2024|0.65661826831948
PAN|2023|-3.19379683721352
PAN|2022|-0.361802808993905
PAN|2021|-1.21399867998869
PAN|2020|0.215312493541314
PAN|2019|-5.14448028522086
PAN|2018|-7.88419298601022
PAN|2017|-5.8224314491849
PAN|2016|-7.54284614640251
PAN|2015|-8.69390485131528
PAN|2014|-12.9838146887401
PAN|2013|-8.69806985044023
PAN|2012|-8.97959013521377
PAN|2011|-12.6581291367517
PAN|2010|-10.3251596675923
PAN|2009|-0.763910452207457
PAN|2008|-8.89223138089915
PAN|2007|-5.43158096330884
PAN|2006|-2.48020850686329
PAN|2005|-6.40102245039663
PAN|2004|-6.92308555260918
PAN|2003|-4.22833726958796
PAN|2002|-0.883534988020672
PAN|2001|-1.55881384647493
PAN|2000|-5.84047277996226
PAN|1999|-9.97538330616165
PAN|1998|-9.10381366758477
PAN|1997|-5.03735296138693
PAN|1996|-2.18102667057483
PAN|1995|-4.9154915141079
PER|2024|2.3885922878139
PER|2023|0.480962420777881
PER|2022|-4.08676202376084
PER|2021|-2.29896613499338
PER|2020|0.657151815147807
PER|2019|-0.727870000015781
PER|2018|-1.28150267165616
PER|2017|-1.11176847186391
PER|2016|-2.42132634833473
PER|2015|-4.77973128045252
PER|2014|-4.40483758703291
PER|2013|-4.85472915477104
PER|2012|-2.85658799241122
PER|2011|-1.96422212136988
PER|2010|-2.41611244249563
PER|2009|-0.598288729210878
PER|2008|-4.41112077807089
PER|2007|1.42931463476859
PER|2006|3.24050716695869
PER|2005|1.5088102611942
PER|2004|0.0288861085400799
PER|2003|-1.61504289543387
PER|2002|-2.02693936398419
PER|2001|-2.31175794610238
PER|2000|-2.98741137277728
PER|1999|-2.74952502384786
PER|1998|-6.01059688640088
PER|1997|-5.7922394566417
PER|1996|-6.59496815056511
PER|1995|-8.67435304434383
POL|2024|0.30454349270969
POL|2023|1.53683077845046
POL|2022|-2.27455866454271
POL|2021|-1.30156521580162
POL|2020|2.39835922164097
POL|2019|-0.272945793712772
POL|2018|-1.96597258830492
POL|2017|-1.18631971999704
POL|2016|-1.06875798055693
POL|2015|-1.3254755565429
POL|2014|-2.97288032663133
POL|2013|-1.98155143805472
POL|2012|-4.11182485634079
POL|2011|-5.11055687403888
POL|2010|-5.16657584018312
POL|2009|-3.94518857698649
POL|2008|-6.74648774312839
POL|2007|-6.68396289819493
POL|2006|-4.64906335604984
POL|2005|-3.30488692842897
POL|2004|-5.96912639653316
POL|2003|-2.50410381576022
POL|2002|-2.77624121851834
POL|2001|-3.09972932809545
POL|2000|-5.98021918224644
POL|1999|-7.31498200628172
POL|1998|-3.93707818430142
POL|1997|-3.59238073994115
POL|1996|-2.02968632371393
POL|1995|0.59787790958511
PRT|2024|2.53619853100595
PRT|2023|0.593927051268713
PRT|2022|-2.08477766426278
PRT|2021|-0.672210743652409
PRT|2020|-0.629832722737581
PRT|2019|0.765771121812588
PRT|2018|0.7276825303456
PRT|2017|1.56389644169824
PRT|2016|1.42555528145605
PRT|2015|0.508297093307308
PRT|2014|0.315317528197345
PRT|2013|1.53973827822347
PRT|2012|-1.52721549957903
PRT|2011|-6.11854777822696
PRT|2010|-10.2611634070617
PRT|2009|-10.3235445210728
PRT|2008|-11.859800223599
PRT|2007|-9.65792414363096
PRT|2006|-10.2302140524554
PRT|2005|-9.60021052870909
PRT|2004|-7.98339399989486
PRT|2003|-6.6669232574819
PRT|2002|-8.31755894208286
PRT|2001|-10.4344116184086
PRT|2000|-10.8233299998961
PRT|1999|-8.85368265057396
PRT|1998|-6.76039275351895
PRT|1997|-5.66728405930872
PRT|1996|-4.0005138112894
PRT|1995|-0.111582055664553
PRY|2024|-3.25034810488206
PRY|2023|0.284720362712866
PRY|2022|-6.45181312903723
PRY|2021|-0.608891037436505
PRY|2020|2.38698954154757
PRY|2019|-0.162746811813041
PRY|2018|0.23070706015291
PRY|2017|3.6769885100988
PRY|2016|4.58868258913127
PRY|2015|-0.217870478359167
PRY|2014|-0.786915039831661
PRY|2013|0.833944389778047
PRY|2012|-1.8854534498319
PRY|2011|-0.732894985105745
PRY|2010|-1.13361355099133
PRY|2009|1.77539259401098
PRY|2008|0.374841642070163
PRY|2007|4.36238494214342
PRY|2006|1.24447680615271
PRY|2005|-0.628692309199553
PRY|2004|-0.101927990310014
PRY|2003|0.221163990286845
PRY|2002|8.61307588678674
PRY|2001|-0.375729695210563
PRY|2000|-2.79049501871093
PRY|1999|1.56971889454463
PRY|1998|1.42468424398124
PRY|1997|-5.50597618386607
PRY|1996|-0.707053011808279
PRY|1995|-2.39891387766325
PSE|2024|-18.0999264452663
PSE|2023|-15.5371822753305
PSE|2022|-10.626522987378
PSE|2021|-9.81804738509631
PSE|2020|-12.251111498554
PSE|2019|-10.3854804313719
PSE|2018|-13.1500305467431
PSE|2017|-13.2065607876551
PSE|2016|-13.90776226662
PSE|2015|-13.8789175930847
PSE|2014|-13.5869104014544
PSE|2013|-14.7723926183375
PSE|2012|-14.917075141058
PSE|2011|-18.500705760576
PSE|2010|-13.4993932332553
PSE|2009|-14.1407042757884
PSE|2008|5.20627128726086
PSE|2007|-7.19650679252473
PSE|2006|-23.0633352516594
PSE|2005|-26.6372592440418
PSE|2004|-34.4972336341483
PSE|2003|-26.9797547641018
PSE|2002|-13.6551918587104
PSE|2001|-20.6776260427205
PSE|2000|-19.8583877091309
PSE|1999|-27.9029137526112
PSE|1998|-25.5251324573607
PSE|1997|-41.1603010798447
PSE|1996|-41.7761614265603
PSE|1995|-29.9652735469721
ROU|2024|-8.16757110224326
ROU|2023|-7.03377443891132
ROU|2022|-9.25302809964963
ROU|2021|-7.21432085371443
ROU|2020|-5.14044816549562
ROU|2019|-4.86977887140915
ROU|2018|-4.60748728741796
ROU|2017|-3.19415712159883
ROU|2016|-2.10324885883263
ROU|2015|-0.637491637323498
ROU|2014|-0.341464408053705
ROU|2013|-1.13746709997941
ROU|2012|-4.57804292376289
ROU|2011|-4.81588301986922
ROU|2010|-4.98543687917278
ROU|2009|-4.72925693261463
ROU|2008|-11.658522565437
ROU|2007|-13.7032326042104
ROU|2006|-10.6661036918405
ROU|2005|-8.67463205439941
ROU|2004|-8.5123232185601
ROU|2003|-5.72774106022585
ROU|2002|-3.31050332793727
ROU|2001|-5.51799372952363
ROU|2000|-3.63721875382544
ROU|1999|-3.60747182475184
ROU|1998|-6.99585947248816
ROU|1997|-5.91423004615668
ROU|1996|-6.96048631418109
ROU|1995|-4.73949323312222
SDN|2024|-4.65471960837971
SDN|2023|-5.19007706528547
SDN|2022|-8.59889945364703
SDN|2021|-7.65468962500371
SDN|2020|-21.6064794369516
SDN|2019|-14.7808388986177
SDN|2018|-14.4693934170139
SDN|2017|-11.1697054533751
SDN|2016|-9.88346111101847
SDN|2015|-10.5569345811594
SDN|2014|-7.1601361847383
SDN|2013|-13.5321488136858
SDN|2012|-16.6318777556219
SDN|2011|-4.82188496528231
SDN|2010|-2.92618988919934
SDN|2009|-9.54372816963053
SDN|2008|-5.54326957101499
SDN|2007|-6.05172200816878
SDN|2006|-14.3510830891701
SDN|2005|-7.02825381106123
SDN|2004|-3.07074148971241
SDN|2003|-4.39506852023541
SDN|2002|-5.36777365828637
SDN|2001|-3.32074310136626
SDN|2000|-4.22360581869545
SDN|1999|-4.03575038645252
SDN|1998|-8.50205479843779
SDN|1997|-7.08918356865189
SDN|1996|-9.1674698509357
SDN|1995|-3.61451082283543
SEN|2024|
SEN|2023|-19.7803402658787
SEN|2022|-19.9485520410487
SEN|2021|-12.0900482268387
SEN|2020|-10.8532305243561
SEN|2019|-8.10949609772061
SEN|2018|-9.58292425612144
SEN|2017|-7.28006040709527
SEN|2016|-4.178756111634
SEN|2015|-5.31619475400191
SEN|2014|-6.80294523804886
SEN|2013|-8.19227245767779
SEN|2012|-8.65191854670285
SEN|2011|-6.44529936745541
SEN|2010|-3.65650876220736
SEN|2009|-5.30915741099426
SEN|2008|-11.222076072763
SEN|2007|-9.37907093301321
SEN|2006|-7.36865431598262
SEN|2005|-6.14150322696352
SEN|2004|-5.0744758990416
SEN|2003|-4.98969389328597
SEN|2002|-4.54340089477442
SEN|2001|-3.77513794796373
SEN|2000|-5.54079842355363
SEN|1999|-4.85800602014769
SEN|1998|-3.80375176727342
SEN|1997|-3.05919124475018
SEN|1996|-3.06028361139742
SEN|1995|-3.86419721134813
SLB|2024|-4.18133473457478
SLB|2023|-11.8314939444528
SLB|2022|-14.8999907899023
SLB|2021|-5.01770966156316
SLB|2020|-1.63132884568903
SLB|2019|-9.51100860736619
SLB|2018|-2.95982088484313
SLB|2017|-4.27498589689084
SLB|2016|-3.53780145431414
SLB|2015|-2.75806023188152
SLB|2014|-3.71113892809321
SLB|2013|-2.99761288648898
SLB|2012|2.22663803763421
SLB|2011|-1.76447706076069
SLB|2010|-16.0506619217521
SLB|2009|-7.39710267104601
SLB|2008|-10.2527260927111
SLB|2007|-11.53055204475
SLB|2006|-6.83313528792249
SLB|2005|-16.3149014874914
SLB|2004|-4.04309489428343
SLB|2003|-9.55791509502594
SLB|2002|-19.5076486144732
SLB|2001|-15.8332825110055
SLB|2000|-9.75872166781304
SLB|1999|4.40043214690359
SLB|1998|1.77441432624841
SLB|1997|-7.19916830125425
SLB|1996|2.85567709426956
SLB|1995|1.77624714752846
SLE|2024|-14.1190349801252
SLE|2023|-7.86330353335447
SLE|2022|-6.3486336227146
SLE|2021|-7.29482310965872
SLE|2020|-5.83728154393524
SLE|2019|-7.78800790188033
SLE|2018|-9.25504556429235
SLE|2017|-11.8197447773241
SLE|2016|-4.83009013015939
SLE|2015|-14.7764569204395
SLE|2014|-6.15041708408739
SLE|2013|-9.82432065734399
SLE|2012|-19.7049574950917
SLE|2011|-39.3593386346764
SLE|2010|-13.7303367162602
SLE|2009|-8.27097097515223
SLE|2008|-5.42208122544718
SLE|2007|-4.40780618552025
SLE|2006|-2.91139372809153
SLE|2005|-4.12285133599241
SLE|2004|-4.42616819447044
SLE|2003|-3.86532771869266
SLE|2002|-3.78669132902158
SLE|2001|-5.82077902001999
SLE|2000|-17.658489136383
SLE|1999|-14.8361767452952
SLE|1998|-4.94309572568763
SLE|1997|-6.45379716642746
SLE|1996|-15.9818934226735
SLE|1995|-13.5594930752413
SLV|2024|-2.76497895911378
SLV|2023|-1.74191990334685
SLV|2022|-6.72643262454089
SLV|2021|-4.30553038660689
SLV|2020|1.11030429654712
SLV|2019|-0.421693578525018
SLV|2018|-3.30179306522223
SLV|2017|-1.85990733613606
SLV|2016|-2.27403286613894
SLV|2015|-3.2159293549397
SLV|2014|-5.37138698730115
SLV|2013|-6.90474689247509
SLV|2012|-5.79721503254672
SLV|2011|-5.48105199392229
SLV|2010|-2.88821622788294
SLV|2009|-1.77368032991474
SLV|2008|-8.51825968802828
SLV|2007|-7.15129248901495
SLV|2006|-4.78478289538241
SLV|2005|-4.22907878622942
SLV|2004|-4.67674940955736
SLV|2003|-5.30205130807915
SLV|2002|-3.19917807931234
SLV|2001|-1.22368889754147
SLV|2000|-3.65297107423069
SLV|1999|-2.12066485546114
SLV|1998|-0.829238100118753
SLV|1997|-0.956383843468498
SLV|1996|-1.76340996059416
SLV|1995|-2.93184061861952
STP|2024|-6.31683649881247
STP|2023|-11.173462712563
STP|2022|-18.1914832537574
STP|2021|-18.1632158527971
STP|2020|-12.64674361519
STP|2019|-21.799320591176
STP|2018|-19.5798259962622
STP|2017|-22.7156290253769
STP|2016|-21.0403152023302
STP|2015|-26.4207009685278
STP|2014|-35.4587784381715
STP|2013|-30.4299465368537
STP|2012|-43.1048517269594
STP|2011|-46.7031436146432
STP|2010|-46.0873607998782
STP|2009|-39.2591791041684
STP|2008|-49.7318439586792
STP|2007|-43.1433732431771
STP|2006|-40.3849806309735
STP|2005|-26.5288051595619
STP|2004|-32.3272461423146
STP|2003|-27.7539600682048
STP|2002|-31.2249951011705
STP|2001|-35.5295840568537
STP|2000|-26.3530521883155
STP|1999|-22.359817347003
STP|1998|-14.5005148243491
STP|1997|-6.853428204033
STP|1996|
STP|1995|
SVK|2024|-4.61427189349135
SVK|2023|-3.01849841620298
SVK|2022|-9.60893340616344
SVK|2021|-4.79283646505897
SVK|2020|-0.437071238574067
SVK|2019|-3.51259174873162
SVK|2018|-1.59262375291933
SVK|2017|-1.71807692688753
SVK|2016|-1.41742583384371
SVK|2015|-2.05103816352739
SVK|2014|1.77620820872981
SVK|2013|2.91051144201471
SVK|2012|0.938943103720464
SVK|2011|-4.92376770602967
SVK|2010|-4.6203044518302
SVK|2009|-3.38105508330994
SVK|2008|-6.48535562964174
SVK|2007|-6.01532811494231
SVK|2006|-9.54715887745851
SVK|2005|-10.497236297843
SVK|2004|-10.146838584551
SVK|2003|-0.835083159855026
SVK|2002|-7.89305502420075
SVK|2001|-8.15075424975695
SVK|2000|-3.36585003127904
SVK|1999|-5.54972617503958
SVK|1998|-9.28104946495994
SVK|1997|-8.90403427725706
SVK|1996|-9.56063606144349
SVK|1995|1.9208133589006
SVN|2024|4.55086826535468
SVN|2023|4.46558757096218
SVN|2022|-1.03068913156479
SVN|2021|3.36779729636638
SVN|2020|7.67395367082141
SVN|2019|6.45290585431634
SVN|2018|6.52066143026875
SVN|2017|6.82058845826205
SVN|2016|5.29223433710434
SVN|2015|4.11844607611057
SVN|2014|5.32786784003453
SVN|2013|3.51650748197892
SVN|2012|1.40334115378876
SVN|2011|-0.772202643426759
SVN|2010|-0.686229865264751
SVN|2009|-1.02930810163582
SVN|2008|-5.30803970003449
SVN|2007|-4.20761971530098
SVN|2006|-1.77091456240672
SVN|2005|-1.89301545547915
SVN|2004|-2.61296856216983
SVN|2003|-0.734658635827973
SVN|2002|1.05020145982641
SVN|2001|0.151435477403197
SVN|2000|-2.71588283528864
SVN|1999|-3.08319417422173
SVN|1998|-0.535844572045627
SVN|1997|0.243644981984294
SVN|1996|0.257560310756861
SVN|1995|-0.35053362750793
SWZ|2024|2.08266309517439
SWZ|2023|2.15139436389029
SWZ|2022|-2.96992116038182
SWZ|2021|2.60694672482631
SWZ|2020|6.55291656984155
SWZ|2019|3.81510661336771
SWZ|2018|1.30781570062784
SWZ|2017|6.11293651555308
SWZ|2016|7.99024652712619
SWZ|2015|13.6462188835414
SWZ|2014|11.9504856315641
SWZ|2013|10.9113844873232
SWZ|2012|5.05366904415604
SWZ|2011|-5.9649333225146
SWZ|2010|-8.90472208675336
SWZ|2009|-11.7528556394377
SWZ|2008|-7.14591112347182
SWZ|2007|-1.93276556706589
SWZ|2006|-6.11526332672519
SWZ|2005|-3.31336100189476
SWZ|2004|2.63067140122666
SWZ|2003|4.15889604093632
SWZ|2002|2.38216911954966
SWZ|2001|0.598910535464894
SWZ|2000|-2.70238391314616
SWZ|1999|-2.12921733088375
SWZ|1998|-5.91886464673934
SWZ|1997|-0.159647506239686
SWZ|1996|-3.24211594984
SWZ|1995|-1.74925944187271
SYC|2024|-7.45776668599762
SYC|2023|-7.12307582064592
SYC|2022|-7.08279204871694
SYC|2021|-10.7699576448461
SYC|2020|-12.5301883307748
SYC|2019|-2.842387489846
SYC|2018|-2.34133369670355
SYC|2017|-2.20368065340164
SYC|2016|-2.61384777681388
SYC|2015|-17.8847188907867
SYC|2014|-22.3701856914691
SYC|2013|-11.8972428115469
SYC|2012|-14.8074270420074
SYC|2011|-28.4521363904849
SYC|2010|-21.8405252938197
SYC|2009|-22.2660045596962
SYC|2008|-26.8423661578652
SYC|2007|-18.0086154122811
SYC|2006|-12.3693581655909
SYC|2005|-17.8003425507562
SYC|2004|-6.75447656002783
SYC|2003|-1.2468218160317
SYC|2002|-13.645650344015
SYC|2001|-23.1184684109926
SYC|2000|-6.56104546972391
SYC|1999|-17.6156832289782
SYC|1998|-16.4185652854264
SYC|1997|-11.0348966495093
SYC|1996|-9.79337791202402
SYC|1995|0.261751917899548
TGO|2024|
TGO|2023|
TGO|2022|
TGO|2021|
TGO|2020|-0.277018884474411
TGO|2019|-0.792850409861065
TGO|2018|-2.62976116468944
TGO|2017|-1.51302452827798
TGO|2016|-7.19180652142337
TGO|2015|-8.01021600244542
TGO|2014|-7.17108249416322
TGO|2013|-9.43944638209534
TGO|2012|-5.43302431064873
TGO|2011|-5.57134555457932
TGO|2010|-4.21167785064637
TGO|2009|-3.75655470430214
TGO|2008|-4.86721309193415
TGO|2007|-5.74598605436746
TGO|2006|-5.31324873611491
TGO|2005|-6.33089706237215
TGO|2004|-6.49399507558124
TGO|2003|-5.43138096608201
TGO|2002|-5.81784745652387
TGO|2001|-8.08590195490082
TGO|2000|-6.64451964783898
TGO|1999|-5.71132962319834
TGO|1998|-6.25067363890598
TGO|1997|-5.52268507704884
TGO|1996|-7.43684829762115
TGO|1995|-6.59580508528401
TJK|2024|6.42365269759176
TJK|2023|4.76980054377007
TJK|2022|15.2573634253921
TJK|2021|8.22937866606437
TJK|2020|4.34918092627649
TJK|2019|-2.23224918510585
TJK|2018|-4.88966506186354
TJK|2017|2.10935261893798
TJK|2016|-5.23235146296922
TJK|2015|-5.76773865149508
TJK|2014|-3.47271227917374
TJK|2013|-10.4728821493758
TJK|2012|-8.92695486705107
TJK|2011|-6.33655867344341
TJK|2010|-10.2987565843148
TJK|2009|-14.40853186566
TJK|2008|-20.5138549086729
TJK|2007|-32.096259393905
TJK|2006|-13.1584118273093
TJK|2005|-12.809877638523
TJK|2004|-2.74745860241597
TJK|2003|-0.306284579701348
TJK|2002|-1.23935164268065
TJK|2001|
TJK|2000|
TJK|1999|
TJK|1998|
TJK|1997|
TJK|1996|
TJK|1995|
TON|2024|-5.28228177617398
TON|2023|-5.08732404392182
TON|2022|-4.98622454176692
TON|2021|-6.2356582846921
TON|2020|-5.61800945856786
TON|2019|-3.73768804085582
TON|2018|-6.95287689868444
TON|2017|-7.16886529463138
TON|2016|-7.4710560000891
TON|2015|-10.9245837700646
TON|2014|-6.26556410417194
TON|2013|-9.47350598315127
TON|2012|-14.8200258513003
TON|2011|-20.2517397724187
TON|2010|-23.83210956232
TON|2009|-30.038855601242
TON|2008|-18.207471277767
TON|2007|-16.4953983377192
TON|2006|-8.10879558988645
TON|2005|-9.29333405709877
TON|2004|-3.26824811194436
TON|2003|-6.34024407217629
TON|2002|-3.46620189323188
TON|2001|-7.26085680790221
TON|2000|
TON|1999|
TON|1998|
TON|1997|
TON|1996|
TON|1995|
TUN|2024|-1.60260258927968
TUN|2023|-2.33716071115365
TUN|2022|-8.83429553808935
TUN|2021|-5.88456562547467
TUN|2020|-6.01234016088557
TUN|2019|-8.04912453318916
TUN|2018|-10.7946228980082
TUN|2017|-10.0143611259515
TUN|2016|-8.52887305480806
TUN|2015|-8.57094815049073
TUN|2014|-8.87794509825976
TUN|2013|-7.96677847902678
TUN|2012|-7.86572520912914
TUN|2011|-7.03556585573608
TUN|2010|-4.55447131361941
TUN|2009|-2.83909252656908
TUN|2008|-3.81468880111158
TUN|2007|-2.35618464912072
TUN|2006|-1.80172304518295
TUN|2005|-0.927371928635411
TUN|2004|-1.41663593407068
TUN|2003|-2.66077074311871
TUN|2002|-3.22389381333493
TUN|2001|-3.80893714007523
TUN|2000|-3.82558496867723
TUN|1999|-1.92535218512776
TUN|1998|-3.09737186587453
TUN|1997|-2.86792629545458
TUN|1996|-2.43885725476728
TUN|1995|-4.2925749806772
TUR|2024|-0.958485187243091
TUR|2023|-3.66451360136676
TUR|2022|-5.03921035996332
TUR|2021|-0.841490012048298
TUR|2020|-4.22884480277712
TUR|2019|1.93503114755598
TUR|2018|-1.85296766104815
TUR|2017|-4.06783613710293
TUR|2016|-2.54530792537505
TUR|2015|-2.46712716353959
TUR|2014|-3.40767483615583
TUR|2013|-5.12686124176872
TUR|2012|-4.72096418758118
TUR|2011|-8.81351105932507
TUR|2010|-5.70254261669491
TUR|2009|-1.73697758122388
TUR|2008|-5.0844969449165
TUR|2007|-5.39177822047968
TUR|2006|-5.5679426761279
TUR|2005|-4.12736838327371
TUR|2004|-3.46160310805252
TUR|2003|-2.39510781690365
TUR|2002|-0.259990521546323
TUR|2001|1.85959025093731
TUR|2000|-3.61057524589502
TUR|1999|-0.360379399136068
TUR|1998|0.724544822196581
TUR|1997|-0.999933462545818
TUR|1996|-0.973371226633304
TUR|1995|-0.99616690058046
TUV|2024|
TUV|2023|40.0273112804595
TUV|2022|-0.271496007405071
TUV|2021|28.2644481240152
TUV|2020|16.175940920155
TUV|2019|-22.4210470726777
TUV|2018|60.9075410272211
TUV|2017|2.07231989129787
TUV|2016|29.8763555684922
TUV|2015|-33.650855840412
TUV|2014|-0.481358144883788
TUV|2013|2.83508546925474
TUV|2012|16.5198797492105
TUV|2011|-60.1588561372752
TUV|2010|-43.2184886122592
TUV|2009|-60.7028687959191
TUV|2008|-11.7348781633598
TUV|2007|-15.2873932470538
TUV|2006|26.9794542429323
TUV|2005|-18.7240022967409
TUV|2004|-30.8619475703454
TUV|2003|-32.1132837366209
TUV|2002|0.150200355708208
TUV|2001|-55.2183117560852
TUV|2000|
TUV|1999|
TUV|1998|
TUV|1997|
TUV|1996|
TUV|1995|
TZA|2024|-3.00342879227062
TZA|2023|-3.74610299942784
TZA|2022|-7.2373333204952
TZA|2021|-3.3603589034405
TZA|2020|-2.20760897715159
TZA|2019|-2.19612703390998
TZA|2018|-4.05016373285835
TZA|2017|-2.77322833378381
TZA|2016|-2.44600098634937
TZA|2015|-5.52237840763772
TZA|2014|-9.97566998652383
TZA|2013|-10.92678991973
TZA|2012|-9.49381708629511
TZA|2011|-12.6408334198025
TZA|2010|-6.90590514874114
TZA|2009|-6.15605248067037
TZA|2008|-9.22106341671595
TZA|2007|-7.84401666779704
TZA|2006|-5.91870284632789
TZA|2005|-5.93931026684705
TZA|2004|-2.89917810279357
TZA|2003|-1.14522022259737
TZA|2002|-0.324018475277026
TZA|2001|-4.15575639482293
TZA|2000|-3.20303174427397
TZA|1999|-6.11682325920144
TZA|1998|-5.78640777187492
TZA|1997|-3.90935028953365
TZA|1996|-4.37556391827358
TZA|1995|-7.72805036797611
UGA|2024|-8.4495415991114
UGA|2023|-7.43279149697522
UGA|2022|-8.91897823001288
UGA|2021|-8.8944875833578
UGA|2020|-9.56958764500258
UGA|2019|-7.44419073613667
UGA|2018|-6.32983605256251
UGA|2017|-4.88278660173815
UGA|2016|-2.85393787294637
UGA|2015|-5.1602872378994
UGA|2014|-6.64160843323991
UGA|2013|-6.05719389968621
UGA|2012|-6.0631263873337
UGA|2011|-7.48878445953833
UGA|2010|-6.0351181457015
UGA|2009|-4.1708492322474
UGA|2008|-8.47510327903427
UGA|2007|-4.72875221684934
UGA|2006|-3.18903604186135
UGA|2005|0.579537398767585
UGA|2004|-0.0210973345748702
UGA|2003|-0.581756161515947
UGA|2002|-2.46011695217403
UGA|2001|-5.23214599458245
UGA|2000|-5.79340706801523
UGA|1999|-4.88783709351708
UGA|1998|-5.52316129222945
UGA|1997|-5.03610167506473
UGA|1996|-3.49899932849718
UGA|1995|-4.8905291793045
URY|2024|-0.756969656971073
URY|2023|-2.95412894360151
URY|2022|-3.51743431791159
URY|2021|-2.43351228681367
URY|2020|-0.641294487904138
URY|2019|1.29076830015762
URY|2018|-0.459786698279111
URY|2017|0.011326168182089
URY|2016|0.825062149663385
URY|2015|-0.255015059040964
URY|2014|-2.98942522248202
URY|2013|-3.28720935568052
URY|2012|-3.7550569524485
URY|2011|-2.61132861090732
URY|2010|-1.74215679383919
URY|2009|-1.16571403141018
URY|2008|-5.55595054569104
URY|2007|-0.926356077597871
URY|2006|-1.9850690235445
URY|2005|0.243497121353953
URY|2004|0.0228310712848396
URY|2003|-0.724417111042172
URY|2002|2.80710265957684
URY|2001|-2.38113794693639
URY|2000|-2.48133850696421
URY|1999|-2.11641577716128
URY|1998|-1.87308798948415
URY|1997|-1.19901179230843
URY|1996|-1.1376787138155
URY|1995|-1.10116960243742
USA|2024|-4.09115799081665
USA|2023|-3.3489507242629
USA|2022|-3.7320030916597
USA|2021|-3.60455110914793
USA|2020|-2.75842923421685
USA|2019|-1.87698392691322
USA|2018|-2.03056023581131
USA|2017|-1.77880983894536
USA|2016|-2.02080700931719
USA|2015|-2.13599122252893
USA|2014|-1.99192555169661
USA|2013|-1.90651646026408
USA|2012|-2.4320888988967
USA|2011|-2.78205420452095
USA|2010|-2.74500495748181
USA|2009|-2.50957534593534
USA|2008|-4.58066568259067
USA|2007|-4.98394802126925
USA|2006|-5.81369602716006
USA|2005|-5.64194252146049
USA|2004|-5.09880499584356
USA|2003|-4.45597894635773
USA|2002|-4.07172296220332
USA|2001|-3.58135081042407
USA|2000|-3.77979528145288
USA|1999|-2.85236313919012
USA|1998|-2.37273907218914
USA|1997|-1.64061377884972
USA|1996|-1.54496736206885
USA|1995|-1.48644935848023
VCT|2024|-16.6849459746644
VCT|2023|-17.7791847090195
VCT|2022|-20.0993766685012
VCT|2021|-23.2111023451403
VCT|2020|-15.8942170558575
VCT|2019|-2.38815343936867
VCT|2018|-10.3037962472728
VCT|2017|-11.8946710104421
VCT|2016|-13.083380397797
VCT|2015|-15.5812824807682
VCT|2014|-25.2076799475114
VCT|2013|-24.7266517767588
VCT|2012|-25.3027530049806
VCT|2011|-22.332258031627
VCT|2010|-26.3254736856599
VCT|2009|-25.6757501478007
VCT|2008|-31.3887476104186
VCT|2007|-21.3718200786995
VCT|2006|-16.4580193516627
VCT|2005|-14.032989246926
VCT|2004|-13.3113071409128
VCT|2003|-8.40936238282576
VCT|2002|-3.64768298215969
VCT|2001|-5.53237309873477
VCT|2000|-6.88016747198498
VCT|1999|-17.3621248601816
VCT|1998|-24.7013689939233
VCT|1997|-23.1719525442501
VCT|1996|-9.93832540054969
VCT|1995|-12.7212207871358
VNM|2024|6.33496605552948
VNM|2023|5.94575853346696
VNM|2022|0.339101746979362
VNM|2021|-1.26284279203588
VNM|2020|4.34486906553373
VNM|2019|3.91824395534242
VNM|2018|1.90236367538642
VNM|2017|-0.586095207209378
VNM|2016|0.243099852637275
VNM|2015|-0.853052854546214
VNM|2014|4.00897026449707
VNM|2013|3.62409015316054
VNM|2012|4.82078231422777
VNM|2011|0.136736251193688
VNM|2010|-2.90486815229253
VNM|2009|-6.23310024019381
VNM|2008|-10.9179529896098
VNM|2007|-8.98165936412439
VNM|2006|-0.246704373698266
VNM|2005|-0.971989162897
VNM|2004|-2.10663701040253
VNM|2003|-4.88211706972335
VNM|2002|-1.72255927072095
VNM|2001|2.08657136826562
VNM|2000|3.54799694298148
VNM|1999|4.10338164918913
VNM|1998|-3.94713600744563
VNM|1997|-5.69221074168667
VNM|1996|-8.19224337661192
VNM|1995|
VUT|2024|
VUT|2023|
VUT|2022|-11.0631077358069
VUT|2021|-6.89789620099998
VUT|2020|-5.68678771450503
VUT|2019|6.90413979627201
VUT|2018|2.8620287508492
VUT|2017|-7.09262183131197
VUT|2016|-7.75456020639786
VUT|2015|-13.4017212958754
VUT|2014|0.481689706354945
VUT|2013|-0.596870701197757
VUT|2012|-9.17502386187912
VUT|2011|-7.91488480979288
VUT|2010|-6.28849949641009
VUT|2009|1.73468872565137
VUT|2008|-23.9660923505511
VUT|2007|-6.66442097163022
VUT|2006|-6.85825815927699
VUT|2005|-8.62045532228855
VUT|2004|-6.14777943367831
VUT|2003|-7.04462338564548
VUT|2002|-6.49555151242909
VUT|2001|0.705178324233457
VUT|2000|1.83612901398448
VUT|1999|-4.87888029034714
VUT|1998|2.19507065890242
VUT|1997|-7.09080001155568
VUT|1996|-10.3070624919748
VUT|1995|-7.3186574586249
ZAF|2024|-0.642799797075048
ZAF|2023|-1.10356312207881
ZAF|2022|-0.29618259812743
ZAF|2021|3.77241369345008
ZAF|2020|2.00352275153333
ZAF|2019|-2.61999067483039
ZAF|2018|-3.00051939426576
ZAF|2017|-2.37436753188649
ZAF|2016|-2.63361451678797
ZAF|2015|-4.31028688643788
ZAF|2014|-4.81243259488481
ZAF|2013|-5.33837274756909
ZAF|2012|-4.68373643403846
ZAF|2011|-2.01967628513274
ZAF|2010|-1.29901805615596
ZAF|2009|-2.38458187361532
ZAF|2008|-5.18618108467679
ZAF|2007|-4.86189160706926
ZAF|2006|-4.00012427594728
ZAF|2005|-2.7747758989594
ZAF|2004|-2.50726120703613
ZAF|2003|-0.782449992267882
ZAF|2002|0.781937464700473
ZAF|2001|0.253001084795547
ZAF|2000|-0.125570459653346
ZAF|1999|-0.445657419944882
ZAF|1998|-1.43749682421619
ZAF|1997|-1.31813387872595
ZAF|1996|-1.0280828308777
ZAF|1995|-1.45179160612888
ZMB|2024|-4.41103708042777
ZMB|2023|-3.03751016927581
ZMB|2022|3.74704409782872
ZMB|2021|11.9003513535048
ZMB|2020|11.790957110182
ZMB|2019|0.603690808802682
ZMB|2018|-1.30116677554112
ZMB|2017|-1.68127057617849
ZMB|2016|-4.55168827542136
ZMB|2015|-3.61227207947561
ZMB|2014|-1.4270939600475
ZMB|2013|-0.575955750525117
ZMB|2012|5.37898486156031
ZMB|2011|4.65823655766585
ZMB|2010|7.52549147652086
ZMB|2009|5.95342818479561
ZMB|2008|-3.33057905300122
ZMB|2007|-1.23802039926344
ZMB|2006|4.64474506229629
ZMB|2005|-2.78498414861087
ZMB|2004|-7.14878830806073
ZMB|2003|-13.5299667044381
ZMB|2002|-15.8142108448002
ZMB|2001|-18.0007855963506
ZMB|2000|-18.3980639927089
ZMB|1999|-11.3504014036785
ZMB|1998|-16.1232788984795
ZMB|1997|-4.22932371041795
ZMB|1996|
ZMB|1995|
```

Export growth (NE.EXP.GNFS.KD.ZG), countries in any top-10:

```
ALB|2024|0.10972760496233
ALB|2023|8.5541025992228
ALB|2022|17.0424879813874
ALB|2021|52.0973691827291
ALB|2020|-27.7255430085865
ALB|2019|2.4800752980137
ALB|2018|4.46629089537305
ALB|2017|12.9646313708102
ALB|2016|7.57276906101264
ALB|2015|-2.25254023391722
ALB|2014|-0.169636687451657
ALB|2013|1.58899617671256
ALB|2012|0.293588275390633
ALB|2011|6.67409512981436
ALB|2010|19.1935791437219
ALB|2009|4.71153337805501
ALB|2008|-4.62556706108955
ALB|2007|19.1122012763883
ALB|2006|16.9274273635671
ALB|2005|24.2668564177305
ALB|2004|18.4838664060318
ALB|2003|11.7732511279745
ALB|2002|3.5523666753469
ALB|2001|15.4561613554149
ALB|2000|38.8812984839359
ALB|1999|73.0967957895076
ALB|1998|33.833480981746
ALB|1997|-18.2745043507087
ALB|1996|15.5828531261344
ALB|1995|
ARM|2024|27.5999999999998
ARM|2023|32.3
ARM|2022|65.3000000000004
ARM|2021|18.2000000000001
ARM|2020|-33.9000000000001
ARM|2019|18.6
ARM|2018|5.00000000096964
ARM|2017|19.2999999980046
ARM|2016|21.3000000043358
ARM|2015|4.8999999940829
ARM|2014|6.40000000350811
ARM|2013|8.60000000000001
ARM|2012|9.13557735883434
ARM|2011|14.8982766263115
ARM|2010|26.4999699824954
ARM|2009|-10.4356553552406
ARM|2008|-13.079985463436
ARM|2007|-3.50822984919257
ARM|2006|-7.33908322521903
ARM|2005|16.2876538336234
ARM|2004|-2.50452689526465
ARM|2003|30.5554346606889
ARM|2002|34.4195713617779
ARM|2001|27.2630374539333
ARM|2000|18.7594821214409
ARM|1999|13.3430389118967
ARM|1998|-0.0701051618937925
ARM|1997|-6.88011702213127
ARM|1996|7.85805418643766
ARM|1995|-48.1757572334714
AZE|2024|
AZE|2023|
AZE|2022|
AZE|2021|
AZE|2020|
AZE|2019|
AZE|2018|
AZE|2017|
AZE|2016|
AZE|2015|
AZE|2014|-1.09729714940593
AZE|2013|1.49999981202413
AZE|2012|2.19999969347569
AZE|2011|3.59495493787011
AZE|2010|24.1995014126276
AZE|2009|8.13317374157107
AZE|2008|7.79590364620421
AZE|2007|47.5371128097792
AZE|2006|34.3114884924763
AZE|2005|48.9433277988705
AZE|2004|11.8083786252285
AZE|2003|0.768622944977565
AZE|2002|10.4660312885481
AZE|2001|27.0504404391746
AZE|2000|22.9850355296886
AZE|1999|13.4554315137672
AZE|1998|14.8169484985588
AZE|1997|29.1971110813134
AZE|1996|20.3468982894763
AZE|1995|-28.7995541862216
COD|2024|18.0147361061034
COD|2023|19.5715683393301
COD|2022|24.8894920278632
COD|2021|4.95738210046785
COD|2020|11.360843790051
COD|2019|-8.27939936085312
COD|2018|16.186608234815
COD|2017|-3.36442001501315
COD|2016|19.6503788435075
COD|2015|-3.13663275487193
COD|2014|5.86940745221331
COD|2013|26.6629287533457
COD|2012|0.137124617742785
COD|2011|12.7394608168468
COD|2010|39.9261165938757
COD|2009|-0.499732360286714
COD|2008|11.1255139330902
COD|2007|74.0075668096557
COD|2006|-9.40124087338087
COD|2005|12.9983583798142
COD|2004|2.73960378376216
COD|2003|14.7450337899416
COD|2002|82.4738415394044
COD|2001|-19.4945848331552
COD|2000|-3.62610661925248
COD|1999|49.4880599982203
COD|1998|24.1525457600731
COD|1997|-22.1122132044533
COD|1996|15.3999965334771
COD|1995|20.3999961760256
EGY|2024|-10.6156716417911
EGY|2023|31.3725490196078
EGY|2022|57.3437161916134
EGY|2021|-13.846440547507
EGY|2020|-23.6591264739412
EGY|2019|-2.68586460412141
EGY|2018|31.5904536391941
EGY|2017|86.0432980152476
EGY|2016|-15.0293542006107
EGY|2015|-0.0391236333733929
EGY|2014|-10.9407665492705
EGY|2013|4.51565913926026
EGY|2012|-2.29885057711766
EGY|2011|1.24688279846295
EGY|2010|-2.9838709670917
EGY|2009|-14.5122371603316
EGY|2008|28.7616511276764
EGY|2007|23.2848232898636
EGY|2006|21.2605042030361
EGY|2005|20.2020201780136
EGY|2004|25.3164557076119
EGY|2003|13.8328530350642
EGY|2002|4.9735990162723
EGY|2001|3.29067645661083
EGY|2000|7.02899936630705
EGY|1999|9.16142559038131
EGY|1998|-2.65306119518721
EGY|1997|-0.946987595180246
EGY|1996|1.78030281177558
EGY|1995|11.2906352338932
ERI|2024|
ERI|2023|
ERI|2022|
ERI|2021|
ERI|2020|
ERI|2019|
ERI|2018|
ERI|2017|
ERI|2016|
ERI|2015|
ERI|2014|
ERI|2013|
ERI|2012|
ERI|2011|575.740456101944
ERI|2010|17.4961090509831
ERI|2009|36.2135806110495
ERI|2008|-21.3730501727156
ERI|2007|-13.1299581777205
ERI|2006|15.0985733002017
ERI|2005|-1.03001790662685
ERI|2004|10.3274917020575
ERI|2003|-25.2541382030274
ERI|2002|8.72608017571036
ERI|2001|16.1974819312292
ERI|2000|1.30169273210645
ERI|1999|-39.4760304697726
ERI|1998|-40.0178575863363
ERI|1997|3.43553837593835
ERI|1996|58.5358732865561
ERI|1995|-16.442379086426
GIN|2024|4.49999999997948
GIN|2023|8.79999999992008
GIN|2022|-5.33052592968802
GIN|2021|30.3782549950307
GIN|2020|53.1723795946915
GIN|2019|-1.90319742549462
GIN|2018|-0.349235411879064
GIN|2017|78.8337585498412
GIN|2016|38.2666305377035
GIN|2015|-9.11866452618514
GIN|2014|6.60606336003046
GIN|2013|-12.4962469613978
GIN|2012|2.95438164047361
GIN|2011|-0.944682028493688
GIN|2010|5.92720310838698
GIN|2009|5.63404586053568
GIN|2008|-10.8538326169059
GIN|2007|29.9079037769765
GIN|2006|
GIN|2005|
GIN|2004|
GIN|2003|
GIN|2002|
GIN|2001|
GIN|2000|
GIN|1999|
GIN|1998|
GIN|1997|
GIN|1996|
GIN|1995|
HTI|2024|-31.031503061426
HTI|2023|-9.62358033781824
HTI|2022|2.38124797516792
HTI|2021|1.3843986222283
HTI|2020|-24.4142503579239
HTI|2019|-2.13167877007969
HTI|2018|-0.118930657202341
HTI|2017|0.533251464011101
HTI|2016|-5.58841783860962
HTI|2015|0.149144044821654
HTI|2014|5.74629363853212
HTI|2013|5.63618154642127
HTI|2012|-1.19271640394314
HTI|2011|130.167225215514
HTI|2010|-18.0767246737892
HTI|2009|9.07077874100644
HTI|2008|7.1338775670702
HTI|2007|104.788235801354
HTI|2006|-27.2111494144602
HTI|2005|2.65514666678548
HTI|2004|-10.5264303562937
HTI|2003|108.572259716922
HTI|2002|-4.14655903750794
HTI|2001|-1.82729813672222
HTI|2000|-68.8495904867903
HTI|1999|16.4844390049258
HTI|1998|23.2763133414043
HTI|1997|14.2772472422787
HTI|1996|27.3001517195522
HTI|1995|35.1681930508263
KHM|2024|14.4415893114104
KHM|2023|-0.367779562977617
KHM|2022|21.3394679976063
KHM|2021|6.1422568614574
KHM|2020|-12.2130815606546
KHM|2019|12.3444528821985
KHM|2018|6.8929419329597
KHM|2017|6.88352792108134
KHM|2016|8.70586418490906
KHM|2015|8.62482697495832
KHM|2014|11.0573051807198
KHM|2013|14.6470306416617
KHM|2012|14.8187951009155
KHM|2011|19.1180870324018
KHM|2010|19.9833887273962
KHM|2009|-7.96453717563855
KHM|2008|15.7605419629893
KHM|2007|11.3261389205511
KHM|2006|19.3127329675137
KHM|2005|18.7885882576693
KHM|2004|30.1726609769893
KHM|2003|9.77634053259983
KHM|2002|13.7060263128346
KHM|2001|17.846896828423
KHM|2000|30.2955021712609
KHM|1999|49.5754280358522
KHM|1998|-2.9605339461616
KHM|1997|36.1049269348735
KHM|1996|-17.4676942700847
KHM|1995|43.7648326036618
LBN|2024|-9.70000270384834
LBN|2023|-1.12999339148837
LBN|2022|0.299990552060507
LBN|2021|13.0836594164967
LBN|2020|-53.7436260462892
LBN|2019|-0.907659375494234
LBN|2018|-4.6857088305039
LBN|2017|3.92332267520659
LBN|2016|-1.42303373248494
LBN|2015|9.92328210940869
LBN|2014|-7.05963344822764
LBN|2013|3.38754830927486
LBN|2012|-14.914913538806
LBN|2011|2.60592868914824
LBN|2010|9.86471105204095
LBN|2009|9.61183387551962
LBN|2008|8.24517148633552
LBN|2007|11.6435811185089
LBN|2006|-3.27619024440548
LBN|2005|4.69976797545732
LBN|2004|24.0278265352652
LBN|2003|7.09999999767554
LBN|2002|12.5000000054253
LBN|2001|16.7999999993917
LBN|2000|1.60000000013392
LBN|1999|5.40000000076543
LBN|1998|5.09999999942801
LBN|1997|27.0679253494516
LBN|1996|36.0561259877835
LBN|1995|48.9392462443068
LBY|2024|-6.90267922782975
LBY|2023|7.10175118780711
LBY|2022|-19.9494100763124
LBY|2021|126.096490412832
LBY|2020|-66.3359320343469
LBY|2019|4.69948058306851
LBY|2018|26.0286784105916
LBY|2017|132.632341827378
LBY|2016|-5.93451564585347
LBY|2015|-2.11034370864505
LBY|2014|-53.791726740934
LBY|2013|-26.2596610492482
LBY|2012|211.505808728935
LBY|2011|-71.376986244933
LBY|2010|310.214442821417
LBY|2009|-4.76536592485532
LBY|2008|-10.8613825930548
LBY|2007|10.416655524885
LBY|2006|21.3142662095021
LBY|2005|7.73352483042488
LBY|2004|-9.86813700051894
LBY|2003|
LBY|2002|
LBY|2001|
LBY|2000|
LBY|1999|
LBY|1998|
LBY|1997|
LBY|1996|
LBY|1995|
LSO|2024|26.449021459682
LSO|2023|-15.5940480697826
LSO|2022|-5.54542819412816
LSO|2021|8.05020748132283
LSO|2020|-15.3754028773894
LSO|2019|-15.2054790557424
LSO|2018|5.26713578910307
LSO|2017|1.99895367740423
LSO|2016|12.2877794807702
LSO|2015|18.4960302706843
LSO|2014|-10.0356355875612
LSO|2013|-8.2912763729276
LSO|2012|-2.23167045247348
LSO|2011|11.8681828003498
LSO|2010|0.49265690021636
LSO|2009|-7.41037928460143
LSO|2008|8.16581268798444
LSO|2007|13.1751596312879
LSO|2006|21.8241336370676
LSO|2005|-5.36224366410042
LSO|2004|2.04359777275829
LSO|2003|-3.86378661678992
LSO|2002|39.8778651592405
LSO|2001|75.6032138958655
LSO|2000|34.2692587425732
LSO|1999|-4.79780733734194
LSO|1998|27.1912463754346
LSO|1997|9.39189140771681
LSO|1996|49.8858468542574
LSO|1995|6.6069671604525
MNG|2024|0.746513641748734
MNG|2023|33.1614745570681
MNG|2022|32.2734825144826
MNG|2021|-14.6346655791823
MNG|2020|-5.2646294005022
MNG|2019|11.9770203286065
MNG|2018|6.07062184523477
MNG|2017|3.69153031287195
MNG|2016|15.5161626202982
MNG|2015|0.121671372839671
MNG|2014|53.1665151271844
MNG|2013|12.8394587843417
MNG|2012|8.30489696635554
MNG|2011|18.2354991998968
MNG|2010|
MNG|2009|
MNG|2008|
MNG|2007|
MNG|2006|
MNG|2005|
MNG|2004|
MNG|2003|
MNG|2002|
MNG|2001|
MNG|2000|
MNG|1999|
MNG|1998|
MNG|1997|
MNG|1996|
MNG|1995|
MNP|2024|
MNP|2023|
MNP|2022|323.913043478261
MNP|2021|-58.1818181818182
MNP|2020|-74.5958429561201
MNP|2019|-24.5644599303136
MNP|2018|-40.702479338843
MNP|2017|20.3980099502488
MNP|2016|77.4834437086093
MNP|2015|10.2189781021898
MNP|2014|4.0506329113924
MNP|2013|4.22163588390501
MNP|2012|16.9753086419753
MNP|2011|-11.2328767123288
MNP|2010|2.52808988764043
MNP|2009|-34.4383057090239
MNP|2008|-36.2676056338028
MNP|2007|-25.4593175853018
MNP|2006|-19.3935119887165
MNP|2005|-16.9789227166276
MNP|2004|8.16972767574413
MNP|2003|-4.12871888281724
MNP|2002|
MNP|2001|
MNP|2000|
MNP|1999|
MNP|1998|
MNP|1997|
MNP|1996|
MNP|1995|
MOZ|2024|-3.4050150543912
MOZ|2023|-5.92986930062
MOZ|2022|26.5058098114799
MOZ|2021|16.7570560916445
MOZ|2020|-15.1589721040351
MOZ|2019|-2.67398498106863
MOZ|2018|17.2720111600082
MOZ|2017|3.24689065861661
MOZ|2016|-6.66623272315505
MOZ|2015|-5.40963241970576
MOZ|2014|25.7735833949881
MOZ|2013|2.00868659830763
MOZ|2012|10.4109443284015
MOZ|2011|15.3608794534169
MOZ|2010|1.37114830726095
MOZ|2009|14.8822178454663
MOZ|2008|5.07784548780619
MOZ|2007|15.0525779251266
MOZ|2006|13.0728752435455
MOZ|2005|5.83169979284672
MOZ|2004|24.3656979787649
MOZ|2003|19.8825957798072
MOZ|2002|32.8691866173538
MOZ|2001|58.0599829662537
MOZ|2000|34.5815915356308
MOZ|1999|-0.561668461634753
MOZ|1998|12.2829385939986
MOZ|1997|8.55352128471023
MOZ|1996|41.1927008685951
MOZ|1995|1.55673643498373
RWA|2024|22.6213850590871
RWA|2023|20.4007611238541
RWA|2022|58.2783635047479
RWA|2021|2.42360379231295
RWA|2020|-9.57598856486732
RWA|2019|19.8743575130381
RWA|2018|10.8929702331958
RWA|2017|41.8688229960466
RWA|2016|12.880324548175
RWA|2015|6.24999999945956
RWA|2014|7.40740740775139
RWA|2013|18.844566708843
RWA|2012|8.9955022482082
RWA|2011|23.5185185276823
RWA|2010|8.43373493451732
RWA|2009|-3.11284047081385
RWA|2008|-11.6838487979616
RWA|2007|44.0594059335143
RWA|2006|1.51133503158914
RWA|2005|11.2044817913982
RWA|2004|31.7343173363068
RWA|2003|20.4444444381198
RWA|2002|5.14018691763573
RWA|2001|39.8692810580617
RWA|2000|0
RWA|1999|40.4636178998172
RWA|1998|1.90025988372113
RWA|1997|30.4105999802531
RWA|1996|42.0712161941587
RWA|1995|8.57107566247765
SDN|2024|-30.0000071565927
SDN|2023|-37.09999131211
SDN|2022|11.9999979833292
SDN|2021|8.00003049207125
SDN|2020|5.23413689113607
SDN|2019|7.00001532778467
SDN|2018|8.00002383777598
SDN|2017|8.99999422596123
SDN|2016|-3.04005800050805
SDN|2015|-1.99997942549113
SDN|2014|72.000056621067
SDN|2013|61.9999732465502
SDN|2012|-76.6000108213832
SDN|2011|-96.3644190953262
SDN|2010|9.0000001417613
SDN|2009|1.79999995309828
SDN|2008|13.4599996041645
SDN|2007|13.0237430765303
SDN|2006|13.6631102853333
SDN|2005|2.94000090997481
SDN|2004|8.39999956576716
SDN|2003|28.0776550541077
SDN|2002|18.5219986064868
SDN|2001|9.8151577718961
SDN|2000|-10.6744788831439
SDN|1999|112.533344847165
SDN|1998|52.1951999176961
SDN|1997|1.83314313344836
SDN|1996|12.2910751539616
SDN|1995|1.54822467054258
SLE|2024|129.183930040268
SLE|2023|4.81657716655144
SLE|2022|8.98836667261398
SLE|2021|69.7699980427376
SLE|2020|-0.538312873482795
SLE|2019|-10.3681877870833
SLE|2018|-16.9631008961354
SLE|2017|-3.44797424472675
SLE|2016|20.6160807869834
SLE|2015|-22.532824300475
SLE|2014|26.9533567311571
SLE|2013|14.5439792699153
SLE|2012|133.776497215946
SLE|2011|-1.30350492333076
SLE|2010|19.4271180480046
SLE|2009|7.68374176184459
SLE|2008|-15.5779201630394
SLE|2007|0.202950459322977
SLE|2006|7.72432097056512
SLE|2005|8.63569019332373
SLE|2004|11.481606542056
SLE|2003|65.2978896581979
SLE|2002|36.723141693011
SLE|2001|11.7483395633481
SLE|2000|21.3547334580874
SLE|1999|-1.27889798431036
SLE|1998|-14.6985569497664
SLE|1997|-25.9369014785873
SLE|1996|76.3942755983189
SLE|1995|-36.1061170855037
SRB|2024|5.19048081365361
SRB|2023|2.72851608089648
SRB|2022|17.0313185618957
SRB|2021|20.4275168698308
SRB|2020|-4.5852598634585
SRB|2019|7.25188317026613
SRB|2018|9.04312531210374
SRB|2017|7.8637676636572
SRB|2016|10.8855972050591
SRB|2015|9.04236504259555
SRB|2014|4.26740407068064
SRB|2013|18.0402686253208
SRB|2012|2.8574665998822
SRB|2011|5.62873477108863
SRB|2010|16.8608693575283
SRB|2009|-11.5328372270531
SRB|2008|12.5580510715743
SRB|2007|2.90047295921229
SRB|2006|7.09623387767992
SRB|2005|18.5552452253195
SRB|2004|9.90117146932636
SRB|2003|28.0547721866429
SRB|2002|19.3404533225785
SRB|2001|53.996707443544
SRB|2000|13.8458181094284
SRB|1999|-42.2050027598679
SRB|1998|29.5049630392437
SRB|1997|51.0805052390224
SRB|1996|123.264351372019
SRB|1995|
STP|2024|6.78682315352803
STP|2023|-31.6635941211375
STP|2022|24.2918577040498
STP|2021|37.3938954755798
STP|2020|-32.5594411266692
STP|2019|-18.2838337423547
STP|2018|-17.6655256203331
STP|2017|-10.5978254240472
STP|2016|-24.8639493812882
STP|2015|19.1887017720933
STP|2014|87.0931285291828
STP|2013|47.6168640168942
STP|2012|2.83619734870459
STP|2011|3.31914429863645
STP|2010|22.5909378475128
STP|2009|-1.21843292214294
STP|2008|
STP|2007|
STP|2006|
STP|2005|
STP|2004|
STP|2003|
STP|2002|
STP|2001|
STP|2000|
STP|1999|
STP|1998|
STP|1997|
STP|1996|
STP|1995|
SYR|2024|
SYR|2023|
SYR|2022|30.6858979187065
SYR|2021|15.7659163239504
SYR|2020|47.1023322431005
SYR|2019|10.6959464256135
SYR|2018|-14.3826735281008
SYR|2017|29.9818291944276
SYR|2016|-4.43918765885698
SYR|2015|-4.45539793219524
SYR|2014|-14.4731430451592
SYR|2013|-30.5165392584125
SYR|2012|-67.1592274194759
SYR|2011|-47.2697580046518
SYR|2010|11.1881455069689
SYR|2009|-18.9798984445703
SYR|2008|-2.26164099145322
SYR|2007|1.41202619462145
SYR|2006|20.563752453964
SYR|2005|-1.49820399188714
SYR|2004|23.8570481489185
SYR|2003|-16.6245786684297
SYR|2002|0
SYR|2001|12.9632860444118
SYR|2000|0.474827090976746
SYR|1999|9.61916416360738
SYR|1998|0.502109061340647
SYR|1997|15.1339142917327
SYR|1996|13.4528235085856
SYR|1995|2.67968718048922
TKM|2024|
TKM|2023|
TKM|2022|
TKM|2021|
TKM|2020|
TKM|2019|
TKM|2018|
TKM|2017|
TKM|2016|
TKM|2015|
TKM|2014|
TKM|2013|
TKM|2012|
TKM|2011|
TKM|2010|
TKM|2009|
TKM|2008|
TKM|2007|
TKM|2006|42.5426947637293
TKM|2005|25
TKM|2004|13.1964035823533
TKM|2003|20.8860754555774
TKM|2002|7.09071806020822
TKM|2001|3.71304940654203
TKM|2000|101.628147127489
TKM|1999|61.668623004019
TKM|1998|-18.6346688935964
TKM|1997|-41.0594515784017
TKM|1996|-14.8675896281075
TKM|1995|-4.20075507931232
TLS|2024|-68.5136795859697
TLS|2023|-59.9912743810539
TLS|2022|-44.1479437820492
TLS|2021|7.38606156463489
TLS|2020|209.067191290216
TLS|2019|1045.4482506022
TLS|2018|16.6336658361891
TLS|2017|-39.0519286029222
TLS|2016|8.47253574115877
TLS|2015|-28.2768766726302
TLS|2014|-22.514484210864
TLS|2013|-24.1023728035394
TLS|2012|41.1537710942304
TLS|2011|-24.9263303386317
TLS|2010|28.0286246168874
TLS|2009|1.20189351655632
TLS|2008|21.3564591984283
TLS|2007|32.2071429255538
TLS|2006|20.8164200450815
TLS|2005|-10.6005466097575
TLS|2004|-10.705846925787
TLS|2003|-7.89073348035613
TLS|2002|-8.37878036688153
TLS|2001|23.2250305466114
TLS|2000|
TLS|1999|
TLS|1998|
TLS|1997|
TLS|1996|
TLS|1995|
VNM|2024|15.6430183136117
VNM|2023|-2.96622853597739
VNM|2022|4.22160032465622
VNM|2021|14.805732397093
VNM|2020|4.06262557016642
VNM|2019|6.23602796834999
VNM|2018|12.2533404787578
VNM|2017|17.253516150692
VNM|2016|11.0039665349257
VNM|2015|13.865902481727
VNM|2014|12.5802355977049
VNM|2013|17.8185178069048
VNM|2012|15.0414291650122
VNM|2011|10.5939353137905
VNM|2010|8.45001096338369
VNM|2009|-5.08505793060772
VNM|2008|13.6999685107938
VNM|2007|12.5000423741552
VNM|2006|11.1999864217698
VNM|2005|17.7759376366782
VNM|2004|25.6196995634225
VNM|2003|19.9495458597287
VNM|2002|10.3679070539275
VNM|2001|17.1804863625
VNM|2000|21.1010677434902
VNM|1999|22.9999999987523
VNM|1998|19.0000000010434
VNM|1997|16.0000000016758
VNM|1996|23.9999999981529
VNM|1995|20.0000000013853
XKX|2024|9.43304022881122
XKX|2023|7.23421516591199
XKX|2022|18.8836038629937
XKX|2021|76.7590418537396
XKX|2020|-29.0924926199787
XKX|2019|7.55370092575298
XKX|2018|9.06728422413509
XKX|2017|20.0155006019454
XKX|2016|10.3789913966063
XKX|2015|1.84342624386309
XKX|2014|6.31681215462909
XKX|2013|-1.47510951089667
XKX|2012|2.03036466076453
XKX|2011|28.2190092004357
XKX|2010|27.470336710984
XKX|2009|19.5994987979702
XKX|2008|
XKX|2007|
XKX|2006|
XKX|2005|
XKX|2004|
XKX|2003|
XKX|2002|
XKX|2001|
XKX|2000|
XKX|1999|
XKX|1998|
XKX|1997|
XKX|1996|
XKX|1995|
ZMB|2024|
ZMB|2023|
ZMB|2022|
ZMB|2021|
ZMB|2020|
ZMB|2019|
ZMB|2018|
ZMB|2017|
ZMB|2016|
ZMB|2015|
ZMB|2014|
ZMB|2013|
ZMB|2012|
ZMB|2011|
ZMB|2010|17.2441530736192
ZMB|2009|61.3276740124387
ZMB|2008|-5.60414929077338
ZMB|2007|10.7112102647903
ZMB|2006|10.4228280313029
ZMB|2005|39.7500549526363
ZMB|2004|57.1564559366442
ZMB|2003|57.9052418070563
ZMB|2002|34.8278931482342
ZMB|2001|20.7437610816085
ZMB|2000|-3.0376258123901
ZMB|1999|87.4513021409417
ZMB|1998|4.74067919462719
ZMB|1997|18.1270584590435
ZMB|1996|11.9716360455743
ZMB|1995|-10.5070805592605
```

Investment share (NE.GDI.TOTL.ZS), countries left out of the ranking:

```
AFG|2024|17.0868898068985
AFG|2023|15.2924823859473
AFG|2022|16.7
AFG|2021|13
AFG|2020|11.5
AFG|2019|
AFG|2018|
AFG|2017|
AFG|2016|
AFG|2015|
AFG|2014|
AFG|2013|
AFG|2012|
AFG|2011|
AFG|2010|
AFG|2009|
AFG|2008|
AFG|2007|
AFG|2006|
AFG|2005|
AFG|2004|
AFG|2003|
AFG|2002|
AFG|2001|
AFG|2000|
AFG|1999|
AFG|1998|
AFG|1997|
AFG|1996|
AFG|1995|
AND|2024|
AND|2023|
AND|2022|
AND|2021|
AND|2020|
AND|2019|
AND|2018|
AND|2017|
AND|2016|
AND|2015|
AND|2014|
AND|2013|
AND|2012|
AND|2011|
AND|2010|
AND|2009|
AND|2008|
AND|2007|
AND|2006|
AND|2005|
AND|2004|
AND|2003|
AND|2002|
AND|2001|
AND|2000|
AND|1999|
AND|1998|
AND|1997|
AND|1996|
AND|1995|
ASM|2024|
ASM|2023|
ASM|2022|
ASM|2021|
ASM|2020|
ASM|2019|
ASM|2018|
ASM|2017|
ASM|2016|
ASM|2015|
ASM|2014|
ASM|2013|
ASM|2012|
ASM|2011|
ASM|2010|
ASM|2009|
ASM|2008|
ASM|2007|
ASM|2006|
ASM|2005|
ASM|2004|
ASM|2003|
ASM|2002|
ASM|2001|
ASM|2000|
ASM|1999|
ASM|1998|
ASM|1997|
ASM|1996|
ASM|1995|
ATG|2024|
ATG|2023|
ATG|2022|
ATG|2021|
ATG|2020|
ATG|2019|
ATG|2018|
ATG|2017|
ATG|2016|
ATG|2015|
ATG|2014|
ATG|2013|
ATG|2012|
ATG|2011|
ATG|2010|
ATG|2009|
ATG|2008|
ATG|2007|
ATG|2006|
ATG|2005|
ATG|2004|
ATG|2003|
ATG|2002|
ATG|2001|
ATG|2000|
ATG|1999|
ATG|1998|
ATG|1997|
ATG|1996|
ATG|1995|
BDI|2024|
BDI|2023|
BDI|2022|
BDI|2021|
BDI|2020|
BDI|2019|
BDI|2018|
BDI|2017|
BDI|2016|
BDI|2015|
BDI|2014|
BDI|2013|
BDI|2012|
BDI|2011|
BDI|2010|
BDI|2009|
BDI|2008|
BDI|2007|
BDI|2006|
BDI|2005|
BDI|2004|
BDI|2003|
BDI|2002|
BDI|2001|
BDI|2000|
BDI|1999|
BDI|1998|
BDI|1997|
BDI|1996|
BDI|1995|
BMU|2024|11.038752628066
BMU|2023|11.2150851626763
BMU|2022|12.7026098741948
BMU|2021|12.902924909709
BMU|2020|12.2379040805742
BMU|2019|14.7485170334877
BMU|2018|13.4097576009445
BMU|2017|13.763644733725
BMU|2016|12.8032086210967
BMU|2015|11.8925858297364
BMU|2014|12.0945969964397
BMU|2013|10.8931113391845
BMU|2012|11.0144291764369
BMU|2011|12.5825420569453
BMU|2010|13.0430267361979
BMU|2009|
BMU|2008|
BMU|2007|
BMU|2006|
BMU|2005|
BMU|2004|
BMU|2003|
BMU|2002|
BMU|2001|
BMU|2000|
BMU|1999|
BMU|1998|
BMU|1997|
BMU|1996|
BMU|1995|
BRB|2024|
BRB|2023|
BRB|2022|
BRB|2021|
BRB|2020|
BRB|2019|
BRB|2018|
BRB|2017|
BRB|2016|
BRB|2015|
BRB|2014|
BRB|2013|
BRB|2012|
BRB|2011|
BRB|2010|
BRB|2009|
BRB|2008|
BRB|2007|
BRB|2006|
BRB|2005|
BRB|2004|
BRB|2003|
BRB|2002|
BRB|2001|
BRB|2000|
BRB|1999|
BRB|1998|
BRB|1997|
BRB|1996|
BRB|1995|
CHI|2024|
CHI|2023|
CHI|2022|
CHI|2021|
CHI|2020|
CHI|2019|
CHI|2018|
CHI|2017|
CHI|2016|
CHI|2015|
CHI|2014|
CHI|2013|
CHI|2012|
CHI|2011|
CHI|2010|
CHI|2009|
CHI|2008|
CHI|2007|
CHI|2006|
CHI|2005|
CHI|2004|
CHI|2003|
CHI|2002|
CHI|2001|
CHI|2000|
CHI|1999|
CHI|1998|
CHI|1997|
CHI|1996|
CHI|1995|
CPV|2024|16.3137481360407
CPV|2023|21.7251071461541
CPV|2022|21.8794313027596
CPV|2021|27.7497642140942
CPV|2020|28.9619236573871
CPV|2019|23.4319738651901
CPV|2018|27.486159184509
CPV|2017|29.2834862444324
CPV|2016|28.5553782407275
CPV|2015|29.1071744394227
CPV|2014|34.9962522997627
CPV|2013|29.9872865504067
CPV|2012|35.2038713812683
CPV|2011|44.9117743846551
CPV|2010|44.9568060390526
CPV|2009|41.3602933111924
CPV|2008|45.9358045471371
CPV|2007|47.271484248355
CPV|2006|
CPV|2005|
CPV|2004|
CPV|2003|
CPV|2002|
CPV|2001|
CPV|2000|
CPV|1999|
CPV|1998|
CPV|1997|
CPV|1996|
CPV|1995|
CUW|2024|
CUW|2023|
CUW|2022|
CUW|2021|
CUW|2020|
CUW|2019|
CUW|2018|41.0673551203898
CUW|2017|30.8959067067378
CUW|2016|28.6395278604093
CUW|2015|26.3697416948829
CUW|2014|25.7891289955871
CUW|2013|30.4838533181729
CUW|2012|32.2011392260924
CUW|2011|37.7759954207402
CUW|2010|36.6275848758626
CUW|2009|36.5864282225877
CUW|2008|38.9359277053594
CUW|2007|35.4515345216102
CUW|2006|34.3026947528675
CUW|2005|34.9138591723173
CUW|2004|
CUW|2003|
CUW|2002|
CUW|2001|
CUW|2000|
CUW|1999|
CUW|1998|
CUW|1997|
CUW|1996|
CUW|1995|
CYM|2024|
CYM|2023|
CYM|2022|
CYM|2021|
CYM|2020|
CYM|2019|
CYM|2018|
CYM|2017|
CYM|2016|
CYM|2015|
CYM|2014|
CYM|2013|
CYM|2012|
CYM|2011|
CYM|2010|
CYM|2009|
CYM|2008|
CYM|2007|
CYM|2006|
CYM|2005|
CYM|2004|
CYM|2003|
CYM|2002|
CYM|2001|
CYM|2000|
CYM|1999|
CYM|1998|
CYM|1997|
CYM|1996|
CYM|1995|
DJI|2024|0.252268985586049
DJI|2023|-3.7352612180732
DJI|2022|-10.5957415251433
DJI|2021|-15.6784437711797
DJI|2020|-0.248727784664231
DJI|2019|2.28145969959191
DJI|2018|2.78690075604472
DJI|2017|21.6328079279849
DJI|2016|21.9359401140492
DJI|2015|-3.94592435677103
DJI|2014|3.11518509884608
DJI|2013|56.9079297902791
DJI|2012|
DJI|2011|
DJI|2010|
DJI|2009|
DJI|2008|
DJI|2007|
DJI|2006|
DJI|2005|
DJI|2004|
DJI|2003|
DJI|2002|
DJI|2001|
DJI|2000|
DJI|1999|
DJI|1998|
DJI|1997|
DJI|1996|
DJI|1995|
DMA|2024|
DMA|2023|
DMA|2022|
DMA|2021|
DMA|2020|
DMA|2019|
DMA|2018|
DMA|2017|
DMA|2016|
DMA|2015|
DMA|2014|
DMA|2013|
DMA|2012|
DMA|2011|
DMA|2010|
DMA|2009|
DMA|2008|
DMA|2007|
DMA|2006|
DMA|2005|
DMA|2004|
DMA|2003|
DMA|2002|
DMA|2001|
DMA|2000|
DMA|1999|
DMA|1998|
DMA|1997|
DMA|1996|
DMA|1995|
ERI|2024|
ERI|2023|
ERI|2022|
ERI|2021|
ERI|2020|
ERI|2019|
ERI|2018|
ERI|2017|
ERI|2016|
ERI|2015|
ERI|2014|
ERI|2013|
ERI|2012|
ERI|2011|12.626317662696
ERI|2010|12.3854014927083
ERI|2009|9.26379597839317
ERI|2008|12.7135404800139
ERI|2007|12.6735754136609
ERI|2006|13.6811165438244
ERI|2005|20.3394397206045
ERI|2004|20.2629217457409
ERI|2003|26.5439604075464
ERI|2002|29.5489323270544
ERI|2001|35.2606217610795
ERI|2000|21.9967567603027
ERI|1999|45.5141796492478
ERI|1998|32.2868589150857
ERI|1997|31.2807273816123
ERI|1996|27.5892573606133
ERI|1995|22.5366961317006
FSM|2024|
FSM|2023|
FSM|2022|
FSM|2021|
FSM|2020|
FSM|2019|
FSM|2018|
FSM|2017|
FSM|2016|
FSM|2015|
FSM|2014|
FSM|2013|
FSM|2012|
FSM|2011|
FSM|2010|
FSM|2009|
FSM|2008|
FSM|2007|
FSM|2006|
FSM|2005|
FSM|2004|
FSM|2003|
FSM|2002|
FSM|2001|
FSM|2000|
FSM|1999|
FSM|1998|
FSM|1997|
FSM|1996|
FSM|1995|
GIB|2024|
GIB|2023|
GIB|2022|
GIB|2021|
GIB|2020|
GIB|2019|
GIB|2018|
GIB|2017|
GIB|2016|
GIB|2015|
GIB|2014|
GIB|2013|
GIB|2012|
GIB|2011|
GIB|2010|
GIB|2009|
GIB|2008|
GIB|2007|
GIB|2006|
GIB|2005|
GIB|2004|
GIB|2003|
GIB|2002|
GIB|2001|
GIB|2000|
GIB|1999|
GIB|1998|
GIB|1997|
GIB|1996|
GIB|1995|
GNQ|2024|5.05406672559606
GNQ|2023|5.29395318380449
GNQ|2022|7.33815470437154
GNQ|2021|8.24679554193157
GNQ|2020|6.98846405853807
GNQ|2019|10.891703090741
GNQ|2018|12.5014966275534
GNQ|2017|14.03171665413
GNQ|2016|16.6986459903143
GNQ|2015|24.7014529043977
GNQ|2014|28.7093001746
GNQ|2013|30.3080451576082
GNQ|2012|41.1481428957988
GNQ|2011|32.0492712659016
GNQ|2010|38.0562994925977
GNQ|2009|39.3928256509129
GNQ|2008|27.5417518128173
GNQ|2007|29.585907339941
GNQ|2006|26.5011245422482
GNQ|2005|39.4767488235046
GNQ|2004|
GNQ|2003|
GNQ|2002|
GNQ|2001|
GNQ|2000|
GNQ|1999|
GNQ|1998|
GNQ|1997|
GNQ|1996|
GNQ|1995|
GRD|2024|
GRD|2023|
GRD|2022|
GRD|2021|
GRD|2020|
GRD|2019|
GRD|2018|
GRD|2017|
GRD|2016|
GRD|2015|
GRD|2014|
GRD|2013|
GRD|2012|
GRD|2011|
GRD|2010|
GRD|2009|
GRD|2008|
GRD|2007|
GRD|2006|
GRD|2005|
GRD|2004|
GRD|2003|
GRD|2002|
GRD|2001|
GRD|2000|
GRD|1999|
GRD|1998|
GRD|1997|
GRD|1996|
GRD|1995|
GUM|2024|
GUM|2023|
GUM|2022|
GUM|2021|
GUM|2020|
GUM|2019|
GUM|2018|
GUM|2017|
GUM|2016|
GUM|2015|
GUM|2014|
GUM|2013|
GUM|2012|
GUM|2011|
GUM|2010|
GUM|2009|
GUM|2008|
GUM|2007|
GUM|2006|
GUM|2005|
GUM|2004|
GUM|2003|
GUM|2002|
GUM|2001|
GUM|2000|
GUM|1999|
GUM|1998|
GUM|1997|
GUM|1996|
GUM|1995|
GUY|2024|
GUY|2023|
GUY|2022|
GUY|2021|
GUY|2020|
GUY|2019|
GUY|2018|
GUY|2017|
GUY|2016|
GUY|2015|
GUY|2014|
GUY|2013|
GUY|2012|
GUY|2011|
GUY|2010|
GUY|2009|
GUY|2008|
GUY|2007|
GUY|2006|
GUY|2005|32.3339782741868
GUY|2004|23.5456808733306
GUY|2003|20.952115865171
GUY|2002|20.8604990254453
GUY|2001|21.5703446978272
GUY|2000|23.7759824891985
GUY|1999|24.9979547163444
GUY|1998|28.9207551153805
GUY|1997|31.8879419916993
GUY|1996|31.8572069303129
GUY|1995|33.2286832637757
IMN|2024|
IMN|2023|
IMN|2022|
IMN|2021|
IMN|2020|
IMN|2019|
IMN|2018|
IMN|2017|
IMN|2016|
IMN|2015|
IMN|2014|
IMN|2013|
IMN|2012|
IMN|2011|
IMN|2010|
IMN|2009|
IMN|2008|
IMN|2007|
IMN|2006|
IMN|2005|
IMN|2004|
IMN|2003|
IMN|2002|
IMN|2001|
IMN|2000|
IMN|1999|
IMN|1998|
IMN|1997|
IMN|1996|
IMN|1995|
JAM|2024|
JAM|2023|
JAM|2022|
JAM|2021|
JAM|2020|
JAM|2019|
JAM|2018|
JAM|2017|
JAM|2016|
JAM|2015|
JAM|2014|
JAM|2013|
JAM|2012|
JAM|2011|
JAM|2010|
JAM|2009|
JAM|2008|
JAM|2007|
JAM|2006|
JAM|2005|
JAM|2004|
JAM|2003|
JAM|2002|
JAM|2001|
JAM|2000|
JAM|1999|
JAM|1998|
JAM|1997|
JAM|1996|
JAM|1995|
JOR|2024|
JOR|2023|
JOR|2022|
JOR|2021|
JOR|2020|
JOR|2019|
JOR|2018|
JOR|2017|
JOR|2016|
JOR|2015|
JOR|2014|
JOR|2013|
JOR|2012|
JOR|2011|
JOR|2010|
JOR|2009|
JOR|2008|
JOR|2007|30.2679844699249
JOR|2006|28.339921689117
JOR|2005|34.1478444026172
JOR|2004|27.383850993091
JOR|2003|20.8405384093959
JOR|2002|20.0956726523403
JOR|2001|21.05693228782
JOR|2000|22.3615116608599
JOR|1999|21.5686274509804
JOR|1998|21.8189596777069
JOR|1997|25.7294687871061
JOR|1996|30.5256942747781
JOR|1995|32.962860839502
KIR|2024|29.9143158847463
KIR|2023|24.7440984281941
KIR|2022|23.275366383485
KIR|2021|17.763963018856
KIR|2020|14.6970481211532
KIR|2019|15.9140674046536
KIR|2018|18.9415015974441
KIR|2017|27.0021649484536
KIR|2016|29.9666166684789
KIR|2015|37.7690573638693
KIR|2014|28.6593579496587
KIR|2013|31.377071852949
KIR|2012|27.7265217537013
KIR|2011|19.4615071231639
KIR|2010|15.9163081562957
KIR|2009|17.5720885152996
KIR|2008|14.1246580305412
KIR|2007|15.3649166957601
KIR|2006|15.7544159059084
KIR|2005|
KIR|2004|
KIR|2003|
KIR|2002|
KIR|2001|
KIR|2000|
KIR|1999|
KIR|1998|
KIR|1997|
KIR|1996|
KIR|1995|
KNA|2024|
KNA|2023|
KNA|2022|
KNA|2021|
KNA|2020|
KNA|2019|
KNA|2018|
KNA|2017|
KNA|2016|
KNA|2015|
KNA|2014|
KNA|2013|
KNA|2012|
KNA|2011|
KNA|2010|
KNA|2009|
KNA|2008|
KNA|2007|
KNA|2006|
KNA|2005|
KNA|2004|
KNA|2003|
KNA|2002|
KNA|2001|
KNA|2000|
KNA|1999|
KNA|1998|
KNA|1997|
KNA|1996|
KNA|1995|
LBR|2024|
LBR|2023|
LBR|2022|
LBR|2021|
LBR|2020|
LBR|2019|
LBR|2018|
LBR|2017|
LBR|2016|
LBR|2015|
LBR|2014|
LBR|2013|
LBR|2012|
LBR|2011|
LBR|2010|
LBR|2009|
LBR|2008|
LBR|2007|
LBR|2006|
LBR|2005|
LBR|2004|
LBR|2003|
LBR|2002|
LBR|2001|
LBR|2000|
LBR|1999|
LBR|1998|
LBR|1997|
LBR|1996|
LBR|1995|
LCA|2024|
LCA|2023|
LCA|2022|
LCA|2021|
LCA|2020|
LCA|2019|
LCA|2018|
LCA|2017|
LCA|2016|
LCA|2015|
LCA|2014|
LCA|2013|
LCA|2012|
LCA|2011|
LCA|2010|
LCA|2009|
LCA|2008|
LCA|2007|
LCA|2006|
LCA|2005|
LCA|2004|
LCA|2003|
LCA|2002|
LCA|2001|
LCA|2000|
LCA|1999|
LCA|1998|
LCA|1997|
LCA|1996|
LCA|1995|
LIE|2024|
LIE|2023|
LIE|2022|
LIE|2021|
LIE|2020|
LIE|2019|
LIE|2018|
LIE|2017|
LIE|2016|
LIE|2015|
LIE|2014|
LIE|2013|
LIE|2012|
LIE|2011|
LIE|2010|
LIE|2009|
LIE|2008|
LIE|2007|
LIE|2006|
LIE|2005|
LIE|2004|
LIE|2003|
LIE|2002|
LIE|2001|
LIE|2000|
LIE|1999|
LIE|1998|
LIE|1997|
LIE|1996|
LIE|1995|
LSO|2024|29.6721348878596
LSO|2023|27.0684655311306
LSO|2022|27.3770081483323
LSO|2021|28.4701352359002
LSO|2020|26.2646701221778
LSO|2019|26.7945041312681
LSO|2018|21.4472792170962
LSO|2017|22.2056129829322
LSO|2016|28.7760063691053
LSO|2015|30.4366347369568
LSO|2014|34.0968182808394
LSO|2013|32.6667455053055
LSO|2012|35.7205960501896
LSO|2011|25.3316425094885
LSO|2010|31.3011900430751
LSO|2009|30.538219790262
LSO|2008|27.9814428627338
LSO|2007|24.9246019342258
LSO|2006|
LSO|2005|
LSO|2004|
LSO|2003|
LSO|2002|
LSO|2001|
LSO|2000|
LSO|1999|
LSO|1998|
LSO|1997|
LSO|1996|
LSO|1995|
MAF|2024|
MAF|2023|
MAF|2022|
MAF|2021|
MAF|2020|
MAF|2019|
MAF|2018|
MAF|2017|
MAF|2016|
MAF|2015|
MAF|2014|
MAF|2013|
MAF|2012|
MAF|2011|
MAF|2010|
MAF|2009|
MAF|2008|
MAF|2007|
MAF|2006|
MAF|2005|
MAF|2004|
MAF|2003|
MAF|2002|
MAF|2001|
MAF|2000|
MAF|1999|
MAF|1998|
MAF|1997|
MAF|1996|
MAF|1995|
MCO|2024|
MCO|2023|
MCO|2022|
MCO|2021|
MCO|2020|
MCO|2019|
MCO|2018|
MCO|2017|
MCO|2016|
MCO|2015|
MCO|2014|
MCO|2013|
MCO|2012|
MCO|2011|
MCO|2010|
MCO|2009|
MCO|2008|
MCO|2007|
MCO|2006|
MCO|2005|
MCO|2004|
MCO|2003|
MCO|2002|
MCO|2001|
MCO|2000|
MCO|1999|
MCO|1998|
MCO|1997|
MCO|1996|
MCO|1995|
MDV|2024|30.7946843948579
MDV|2023|33.0509347055178
MDV|2022|32.9897963177697
MDV|2021|25.1856622862565
MDV|2020|35.5119966004124
MDV|2019|43.161162875967
MDV|2018|48.970177770723
MDV|2017|42.8197158524795
MDV|2016|39.7662853405846
MDV|2015|31.9049232315583
MDV|2014|27.8611798197388
MDV|2013|
MDV|2012|
MDV|2011|
MDV|2010|
MDV|2009|
MDV|2008|
MDV|2007|
MDV|2006|
MDV|2005|
MDV|2004|
MDV|2003|
MDV|2002|
MDV|2001|
MDV|2000|
MDV|1999|
MDV|1998|
MDV|1997|
MDV|1996|
MDV|1995|
MMR|2024|
MMR|2023|
MMR|2022|
MMR|2021|
MMR|2020|
MMR|2019|
MMR|2018|
MMR|2017|
MMR|2016|
MMR|2015|
MMR|2014|
MMR|2013|
MMR|2012|
MMR|2011|
MMR|2010|
MMR|2009|
MMR|2008|
MMR|2007|
MMR|2006|
MMR|2005|
MMR|2004|
MMR|2003|
MMR|2002|
MMR|2001|
MMR|2000|
MMR|1999|
MMR|1998|
MMR|1997|
MMR|1996|
MMR|1995|
MNP|2024|
MNP|2023|
MNP|2022|
MNP|2021|
MNP|2020|
MNP|2019|
MNP|2018|
MNP|2017|
MNP|2016|
MNP|2015|
MNP|2014|
MNP|2013|
MNP|2012|
MNP|2011|
MNP|2010|
MNP|2009|
MNP|2008|
MNP|2007|
MNP|2006|
MNP|2005|
MNP|2004|
MNP|2003|
MNP|2002|
MNP|2001|
MNP|2000|
MNP|1999|
MNP|1998|
MNP|1997|
MNP|1996|
MNP|1995|
MWI|2024|13.7207306888371
MWI|2023|14.4830771619003
MWI|2022|15.9327969038503
MWI|2021|16.915576065163
MWI|2020|16.7106351396417
MWI|2019|21.9119103002645
MWI|2018|21.276061190562
MWI|2017|20.2873149467203
MWI|2016|
MWI|2015|
MWI|2014|
MWI|2013|
MWI|2012|
MWI|2011|
MWI|2010|
MWI|2009|
MWI|2008|
MWI|2007|
MWI|2006|
MWI|2005|
MWI|2004|
MWI|2003|
MWI|2002|
MWI|2001|
MWI|2000|
MWI|1999|
MWI|1998|
MWI|1997|
MWI|1996|
MWI|1995|
NGA|2024|
NGA|2023|
NGA|2022|
NGA|2021|
NGA|2020|
NGA|2019|
NGA|2018|
NGA|2017|
NGA|2016|
NGA|2015|
NGA|2014|
NGA|2013|
NGA|2012|
NGA|2011|
NGA|2010|
NGA|2009|
NGA|2008|
NGA|2007|
NGA|2006|
NGA|2005|
NGA|2004|
NGA|2003|
NGA|2002|
NGA|2001|
NGA|2000|
NGA|1999|
NGA|1998|
NGA|1997|
NGA|1996|
NGA|1995|
NRU|2024|
NRU|2023|
NRU|2022|
NRU|2021|
NRU|2020|
NRU|2019|
NRU|2018|
NRU|2017|
NRU|2016|
NRU|2015|
NRU|2014|
NRU|2013|
NRU|2012|
NRU|2011|
NRU|2010|
NRU|2009|
NRU|2008|
NRU|2007|
NRU|2006|
NRU|2005|
NRU|2004|
NRU|2003|
NRU|2002|
NRU|2001|
NRU|2000|
NRU|1999|
NRU|1998|
NRU|1997|
NRU|1996|
NRU|1995|
PLW|2024|34.9671396264766
PLW|2023|35.7028148801293
PLW|2022|44.2218552162716
PLW|2021|37.9055423479613
PLW|2020|42.1552745248217
PLW|2019|34.5726607886393
PLW|2018|28.7972372599112
PLW|2017|32.7792611587916
PLW|2016|28.9179839026394
PLW|2015|28.4164078174665
PLW|2014|31.3815122404028
PLW|2013|24.5409409522502
PLW|2012|28.214293269754
PLW|2011|30.0308082907055
PLW|2010|26.1102567261303
PLW|2009|25.9358656817089
PLW|2008|32.1363226846543
PLW|2007|35.6034549416197
PLW|2006|39.0748544913473
PLW|2005|43.7874612137915
PLW|2004|
PLW|2003|
PLW|2002|
PLW|2001|
PLW|2000|
PLW|1999|
PLW|1998|
PLW|1997|
PLW|1996|
PLW|1995|
PNG|2024|
PNG|2023|
PNG|2022|
PNG|2021|
PNG|2020|
PNG|2019|
PNG|2018|
PNG|2017|
PNG|2016|
PNG|2015|
PNG|2014|
PNG|2013|
PNG|2012|
PNG|2011|
PNG|2010|
PNG|2009|
PNG|2008|
PNG|2007|
PNG|2006|
PNG|2005|
PNG|2004|20.0013064999479
PNG|2003|19.9214691833082
PNG|2002|21.1919831839046
PNG|2001|22.9518867289324
PNG|2000|21.892017091559
PNG|1999|16.3683366937768
PNG|1998|17.9066853759803
PNG|1997|21.0575795242669
PNG|1996|22.7455163583381
PNG|1995|21.939185109852
PRK|2024|
PRK|2023|
PRK|2022|
PRK|2021|
PRK|2020|
PRK|2019|
PRK|2018|
PRK|2017|
PRK|2016|
PRK|2015|
PRK|2014|
PRK|2013|
PRK|2012|
PRK|2011|
PRK|2010|
PRK|2009|
PRK|2008|
PRK|2007|
PRK|2006|
PRK|2005|
PRK|2004|
PRK|2003|
PRK|2002|
PRK|2001|
PRK|2000|
PRK|1999|
PRK|1998|
PRK|1997|
PRK|1996|
PRK|1995|
PYF|2024|21.9053653809211
PYF|2023|22.6504245108896
PYF|2022|22.50674340275
PYF|2021|22.0083668171371
PYF|2020|21.095927488638
PYF|2019|25.4985138057167
PYF|2018|27.4598586301122
PYF|2017|19.6741291312004
PYF|2016|18.3657938165901
PYF|2015|19.9706011745564
PYF|2014|18.9560603620347
PYF|2013|19.3028649662983
PYF|2012|18.2394492723473
PYF|2011|18.1944154581742
PYF|2010|21.1616841006284
PYF|2009|20.883221176291
PYF|2008|23.9672290255229
PYF|2007|22.3199023199023
PYF|2006|21.9680547326289
PYF|2005|24.8555430885454
PYF|2004|
PYF|2003|
PYF|2002|
PYF|2001|
PYF|2000|
PYF|1999|
PYF|1998|
PYF|1997|
PYF|1996|
PYF|1995|
SMR|2024|
SMR|2023|16.5828788451836
SMR|2022|23.0259588963445
SMR|2021|22.2349508792548
SMR|2020|18.0508704925175
SMR|2019|24.0244755743653
SMR|2018|20.6091878712611
SMR|2017|19.1193560418814
SMR|2016|15.7692011952972
SMR|2015|12.0862064854973
SMR|2014|
SMR|2013|
SMR|2012|
SMR|2011|
SMR|2010|
SMR|2009|
SMR|2008|
SMR|2007|
SMR|2006|
SMR|2005|
SMR|2004|
SMR|2003|
SMR|2002|
SMR|2001|
SMR|2000|
SMR|1999|
SMR|1998|
SMR|1997|
SMR|1996|
SMR|1995|
SOM|2024|26.7485585359739
SOM|2023|23.6083226866216
SOM|2022|23.6499068901304
SOM|2021|17.9795423389223
SOM|2020|16.006026889198
SOM|2019|16.0813308687616
SOM|2018|16.1056776324146
SOM|2017|13.8251070470324
SOM|2016|12.8456368959279
SOM|2015|13.1480812127699
SOM|2014|13.4104063533751
SOM|2013|14.3695600150118
SOM|2012|15.7360330751388
SOM|2011|
SOM|2010|
SOM|2009|
SOM|2008|
SOM|2007|
SOM|2006|
SOM|2005|
SOM|2004|
SOM|2003|
SOM|2002|
SOM|2001|
SOM|2000|
SOM|1999|
SOM|1998|
SOM|1997|
SOM|1996|
SOM|1995|
SSD|2024|
SSD|2023|
SSD|2022|
SSD|2021|
SSD|2020|
SSD|2019|
SSD|2018|
SSD|2017|
SSD|2016|
SSD|2015|5.75075637151052
SSD|2014|7.9945088302124
SSD|2013|11.3677738263753
SSD|2012|7.0742528372385
SSD|2011|9.48877706805626
SSD|2010|10.2896550768433
SSD|2009|13.6521309804579
SSD|2008|13.7699875260258
SSD|2007|
SSD|2006|
SSD|2005|
SSD|2004|
SSD|2003|
SSD|2002|
SSD|2001|
SSD|2000|
SSD|1999|
SSD|1998|
SSD|1997|
SSD|1996|
SSD|1995|
STP|2024|6.92136880359529
STP|2023|6.20476462377871
STP|2022|8.2925116011365
STP|2021|10.2866385323613
STP|2020|11.8050231657312
STP|2019|11.9753186750673
STP|2018|13.7536956718475
STP|2017|15.303904220694
STP|2016|13.1023402352826
STP|2015|14.5502307918632
STP|2014|16.2190837351036
STP|2013|17.1080459100707
STP|2012|16.5558937115758
STP|2011|22.4489867997261
STP|2010|25.7158326122362
STP|2009|21.3371255943894
STP|2008|18.7857875236744
STP|2007|
STP|2006|
STP|2005|
STP|2004|
STP|2003|
STP|2002|
STP|2001|
STP|2000|
STP|1999|
STP|1998|
STP|1997|
STP|1996|
STP|1995|
SUR|2024|
SUR|2023|
SUR|2022|
SUR|2021|
SUR|2020|
SUR|2019|
SUR|2018|
SUR|2017|
SUR|2016|
SUR|2015|
SUR|2014|
SUR|2013|
SUR|2012|
SUR|2011|
SUR|2010|36.2044525973484
SUR|2009|50.1880052641474
SUR|2008|44.3081047638688
SUR|2007|46.1853368068478
SUR|2006|40.1609769636414
SUR|2005|
SUR|2004|
SUR|2003|
SUR|2002|
SUR|2001|
SUR|2000|
SUR|1999|
SUR|1998|
SUR|1997|
SUR|1996|
SUR|1995|
SWZ|2024|14.9720984162991
SWZ|2023|20.8277519082123
SWZ|2022|22.0925604538439
SWZ|2021|19.7885871413021
SWZ|2020|15.2902282173586
SWZ|2019|16.2318349707561
SWZ|2018|19.8490383026284
SWZ|2017|17.6967903356276
SWZ|2016|17.3577663965022
SWZ|2015|17.2217061828251
SWZ|2014|19.6275885076679
SWZ|2013|16.1345781176745
SWZ|2012|
SWZ|2011|
SWZ|2010|
SWZ|2009|
SWZ|2008|
SWZ|2007|
SWZ|2006|
SWZ|2005|
SWZ|2004|
SWZ|2003|
SWZ|2002|
SWZ|2001|
SWZ|2000|
SWZ|1999|
SWZ|1998|
SWZ|1997|
SWZ|1996|
SWZ|1995|
SXM|2024|
SXM|2023|
SXM|2022|
SXM|2021|
SXM|2020|
SXM|2019|
SXM|2018|
SXM|2017|
SXM|2016|
SXM|2015|
SXM|2014|
SXM|2013|
SXM|2012|
SXM|2011|
SXM|2010|
SXM|2009|
SXM|2008|
SXM|2007|
SXM|2006|
SXM|2005|
SXM|2004|
SXM|2003|
SXM|2002|
SXM|2001|
SXM|2000|
SXM|1999|
SXM|1998|
SXM|1997|
SXM|1996|
SXM|1995|
SYR|2024|
SYR|2023|
SYR|2022|
SYR|2021|
SYR|2020|
SYR|2019|
SYR|2018|
SYR|2017|
SYR|2016|
SYR|2015|
SYR|2014|
SYR|2013|
SYR|2012|
SYR|2011|
SYR|2010|
SYR|2009|
SYR|2008|
SYR|2007|
SYR|2006|
SYR|2005|
SYR|2004|
SYR|2003|
SYR|2002|
SYR|2001|
SYR|2000|
SYR|1999|
SYR|1998|
SYR|1997|
SYR|1996|
SYR|1995|
TCA|2024|
TCA|2023|
TCA|2022|
TCA|2021|
TCA|2020|
TCA|2019|
TCA|2018|
TCA|2017|
TCA|2016|
TCA|2015|
TCA|2014|
TCA|2013|
TCA|2012|
TCA|2011|
TCA|2010|
TCA|2009|
TCA|2008|
TCA|2007|
TCA|2006|
TCA|2005|
TCA|2004|
TCA|2003|
TCA|2002|
TCA|2001|
TCA|2000|
TCA|1999|
TCA|1998|
TCA|1997|
TCA|1996|
TCA|1995|
TKM|2024|
TKM|2023|
TKM|2022|
TKM|2021|
TKM|2020|
TKM|2019|
TKM|2018|
TKM|2017|
TKM|2016|
TKM|2015|
TKM|2014|
TKM|2013|
TKM|2012|
TKM|2011|
TKM|2010|
TKM|2009|46.6
TKM|2008|31.7
TKM|2007|18.6
TKM|2006|19.5019564924266
TKM|2005|22.9195946475561
TKM|2004|23.0536196152804
TKM|2003|25.4187357966501
TKM|2002|27.5596816976127
TKM|2001|31.7126612120372
TKM|2000|34.7386559448593
TKM|1999|39.6709050112191
TKM|1998|45.4948195784209
TKM|1997|38.6768676867687
TKM|1996|49.4207741935484
TKM|1995|
TUV|2024|
TUV|2023|
TUV|2022|
TUV|2021|
TUV|2020|
TUV|2019|
TUV|2018|
TUV|2017|
TUV|2016|
TUV|2015|
TUV|2014|
TUV|2013|
TUV|2012|
TUV|2011|
TUV|2010|
TUV|2009|
TUV|2008|
TUV|2007|
TUV|2006|
TUV|2005|
TUV|2004|
TUV|2003|
TUV|2002|
TUV|2001|
TUV|2000|
TUV|1999|
TUV|1998|
TUV|1997|
TUV|1996|
TUV|1995|
VCT|2024|
VCT|2023|
VCT|2022|
VCT|2021|
VCT|2020|
VCT|2019|
VCT|2018|
VCT|2017|
VCT|2016|
VCT|2015|
VCT|2014|
VCT|2013|
VCT|2012|
VCT|2011|
VCT|2010|
VCT|2009|
VCT|2008|
VCT|2007|
VCT|2006|
VCT|2005|
VCT|2004|
VCT|2003|
VCT|2002|
VCT|2001|
VCT|2000|
VCT|1999|
VCT|1998|
VCT|1997|
VCT|1996|
VCT|1995|
VGB|2024|
VGB|2023|
VGB|2022|
VGB|2021|
VGB|2020|
VGB|2019|
VGB|2018|
VGB|2017|
VGB|2016|
VGB|2015|
VGB|2014|
VGB|2013|
VGB|2012|
VGB|2011|
VGB|2010|
VGB|2009|
VGB|2008|
VGB|2007|
VGB|2006|
VGB|2005|
VGB|2004|
VGB|2003|
VGB|2002|
VGB|2001|
VGB|2000|
VGB|1999|
VGB|1998|
VGB|1997|
VGB|1996|
VGB|1995|
VIR|2024|
VIR|2023|
VIR|2022|
VIR|2021|
VIR|2020|
VIR|2019|
VIR|2018|
VIR|2017|
VIR|2016|
VIR|2015|
VIR|2014|
VIR|2013|
VIR|2012|
VIR|2011|
VIR|2010|
VIR|2009|
VIR|2008|
VIR|2007|
VIR|2006|
VIR|2005|
VIR|2004|
VIR|2003|
VIR|2002|
VIR|2001|
VIR|2000|
VIR|1999|
VIR|1998|
VIR|1997|
VIR|1996|
VIR|1995|
WSM|2024|29.0207314789872
WSM|2023|36.0680837032175
WSM|2022|32.187971798949
WSM|2021|35.2314181058421
WSM|2020|33.1905048867063
WSM|2019|33.6506492980512
WSM|2018|33.1401642944483
WSM|2017|32.1825880825996
WSM|2016|35.4648827223798
WSM|2015|35.8616376044544
WSM|2014|37.3331843934814
WSM|2013|9.01812018037557
WSM|2012|40.299132906469
WSM|2011|37.1493303117706
WSM|2010|14.6447083760345
WSM|2009|31.7413750566996
WSM|2008|
WSM|2007|
WSM|2006|
WSM|2005|
WSM|2004|
WSM|2003|
WSM|2002|
WSM|2001|
WSM|2000|
WSM|1999|
WSM|1998|
WSM|1997|
WSM|1996|
WSM|1995|
XKX|2024|33.9651432750713
XKX|2023|33.9456293075627
XKX|2022|35.2326459658665
XKX|2021|35.9511804344753
XKX|2020|33.4061275308265
XKX|2019|34.5581995450224
XKX|2018|36.2945421291487
XKX|2017|34.6926494889605
XKX|2016|33.5220002547509
XKX|2015|30.4324686404239
XKX|2014|27.8460008694681
XKX|2013|29.9978585507713
XKX|2012|31.9017216861076
XKX|2011|36.0573444918945
XKX|2010|33.1284870466064
XKX|2009|32.619616274023
XKX|2008|37.2836774320662
XKX|2007|
XKX|2006|
XKX|2005|
XKX|2004|
XKX|2003|
XKX|2002|
XKX|2001|
XKX|2000|
XKX|1999|
XKX|1998|
XKX|1997|
XKX|1996|
XKX|1995|
ZMB|2024|23.7884862636697
ZMB|2023|31.4450686240954
ZMB|2022|26.980508150543
ZMB|2021|31.3669178305336
ZMB|2020|32.2448509806584
ZMB|2019|39.2619086467844
ZMB|2018|38.5885582958265
ZMB|2017|41.0018208583077
ZMB|2016|38.2062329128451
ZMB|2015|42.8051164515408
ZMB|2014|34.0692641856177
ZMB|2013|33.8029886804422
ZMB|2012|31.5179510511994
ZMB|2011|32.889211245159
ZMB|2010|29.8775153023967
ZMB|2009|
ZMB|2008|
ZMB|2007|
ZMB|2006|
ZMB|2005|
ZMB|2004|
ZMB|2003|
ZMB|2002|
ZMB|2001|
ZMB|2000|
ZMB|1999|
ZMB|1998|
ZMB|1997|
ZMB|1996|
ZMB|1995|
```

