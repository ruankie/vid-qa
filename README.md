[![GitHub Repo stars](https://img.shields.io/github/stars/ruankie/conda-py-minimal-template)](https://github.com/ruankie/conda-py-minimal-template)
[![GitHub file size in bytes](https://img.shields.io/github/size/ruankie/conda-py-minimal-template)](https://github.com/ruankie/conda-py-minimal-template)

# conda-py-minimal-template
Minimal template with the essentials for quickly setting up new python projects. Includes a simple folder structure and a conda environment for isolated dependency management.

## Usage
1. Start a new repo using this template
2. Update your `LICENSE` file.
3. Update your `README.md` file.
4. Set up and activate conda environment
   1. Rename your conda environment in the `./conda.yml` file.
   2. Add/change any dependencies and their versions in the `./conda.yml` file.
   3. Set up your conda environment and activate it by running:
        ```bash
        conda env create -f conda.yml
        conda activate <your-env-name>
        ```
5. Add your own scripts in `./src/`
6. Add your own notebooks in `./notebooks/`
7. Add your own data in `./data/`

This template creates the following folder structure:

```
<your-repo-name>
├── LICENSE
├── README.md
├── conda.yml
├── data
├── notebooks
│   └── example.ipynb
├── setup.py
└── src
    ├── __init__.py
    └── utils.py
```
