# Adaptive Remainder Modulo m Data Hiding

**Manuscript ID:** IEEE LATAM Submission ID: 9901 
**Authors:**
- Alexander Chefranov
- Gürcü Öz

---

## 📁 Included Scripts

This repository contains all scripts required to reproduce the simulation and numerical results presented in the article.

| Script | Related Figure(s) | Description |
|--------|-------------------|-------------|
| `Make_stegos_30092023.m` | Fig. 3 | Makes stego-images for the cover images from the UCID v2 dataset using a particular method selected from a drop-down list for SPAM analysis. |
| `Calc_SPAM_21092018.m, spam686.m` | Fig. 3 | Calculate SPAM features. |
| `Make_Table_Train_23092018.m,   Majke_TT1_25092023.m` | Fig. 3 | Prepare a table TT of SPAM features of the cover- and stego-images for the next training and testing, and split TT into TT1 for training and TT2 for testing. |
| `de_calc_28092023.m`|    Fig. 3 |  Calculates detection error (DE) from the results of testing.|
| `SPAManalInv15102025.m` | Fig. 3 | Plots results. |
| `Readme on SPAM experiments 18042025.docx` | Fig. 3 |  Contains description of how to use code scripts related to SPAM experiments results shown in Fig.3. |
| `adaptiveLSB29092023.m` | Fig. 3, 4 | Contains code of ARM-m. |
| `stc_embed_29032021.m', 'calc_syndrome.m',create_code_from_submatrix.m,create_from_submatrix.m,dualviterbi.m` | Fig. 3 | Contain code for STC. |
| `mlsbrevpair_embed_16072021.m` | Fig. 3 | Contains code for ALSBMR. |
| `OPAP21052021.m` | Fig. 3 | LContains code for OOPAP. |
| `Make_stegos_11102025.m` | Fig. 4 | Contains code for CNN experiments. |
| `Readme on CNN experiments.docx` | Fig. 4 | Contains detailed description of how to conduct CNN-related experiments. |
| `mainARM_RSsteganalysis21102025.m,   RSsteganalysis30042018.m` | Fig. 5 | Contain RS-steganalysis-related scripts. |
| `Readme on RS steganalysis.docx` | Fig. 5 | Contains detailed description of how RS-steganalysis was made. |

---

## 📂 Required Files

- `ucid.v2.tar.gz`: contains a part of UCID v2 dataset used in the
  SPAM-related experiments. It shall be extracted to 'C:\\Temp\\ucid.v2.
- `BOSSbase 1.01`: from DDE lab site <https://dde.binghamton.edu/download/>
  used in CNN-related experiments shall be located in
  \'C:\\Temp\\Boss1.01\.

---

## 💻 Requirements

- MATLAB R2018b or later.
- No additional toolboxes are required.

---

## ✉️ Contact

For questions or replication of results:  
gurcu.oz@emu.edu.tr, alexander.chefranoc@emu.edu.tr

