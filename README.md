# NGS Data Structures in R

> A visual guide to `RangedSummarizedExperiment` and the Bioconductor ecosystem — course notes rendered with [Quarto](https://quarto.org/) and published via GitHub Pages.

## 📖 Read the notes

👉 **[https://YOUR-USERNAME.github.io/YOUR-REPO-NAME](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME)**

## Contents

| Chapter | Topic |
|---------|-------|
| 1 — Structure | Anatomy of an RSE: assays, rowRanges, colData, rowData, metadata |
| 2 — Access & Manipulation | Accessors, subsetting, merging |
| 3 — Workflow | From FASTQ to RSE via featureCounts / tximeta / DESeq2 |

## 🚀 Render locally

```bash
# 1. Install Quarto → https://quarto.org/docs/get-started/
# 2. Install R packages
Rscript -e 'install.packages("BiocManager"); BiocManager::install(c("SummarizedExperiment","GenomicRanges","tximeta","DESeq2"))'
# 3. Render
quarto render
# 4. Preview
quarto preview
```

Output goes to the `docs/` folder (configured for GitHub Pages).

## 🌐 Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages → Source** and select `Deploy from a branch`, branch `main`, folder `/docs`.
3. Click Save — your site will be live in ~1 minute.

Or use the included GitHub Actions workflow (`.github/workflows/publish.yml`) for automatic deployment on every push.

## License

CC BY 4.0
