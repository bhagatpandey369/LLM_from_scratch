# LLM from Scratch

This project is a hands-on guide to building a Large Language Model (LLM) from scratch, following the principles and practices outlined in the book "LLM from Scratch" by Sebastian Raschka.

## Description

This repository contains code, notebooks, and resources to accompany the book. It's designed to provide a practical understanding of how LLMs work by building one from the ground up.

## Getting Started

### Prerequisites

- Python 3.12 or higher
- `uv` package manager (or `pip`)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/bhagatpandey369/LLM_from_scratch.git
    cd LLM_from_scratch
    ```

2.  **Create a virtual environment:**

    Using `uv`:

    ```bash
    uv venv
    ```

    Using `venv`:

    ```bash
    python -m venv .venv
    ```

3.  **Activate the virtual environment:**

    On Windows:

    ```bash
    .venv\Scripts\activate
    ```

    On macOS/Linux:

    ```bash
    source .venv/bin/activate
    ```

4.  **Install the dependencies:**

    Using `uv`:

    ```bash
    uv pip install -r requirements.txt
    ```

    Using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the main script:

```bash
python main.py
```

To launch Jupyter Lab and explore the notebooks:

```bash
jupyter lab
```

## Project Structure

-   `main.py`: The main entry point of the project.
-   `chapter02.ipynb`: Jupyter notebook for Chapter 2.
-   `requirements.txt`: A list of the Python packages required for this project.
-   `pyproject.toml`: Project metadata and dependencies.
-   `data.txt`: Sample data used in the project.
-   `.gitignore`: Specifies intentionally untracked files to ignore.
-   `test.ipynb`: A notebook for testing purposes.
-   `uv.lock`: A lock file for the `uv` package manager.
