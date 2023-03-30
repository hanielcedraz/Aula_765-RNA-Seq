# Introduction to bioinformatics

Open the file <a href="https://github.com/hanielcedraz/RNA-Seq_Course/blob/main/rnaSeqAnalysis.ipynb" target="_blank">rnaSeqAnalysis.ipynb</a> and click on "Open In Colab" button to follow the tutorial in Google Colab.



<!---
```
https://github.com/hanielcedraz/RNA-Seq_Course/blob/main/rnaSeqAnalysis.ipynb">rnaSeqAnalysis.ipynb
```
-->



## Downloading fastq files
Download the files in <a href="https://github.com/hanielcedraz/RNA-Seq_Course/tree/main/00-Fastq" target="_blank">00-Fastq</a> 


## Loading conda env
Download the file <a href="https://github.com/hanielcedraz/RNA-Seq_Course/blob/main/curso_RNA-Seq.yaml" target="_blank">curso_RNA-Seq.yaml</a>  

Run:
´´´bash
# Download Miniconda installer
wget https://repo.anaconda.com/miniconda/Miniconda3-py37_4.11.0-Linux-x86_64.sh

# Activate conda base env
conda activate base


# Install miniconda
bash Miniconda3-py37_4.11.0-Linux-x86_64.sh



# Update conda to the latest version if needed
conda update conda



# Display active channels
conda config --show channels


# Create stgen env from yaml
conda env create -f curso_RNA-Seq.yaml

´´´
