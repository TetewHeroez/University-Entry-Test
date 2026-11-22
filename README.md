# 🎓 University Entry Test Archive

Arsip komprehensif naskah soal, dokumen LaTeX, dan pembahasan ujian masuk program pascasarjana (Master / Graduate School) bidang Matematika dan Sains Komputasi.

## 🏛️ Universitas & Program

### 1. Kyoto University (Graduate School of Science / Informatics)
- **Tahun**: 2022 – 2027
- **Tingkat Soal**:
  - `Basic` (Linear Algebra, Calculus, Differential Equations, Basic Analysis)
  - `Advanced` (Abstract Algebra, Complex Analysis, Topology, Geometry, Applied Mathematics)

### 2. The University of Tokyo (Graduate School of Mathematical Sciences / IST)
- **Tahun**: 2022 – 2026
- **Format**: Naskah LaTeX (`.tex`) dan dokumen siap cetak (`.pdf`)
- **Topik**: Ujian spesialisasi matematika tingkat lanjut.

### 3. Institut Teknologi Sepuluh Nopember (Magister Matematika ITS)
- **Materi**: Tes Tulis Seleksi Masuk Program Magister (S2) Matematika ITS.
- **Format**: LaTeX source (`.tex`) dan compiled PDF (`.pdf`).

## 📁 Struktur Direktori

```
University Entry Test/
├── Graduate School KyotoU/
│   ├── 2022/ (Basic & Advanced)
│   ├── 2023/
│   ├── 2024/
│   ├── 2025/
│   ├── 2026/
│   └── 2027/
├── Graduate School UTokyo/
│   ├── 2022/ (UTokyo 2022.pdf / .tex)
│   ├── 2023/
│   ├── 2024/
│   ├── 2025/
│   └── 2026/
└── Magister ITS/
    └── Tes Tulis S2 (.tex & .pdf)
```

## 🛠️ Persyaratan Kompilasi

Naskah LaTeX dikompilasi menggunakan distribusi TeX standar (`pdfLaTeX` atau `XeLaTeX`):
```bash
latexmk -pdf filename.tex
```
