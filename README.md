# Cancer-Biomarker-Discovery-Reproducible-Study-Based-on-TNMplot
This project identifies and ranks cancer biomarkers by analyzing RNA-seq data from breast, lung, and colon cancer cohorts in TCGA. Based on TNMplot's methodology, it focuses on differential gene expression, statistical analysis, and visualization to uncover key biomarkers for therapeutic development

## Background
Cancer development is driven by genetic lesions, resulting from both external and hereditary factors, that lead to significant changes in gene expression. These alterations can produce cancerous cells, and understanding how specific genes behave in normal versus tumor tissues is crucial for identifying biomarkers and therapeutic targets.

However, the vast amount of genomic data available, such as from The Cancer Genome Atlas (TCGA) and Genotype-Tissue Expression (GTEx), is often overwhelming and not neatly organized. TNMplot, a tool that offers a curated, accessible dataset of gene expression across multiple cancer types, helps address this challenge by highlighting genes with altered expression in tumor tissues compared to normal counterparts.

Our study aims to replicate the findings from TNMplot by applying a reproducible bioinformatics pipeline based on their approach. By leveraging public datasets, we seek to identify key biomarkers in various cancer cohorts, with a specific focus on breast, colon, and lung cancers. We employ traditional statistical methods like differential expression analysis as well as modern machine learning techniques to rank and validate biomarkers. The focus on reproducibility ensures that the results can be independently verified, laying a strong foundation for future research and potential therapeutic development.

## Installation/Setup
Clone this repository and install dependencies:
```bash
git clone https://github.com/tera90223/Cancer-Biomarker-Discovery.git
cd Cancer-Biomarker-Discovery
pip install -r requirements.txt
```

## Usage


## Project Structure
``` bash
├── data/                  # Contains raw data files (e.g., TCGA RNA-seq data)
├── scripts/               # Python/R scripts for analysis
├── results/               # Generated results (plots, statistics, etc.)
├── README.md              # Project overview
└── requirements.txt       # Python dependencies
```

## Contributing
## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments 
- __The Cancer Genome Atlas (TCGA) for__ providing the dataset used in this project.
- __DESeq2__ for differential expression analysis.
- __AnnotationDbi__ for gene annotation.
- __TNMplot creators__ for providing the tool and methodology that guided this study.
- __Dr. Andrej Savol, and Northeastern University__ for their support throughout the project.
- __My team__ for their contributions and insights.

## References
Bartha, Á., & Győrffy, B. (2021, March 5). TNMplot.com: A web tool for the comparison of gene  expression in normal, tumor and metastatic tissues. MDPI. https://www.mdpi.com/1422-0067/22/5/2622 
