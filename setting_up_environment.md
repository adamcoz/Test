# Analytics Environment Setup Guide

This document outlines the steps to set up your analytics environment using:
- **VS Code** (Code Editor)
- **GitHub** (Version and Environment Control)
- **Miniconda** (Python Distribution)
- **Poetry** (Dependency Tracking)

Additionally, it includes best practices for utilizing this setup effectively.

---

## **Setup Steps**

### **1. Prerequisites: Install Required Applications**
Ensure the following applications are downloaded and installed before proceeding:
- **[Microsoft Visual Studio Code](https://code.visualstudio.com/)**
- **[Python](https://www.python.org/downloads/)**
- **[Miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)**
- **[Git Bash](https://git-scm.com/downloads)**

> **Note:** During Miniconda installation, ensure "Add Miniconda to my PATH environment variable" is selected. Verify the installation by running:
> ```bash
> conda --version
> ```    
> Miniconda: is a package and environment management system that simplifies dependency installation, version control, and environment isolation, ensuring compatibility across projects    
> Git: is a version control system that tracks changes in code, enabling collaboration and efficient management of project histories across different versions and contributors.   
> Git Bash: is a command-line interface that provides a Unix-like environment for Windows, allowing users to run Git commands and use shell commands that are typically available on Linux and macOS.        
---

### **2. Set Up Conda with Poetry Inside It**
1. Create a specific Conda environment:
   ```bash
   conda create -n poetry_env python=3.9 -y
   ```
2. 


