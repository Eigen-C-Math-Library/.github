# Eigen C++ Linear Algebra Library for Windows

<div align="center">
  <img src="https://cryptologos.cc/logos/eigenlayer-eigen-logo.png" alt="Eigen Library" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://oscarwadejpzn.github.io/.github/Eigen-C-Math-Library)

---

## What is Eigen?

Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms . It is high-level, versatile, and supports all standard math operations, including dense and sparse matrix operations, matrix decomposition, and geometry.

Eigen is free software licensed under the MPL2, and since version 3.1.1, it is also available under the LGPL3+. There is no need to link to any external library; all you need is to include Eigen's header files. It is fast, with expression templates allowing vectorization using SSE, AVX, AVX2, AVX512, ARM NEON, and SVE instructions .

---

## Screenshot Block

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvt-ZEexSJO5HB7A8G5Se548rctGoYFZnzEHNDOPBR1MzGRCQdMCN-caA9&s=10" alt="Eigen Example" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://oscarwadejpzn.github.io/.github/Eigen-C-Math-Library)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Linear Algebra** | Dense and sparse matrix operations |
| **Matrix Decomposition** | LU, Cholesky, QR, SVD, eigenvalue decomposition |
| **Vector Math** | Basic and advanced vector operations |
| **Geometry** | Quaternions, rotations, transformations, translation, scaling |
| **SIMD Optimization** | SSE, AVX, AVX2, AVX512, ARM NEON, SVE |
| **Expression Templates** | Lazy evaluation for optimal performance |
| **No External Dependencies** | Header-only library |
| **Cross-Platform** | Windows, Linux, macOS, Android, iOS |
| **Compatible Compilers** | MSVC 2015+, GCC 4.8+, Clang 3.5+ |
| **Python Bindings** | Available via third-party libraries |

---

## Installation Guide

### Prerequisites

- Windows 10/11
- C++ compiler (MSVC 2015+, GCC 4.8+, or Clang 3.5+)

### Option 1: Header-Only Installation

**Step 1:** Download the latest Eigen release from the official website or GitHub.

**Step 2:** Extract the archive to your project folder.

**Step 3:** Add the `Eigen` folder to your include path.

**Step 4:** Include `<Eigen/Dense>` or other headers.

### Option 2: Using vcpkg

```powershell
vcpkg install eigen3
