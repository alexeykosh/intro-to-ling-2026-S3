
# Introduction to linguistics for data science

## Instuctors  

- Alexey Koshevoy (AK)
- Mathilde Hutin (MH)
- Magdalena Lemus Serrano (MLS)

## Overview

This repository contains practicals for the course "Introduction to linguistics trough data science" taught at the CPES program at ENS-PSL during the Autumn semester of 2026-2027.

## Prerequisites  

Students are expected to be familiar with the basics of Python programming language. The knowledge of the following libraries would be an asset: `pandas`, `numpy`, `matplotlib`. 

## Set up and run the notebooks

You only need to do the setup once. Open a terminal in this repository, then follow the instructions for your operating system. That way, you can run all the code locally if you cannot run it on Google Colab. 

### macOS or Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Windows (PowerShell)

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

### Install the requirements

With `.venv` activated, install the course requirements:

```bash
python -m pip install -r requirements.txt
```

### Open the notebooks in VS Code

1. Install [Visual Studio Code](https://code.visualstudio.com/) and its [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extensions.
2. In VS Code, select **File → Open Folder** and open this repository.
3. Open a notebook (`.ipynb` file).
4. Click **Select Kernel** in the top-right corner of the notebook.
5. Choose **Select Another Kernel → Python Environments**, then select the interpreter inside `.venv`.

VS Code remembers the selected environment for the next time you open the notebook.

If `.venv` does not appear, open the Command Palette (`Ctrl+Shift+P` on Windows/Linux or `Cmd+Shift+P` on macOS), run **Developer: Reload Window**, and try again.

## Schedule

| Week | Module | Date | Practicals link | Instructor |
|------|--------|---------|---------|---------|
| 1 | Morphology 1 | 09/09 | | AK |
