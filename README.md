# 👋 Hi, I'm Francisco González!

**Biomedical Engineer | Bioinformatics & Biostatistics | Scientific Computing**

I am a biomedical engineer and bioinformatician working at the intersection of biomedical research, omics data analysis, machine learning, and scientific computing.

My background combines biomedical engineering with bioinformatics and biostatistics, allowing me to work from understanding a biological or technical problem to designing reproducible computational analyses.


## 🔬 Main interests

- 🧬 Transcriptomics, single-cell RNA-seq and multi-omics analysis
- 📊 Statistical modelling and biomedical data analysis
- 🤖 Machine learning and deep learning for biomedical applications
- ⚙️ Reproducible scientific workflows and data pipelines
- 🖥️ Linux, containers and HPC environments


## 🚀 Featured projects

### 🧬 Single-cell RNA-seq analysis of colorectal cancer

[**TFM repository**](https://github.com/frgonzanu/TFM)

End-to-end analysis of public colorectal cancer *scRNA-seq* data, from raw sequencing files to candidate gene prioritisation for lymph-node metastasis.

Main steps:

- FASTQ preprocessing and quality control
- STAR alignment and count generation
- SingleCellExperiment-based analysis
- QC, normalisation and batch correction
- PCA, UMAP, t-SNE and clustering
- Cell-type annotation
- Patient-aware pseudobulk differential expression with `edgeR`
- Multivariate modelling with `sPLS-DA`
- GSEA and pathway enrichment
- PROGENy and DoRothEA activity inference
- Exploratory scVI and LDVAE analyses

**Technologies:**  
`R` · `Bioconductor` · `Python` · `Bash` · `STAR` · `edgeR` · `SingleR` · `mixOmics` · `clusterProfiler` · `scvi-tools`

---

### ⚙️ Reproducible scRNA-seq preprocessing with Snakemake

[→ Repository: scWorkflowCRC](https://github.com/frgonzanu/scWorkflowCRC)

Refactoring of the preprocessing stage of my MSc thesis into a reproducible and HPC-oriented **Snakemake workflow** using real GSE97693 colorectal cancer scRNA-seq data.

The workflow includes:

- ENA metadata retrieval and validated FASTQ downloads
- MD5 integrity checks and resumable transfers
- Raw and post-trimming FastQC
- Protocol-specific Cutadapt preprocessing
- GRCh38 / GENCODE v38 reference preparation
- STAR genome indexing and gene-level quantification
- Parallel execution on SLURM-based HPC environments
- Automated generation of the gene-by-cell count matrix
- MultiQC reporting
- Conda-based software environments and configuration validation

The project illustrates the transition from sequential Bash/Python preprocessing scripts to a dependency-aware, reproducible scientific workflow suitable for local and HPC execution.

**Technologies:** Snakemake, Python, Bash, STAR, Cutadapt, FastQC, MultiQC, Conda, SLURM, ENA

---

### 📊 Interactive omics data visualisation

[**API_omic-visualization**](https://github.com/frgonzanu/API_omic-visualization)

R Shiny application for exploratory omics data analysis, including interactive heatmaps and correlation matrices.

A deployed version is available through shinyapps.io.

**Technologies:**  
`R` · `Shiny` · `ComplexHeatmap` · `corrplot`

---

### 🧮 Synthetic disease population modelling

[**Disease_artif_population_ORs**](https://github.com/frgonzanu/Disease_artif_population_ORs)

Simulation of synthetic populations using epidemiological risk factors and published odds ratios to explore disease-risk distributions and predictive modelling strategies.

**Technologies:**  
`R` · `Statistical modelling` · `Epidemiological data analysis`


## 🖥️ Scientific computing

Alongside omics analysis, I currently work on computational biomedical research involving **machine learning and deep learning applied to biomedical engineering and bioprinting**.

My current technical work includes:

- Python and PyTorch
- Computer vision and video classification
- Hyperparameter optimisation
- Linux-based scientific computing
- Docker and Apptainer/Singularity
- SLURM-based HPC environments
- GPU/CUDA workloads
- Git-based development
- Reproducible data-processing workflows
- Snakemake

I am particularly interested in bridging bioinformatics, reproducible workflows and scalable scientific computing.

## 🛠️ Technical stack

### Bioinformatics & statistics

`R` · `Bioconductor` · `SingleCellExperiment` · `edgeR` · `SingleR` · `clusterProfiler` · `mixOmics` · `scVI`

### Programming & data

`Python` · `R` · `Bash` · `Git`

### Machine learning and deep learning

### Scientific computing

`Linux` · `Docker` · `Apptainer/Singularity` · `SLURM` · `CUDA` · `Snakemake`



## 📄 Publications

- [**Menstrual blood-derived mesenchymal stromal cells: impact of preconditioning on the
cargo of extracellular vesicles as potential therapeutics**, MA de Pedro et al. (2023)](https://doi.org/10.1186/s13287-023-03413-5)

- [**Menstrual Blood-Derived Mesenchymal Stromal Cell Secretome Modulates Macrophage Polarization in a Preconditioning-Dependent Manner**, MA de Pedro et al. (2026).](doi.org/10.3389/fcell.2025.1691010)


My contributions include biomedical data analysis, proteomics and transcriptomics interpretation, statistical analysis and scientific research.


## 🏛️ Conferences

- **Systems biology applied to ovarian cancer: a new therapeutic strategy using extracellular vesicles derived from menstrual blood stromal cells** (Spanish: Biología de sistemas aplicada al cáncer de ovario: nueva estrategia terapéutica con vesículas extracelulares derivadas de células estromales de sangre menstrual), María de los Ángeles de Pedro et al. Presentation at the Congress of the Spanish Society of Surgical Research (SEIQ 2025).

- **Comparison of ergonomics between robotic and conventional surgery: a study of muscle activity and body posture**, M. Kappel et al. (2024).

- **Objective analysis of ergonomics in robotic microsurgery**, M. Kappel et al. (2024).

- **Objective analysis and comparison of stress level during robotic and conventional laparoscopic surgery**, M. J. Pérez Salazar et al. (2024).

- **Analysis of stress during surgical procedures using conventional and robotic laparoscopy** (Spanish: Análisis del estrés durante procedimientos quirúrgicos mediante laparoscopia convencional y robótica), M. J. Pérez Salazar (2024), Presentation at the XLI Annual Congress of the Spanish Society of Biomedical Engineering (CASEIB 2023).

- **Proinflammatory priming of menstrual blood-derived mesenchymal stromal cells alters the protein cargo of their extracellular vesicles enhancing their immunosuppressive properties**, María Ángeles De Pedro et al. Poster in 44th Conference of Spanish Society of Immunology (SEI2023).

- **Effect of Experimental Microsurgical Anastomosis Training on Procedure Quality and Surgeon Ergonomics** (Spanish: Efecto del entrenamiento de la anastomosis microquirúrgica experimental en la calidad del procedimiento y la ergonomía del cirujano), Francisco M. González Nuño et al. (CASEIB2022).

 

## 🎓 Background

- **MSc Bioinformatics & Biostatistics** — Universitat Oberta de Catalunya
- **MSc Biomedical Engineering** — Universitat de Barcelona
- **BSc Industrial Electronic Engineering** — Universidad de Granada

---

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/francisco-manuel-gonzalez-nuno/)
- 
- [Email](mailto:paco.gonzaln@gmail.com)
