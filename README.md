# The Art of Value

Information Visualization final project exploring print-auction records through colorfulness, SVD entropy, artists, printmaking techniques, creation periods, and recorded sale prices.

## Dataset

- `dataset/auction_results_color_svd.csv`: processed auction records with colorfulness and SVD entropy features.
- `dataset/results_2024_05_11.xlsx`: source workbook, stored with Git LFS.

Source: Patryk Mauer, [Art auction result of prints (RepOD)](https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/AEQF8C).

## Clone

Install [Git LFS](https://git-lfs.com/) before cloning to download the full workbook:

```sh
git lfs install
git clone https://github.com/Evawangyw/art-of-value.git
cd art-of-value
git lfs pull
```

## Sync changes

```sh
git add .
git commit -m "Update project data or visualization"
git push
```

The `guideline/` folder and macOS metadata are excluded from version control. Git LFS manages Excel files in `dataset/`; the CSV is tracked directly by Git.
