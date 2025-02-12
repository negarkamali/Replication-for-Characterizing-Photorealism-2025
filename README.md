# Replication for Characterizing Photorealism (2025 Paper)

This repository contains the replication materials for the **"Characterizing Photorealism"** paper. The repository includes the necessary code and instructions to replicate the analysis presented in the paper.

## Data and Stimuli

- The **stimuli** and **data.csv** are available on **[Zenodo](https://zenodo.org/records/14852020?preview=1&token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjkwOTdlNDNhLTQ2ODgtNGEzMC1hNDI3LTRiNzIwNzg5YTE3NyIsImRhdGEiOnt9LCJyYW5kb20iOiJmNTU4N2ZlYzEwMDgwMzgwMTIwNGYyYjUwYjZiNzlmYyJ9.lP7a_PYhXIQCNzbSa3l4ePTY5TJKEXT5Fq5mddNvIUnhRxUccVb869X6KX42VpLiMZ94hG-_EUWaH_1nPRNueQ)**.  


- Open and run jupyter notebook CHI2025_feb.ipynb

## Data Files

This repository contains several CSV files used in the analysis. Below is a description of each:

### **1. Image Metadata (`image_metadata.csv`)**
- Contains filenames of all images used in the experiment.
- Indicates whether each image is **real** or **AI-generated**.

### **2. User Guesses (`data.csv`)**
- Contains **participant responses** from the online experiment.
- Includes 749,828 user entries with details such as:

### **3. Artifact Annotations (`artifact_annotations.csv`)**
- Contains images and their associated **artifact annotations**.
- Includes a description of **each artifact type** and the reasoning behind the classification.

### **4. Human Curation (`human_curation.csv`)**
- Evaluates the **effect of human curation** on image accuracy.


### **5. Classified Comments (`classified_comments_chunked.csv`)**
- Contains **participant comments** collected from the online experiment.
- Each comment is classified into **one or more artifact categories** based on the themes identified by GPT-3.5 Turbo.


If you use this dataset or code, please cite:

@inproceedings{kamali2025photorealism,
  author    = {Negar Kamali and Karyn Nakamura and Aakriti Kumar and Angelos Chatzimparmpas and Jessica Hullman and Matthew Groh},
  title     = {Characterizing Photorealism and Artifacts in Diffusion Model-Generated Images},
  booktitle = {CHI Conference on Human Factors in Computing Systems (CHI '25)},
  year      = {2025},
  publisher = {Association for Computing Machinery},
  address   = {Yokohama, Japan},
  doi       = {10.1145/3706598.3713962},
  isbn      = {979-8-4007-1394-1},
  keywords  = {photorealism, diffusion models, generative AI, synthetic media, deepfakes, misinformation}
}


