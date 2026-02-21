# 🧬 Viral Genome Compression Using BWT, RLE and Zstandard (ZSTD)

## 📌 Overview
This project implements an advanced genome compression pipeline for viral DNA sequences using a hybrid combination of classical bioinformatics transformations and modern compression algorithms. The system processes FASTA genomic sequences and applies multiple compression strategies including BWT, RLE and Zstandard (ZSTD) to optimize storage efficiency and computational performance.

The implementation is designed for experimental analysis of genomic data compression using real viral sequence datasets.

---

## 🎯 Objective
- Efficient compression of viral genome sequences from FASTA files
- Reduce redundancy in biological sequence data
- Apply hybrid compression techniques for improved storage efficiency
- Benchmark different compression strategies on genomic sequences

---

## 🧬 Compression Pipeline (Actual Implementation)
The IBS2 notebook implements multiple compression approaches:

### 1. Zstandard (ZSTD) Compression
- High-performance modern compression algorithm
- Used for compressing transformed genome sequences
- Provides better compression ratio and speed compared to traditional methods

### 2. Burrows-Wheeler Transform (BWT) + ZSTD
- Rearranges genomic sequences for better compressibility
- Followed by ZSTD compression for efficient storage

### 3. Run-Length Encoding (RLE) + ZSTD
- Compresses repetitive nucleotide patterns
- Further optimized using Zstandard compression

### 4. Delta Encoding + ZSTD
- Reduces sequence redundancy before compression
- Improves compression effectiveness on biological data

---

## 📊 Dataset
- File: `sequences.fasta`
- Format: FASTA (Biological sequence format)
- Type: Viral genomic sequences (DNA)
- Processing: Sequence parsing, transformation and compression analysis

---

## 📁 Project Structure
Viral-Genome-Compression/
│
├── IBS2.ipynb # Main hybrid compression pipeline (BWT + RLE + ZSTD)
├── sequences.fasta # Input viral genome sequences (FASTA format)
└── README.md

---

## 🛠️ Technologies Used
- Python  
- Zstandard (zstd)  
- NumPy  
- Pandas  
- Matplotlib  
- TQDM  
- Biopython (FASTA processing)  
- File I/O  
- Bioinformatics Algorithms  

---

## 🔬 Key Features
- Hybrid genome compression pipeline (Classical + Modern methods)
- FASTA sequence parsing and preprocessing
- ZSTD-based high-performance compression
- BWT and RLE transformation experiments
- Compression performance tracking and analysis
- Reproducible notebook-based workflow

---

## 🚀 How to Run
1. Install dependencies:
```bash
pip install zstandard numpy pandas matplotlib tqdm biopython
