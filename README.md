# Instructions
## Prerequisits
* [Anaconda](https://www.anaconda.com/)

## Creating an environment
Use the terminal (or GUI, if that is preferred) and create an environment from the provided `environment.yml` file:
```shell
conda env create -f environment.yml
```

Then activate the new environment:
```shell
conda activate citw_analysis
```

(See [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) for more information.)

## Running the analysis scripts
Run the Jupyter notebook:
```shell
jupyter notebook
```
and open the prompted link in browser.

Navigate to `scripts` directory and run necessary analysis script.

`analysis.ipynb` generates Figures 8~19 and conducts the statistical analysis provided in Sections 5.3 through 5.8 in the paper.

`abandonment_analysis.ipynb` generates Tables 5~8 in the paper.