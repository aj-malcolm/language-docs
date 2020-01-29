# Conda-Commands

## Table of Contents

1. [Managing Environment](#env)
1. [Managing Packages](#packages)

### <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html" name="env"> Managing Environment </a>

| Command | Description |
| ------- | ----------- |
| `conda create --name myenv` | Create environment with commands. |
| `conda create -n myenv python=3.6` | Create environment with specific python/package version. |
| `conda env create -f environment.yml` | Create environment from yml file. |
| `conda env export > environment.yml` | Export current environment settings to file. |

### <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html" name="packages"> Managing Packages </a>

| Command | Description |
| ------- | ----------- |
| `conda list` | View packages in active environment. |
| `conda list -n myenv` | View packages in given environment. |
| `conda install scipy` | Install package in active environment. |
| `conda install --name myenv scipy` | Install package in given environment. |
| `conda install scipy=0.15.0` | Install specific version of package. |
| `conda install scipy numpy` | Install multiple packages. |
