# Homerton-Image-Processing-with-Python-Workshop
Teaching material for the image processing with python course at Homerton College, Cambridge on the 12th Aug, 2024

## Contact
Cheng-Yu Huang "Kou" (cyh37@cam.ac.uk)

https://drive.google.com/drive/folders/1REqwtiGnpN3ny87VonwpauwFmX39IVO2?usp=sharing

## Pre-requirement for the workshop

- Please install miniconda (https://docs.anaconda.com/miniconda/miniconda-install/) on your laptop (Yes, you need a laptop) and follow the “Creating a Python Environment for the workshop” workflow below for the setup.
- Please install Github desktop (https://desktop.github.com/download/) on your laptop.

### Creating a Python Environment for the workshop

1. With the Anaconda prompt, create a virtual environment with the name “bioimage-analysis” (When asked `proceed ([y]/n)?` press `y` and enter)

    ```bash
    conda create --name bioimage-analysis python=3.11
    ```

2. Then activate the environment
    ```bash
    conda activate bioimage-analysis
    ```

3. Install all the necessary packages
    ```
    pip3 install numpy matplotlib scipy scikit-image jupyter pandas 
    ```
    Then install Napari 3D viewer (https://napari.org/stable/index.html) with
    ```bash
    python -m pip install "napari[all]"
    ```

4. Launch the Jupyter Lab by:
    ```bash
    jupyter lab
    ```
    ** You can launch python from within the visual studio code too. Ask me about how to do it if you have vscode on your laptop.

5. Download this repository with Github desktop; navigate to the downloaded Github repository within the Jupyter lab.

6. (**Do it over the dinner time**, as this takes longer) Install machine learning packages
    ```bash
    pip3 install scikit-learn seaborn umap-learn 
    ```
    and 
    ```bash
    pip3 install hdbscan
    ```

## Other resources
- Other conda command: https://docs.conda.io/projects/conda/en/4.6.0/user-guide/tasks/manage-environments.html
