# Convert Marshal ↔ PYC

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Language](https://img.shields.io/badge/language-Python-blue.svg)]()
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/KhanhNguyen9872/Convert_Marshal-PYC.svg)](https://github.com/KhanhNguyen9872/Convert_Marshal-PYC/issues)

</div>

## 🌟 Introduction

**Convert_Marshal-PYC** is a utility tool designed to convert between Python `.pyc` files (compiled bytecode) and Marshal dumps. It is particularly useful for reverse engineering, debugging, or analyzing Python bytecode.

## ✨ Key Features

-   **🔄 Bidirectional Conversion**:
    -   **PYC to Marshal**: Extracts code objects from `.pyc` files and generates a script using `marshal.loads`.
    -   **Marshal to PYC**: Reconstructs valid `.pyc` files from marshal dumps by attaching the correct magic numbers.
-   **🐍 Multi-Version Support**: Integrated magic numbers for Python versions 3.6 through 3.14.
-   **🛠️ Automatic Validation**: Checks file size and format before processing to ensure data integrity.

## 🚀 Getting Started

### Prerequisites

-   Python 3.x installed on your system.

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/KhanhNguyen9872/Convert_Marshal-PYC.git
    cd Convert_Marshal-PYC
    ```

### Usage

1.  **Run the tool**:
    ```bash
    python cv_marshal_pyc.py
    ```
2.  **Input File**: When prompted `>> Input file marshal/PYC:`, enter the path to your target file.
3.  **Check Output**:
    -   Input `.pyc` ➔ Output `_marshal.py` (Script capable of executing the bytecode)
    -   Input Marshal dump ➔ Output `_pyc.pyc` (Compilable .pyc file)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## ✍️ Author

**Nguyễn Văn Khánh** (KhanhNguyen9872)

-   Facebook: [KhanhNguyen9872](https://fb.me/khanh10a1)

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
