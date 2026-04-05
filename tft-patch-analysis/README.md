# TFT Patch Meta Analysis (16.1c vs 16.2)

## Project Overview
This project analyzes how the Teamfight Tactics (TFT) meta changed from Patch 16.1c to Patch 16.2.

The main focus is to examine whether Patch 16.2 reduced the dominance of previously strong compositions, especially Piltover T-Hex, and whether the overall meta became less concentrated after the balance changes.

## Objectives
- Compare the top team compositions in Patch 16.1c and Patch 16.2
- Analyze changes in pick rate, average placement, top 4 rate, and win rate
- Measure whether the meta became less concentrated after the patch
- Connect data results with Riot’s official patch notes

## Tools Used
- Python
- pandas
- matplotlib
- Jupyter Notebook

## Dataset
The dataset was manually collected from TFT top composition statistics for Patch 16.1c and Patch 16.2.

Variables used:
- patch
- comp
- pick_rate
- avg_placement
- top4_rate
- win_rate

## Key Findings
- Piltover T-Hex was one of the leading compositions in Patch 16.1c, but it no longer appeared in the top tracked compositions in Patch 16.2.
- Meta concentration decreased after the patch.
- Ionia Yunara also became less dominant after direct nerfs.
- Some alternative compositions such as Yordle Veigar and Bilgewater Value became more popular.

## Outputs
- Top 10 compositions by pick rate in Patch 16.1c
- Top 10 compositions by pick rate in Patch 16.2
- Meta concentration comparison between the two patches
- Pick rate change for shared compositions
- Shared composition comparison table

## Project Structure
tft-patch-analysis/
├── README.md
├── data/
│   └── patch_data.csv
├── notebooks/
│   └── tft_patch_analysis.ipynb
├── output/
│   ├── top10_pickrate_16_1c.png
│   ├── top10_pickrate_16_2.png
│   ├── meta_concentration_comparison.png
│   └── shared_comp_comparison.csv
└── report/
    └── TFT_Patch_Meta_Analysis.pdf

## Conclusion
This project suggests that Patch 16.2 successfully reduced the dominance of several overpowered strategies and created a more diverse meta compared to Patch 16.1c.