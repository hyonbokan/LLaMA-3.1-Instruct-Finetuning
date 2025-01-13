# LLaMA 3.1-Instruct Finetuning

## Unsloth Environment Setup and Dependencies
Finetuning process uses a Conda environment with specific dependencies to ensure compatibility with the **unsloth** library, **PyTorch**, and **CUDA**.
Follow the instructions below to set up and replicate the development environment.

## Environment Overview

- **Environment Name**: `unsloth_env`
- **Python Version**: `3.10.16`
- **Key Libraries**:
  - **PyTorch Version**: `2.2.0` (with CUDA 12.1)
  - **CUDA Version**: `12.1`
  - **Unsloth Version**: `2024.12.12`
  - **Unsloth Zoo Version**: `2024.12.7`

### Step 1: Clone the Repository
Clone the project repository:
```bash
git clone https://github.com/hyonbokan/LLaMA-3.1-Instruct-Finetuning.git
cd LLaMA-3.1-Instruct-Finetuning
```

### Step 2: Set Up Conda Environment
1. Create the environment using the included .yaml file:
```bash
conda env create --file unsloth_env.yaml
```

2. Activate the environment:
```bash
conda activate unsloth_env
```

## Dependencies
The .yaml file contains all necessary dependencies, including:
- Python version
- Conda-installed libraries
- Pip-installed packages (captured under the pip section in the file)
