# KocG-nelLAB_FGFR4LAM

### **Overview**
This repository contains data and resources from the study: *“FGFR4 p.Gly388Arg polymorphism in PBMCs of LAM Patients: A Potential Systemic Driver of Disease.”* The study investigates the potential role of FGFR4 mutations in disease progression among LAM patients, providing genomic, clinical, and methodological insights.

---

## **Contents**

1. **Raw Data**:
   - Processed BAM files for PBMC samples from seven sporadic LAM patients, aligned to the GRCh37 (hg19) reference genome.
   - Corresponding `.bai` index files for BAM files.

2. **Metadata**:
   - Patient metadata including sample identifiers, clinical characteristics, and sequencing parameters (`sample_metadata.tsv`).

3. **Processed Data**:
   - Allelic frequencies of FGFR4 mutations derived from NGS analysis.

---

## **Methodology**

### **Sample Collection**
Peripheral blood mononuclear cells (PBMCs) were isolated from seven LAM patients. Clinical data, including pulmonary function tests (PFTs), treatment regimens, and disease severity, were collected. Diagnosis followed ATS/ERS guidelines and was confirmed via CT scans, serum VEGF-D levels, and, in some cases, lung biopsies.

### **NGS Sequencing**
Targeted mutation analysis of PBMC DNA was performed using the Oncomine Comprehensive Assay v3 (Thermo Fisher). Sequencing was carried out on an Ion Torrent platform, assessing 160 cancer-related genes. Data were processed using Ion Reporter™ software.

### **Data Processing**
- BAM files represent raw sequencing data aligned to the reference genome (GRCh37).
- Index files (`.bai`) are provided for BAM navigation.
- Variant calls and allelic frequencies were derived and validated against control samples.

### **Key Metrics**
- FGFR4 p.Gly388Arg mutation frequencies ranged from 49% to 99%.

---

## **Usage Instructions**

### **File Formats**
- **BAM Files**: Aligned sequencing reads. Compatible with genome browsers such as [IGV](https://software.broadinstitute.org/software/igv/).
- **BAI Files**: Index files for quick genomic region access within BAM files.
- **Metadata**: Tab-delimited `.tsv` file with sample IDs, clinical data, and sequencing quality metrics.

### **Analysis Tools**
- Use [samtools](http://www.htslib.org/) or [bcftools](http://samtools.github.io/bcftools/) for BAM file analysis.
- Analyze variant frequencies with Ion Reporter™ or alternative bioinformatics pipelines.

---

## **Data Access and Attribution**
Please cite the following publication when using this data:
Koc-Gunel S., Ryan A. L., Winter M., Wagner T.O.F. *FGFR4 p.Gly388Arg polymorphism in PBMCs of LAM Patients: A Potential Systemic Driver of Disease.*

For inquiries, contact:
**Sinem Koc-Gunel**  
Email: koc-guenel@med.uni-frankfurt.de  

---

## **License**
This dataset is distributed under the [Creative Commons Attribution License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

## **Acknowledgements**
This study was supported by the German Research Foundation (DFG, Grant No. KO5803/2-1), the Federal Ministry for Research and Education Germany (BMBF, Grant No. 01EO2102), and departmental funds from the Department of Internal Medicine, Goethe University Frankfurt.
