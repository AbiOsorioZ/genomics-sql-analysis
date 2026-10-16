# Global Genomics & Scientific Tools Analysis (NCBI SRA)

![Dashboard Preview](ruta_de_tu_imagen_o_captura_aqui.png)

## Project Overview
Exploratory data analysis of the Sequence Read Archive (SRA) from NCBI, the world's largest public repository for genomic sequencing data. This project bridges biotechnology and data analytics by extracting, cleaning, and querying large-scale datasets via Google BigQuery to uncover global trends in research investments, sequencing technologies, and dominant organisms.

## Key Questions Explored
* **What are the most heavily sequenced organisms?** See [01_organismos_mas_secuenciados.sql](01_organismos_mas_secuenciados.sql)
* **What are the most commonly used assay/sequencing types?** See [02_tecnica_mas_utilizada.sql](02_tecnica_mas_utilizada.sql)
* **Which sequencing platforms dominate the industry?** See [03_plataformas_secuenciacion.sql](03_plataformas_secuenciacion.sql)
* **Which countries generate the highest volume of genomic data?** See [04_pais_mas_datos.sql](04_pais_mas_datos.sql)
* **How has the volume of sequencing data evolved over time?** See [05_evolucion_volumen.sql](05_evolucion_volumen.sql)
* **Which bioprojects have the largest associated sample sizes?** See [06_bioproyectos_top.sql](06_bioproyectos_top.sql)

## Tools & Technologies
* **Google BigQuery & SQL:** Data extraction, querying, and exploratory data analysis using public datasets (`nih-sra-datastore.sra.metadata`).
* **Power BI:** Interactive data visualization and dashboard design for executive reporting.
* **Domain Knowledge:** Applied biotechnology, genomics, NGS (Next-Generation Sequencing) platforms, and public health data interpretation.

## Key Findings
* **The Illumina Monopoly:** Illumina leads global sequencing with ~39.6M records—nearly 36 times more than its closest competitor, Oxford Nanopore (~1.1M), proving its status as the absolute industry standard for NGS.
* **Pandemic Impact on Research:** Global sequencing volume experienced a steep, sustained surge peaking in 2022 (~6.5M records), heavily driven by COVID-19 genomic surveillance (such as the COG-UK consortium dataset).
* **Top Organisms & Techniques:** *Homo sapiens* leads sequencing volume (~8.2M records), closely followed by SARS-CoV-2 (~7.6M). Amplicon sequencing dominates diagnostic and targeted applications (~18M records).
* **Geographic Concentration:** Genomic research investment and data generation remain heavily centralized in a few high-income countries, primarily the United States and the United Kingdom.

## Dashboard & Interactive Visualizations
The interactive Power BI dashboard integrates yearly evolution trends, platform market share, and top organism distributions into a clean, executive one-pager designed for quick technical assessment.

---
**Author:** Abigail Osorio ([abiosorioz.04@gmail.com](mailto:abiosorioz.04@gmail.com))
