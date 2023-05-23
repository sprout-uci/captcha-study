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

`analysis.ipynb` generates Figures 7~14 in Sections 5.1 through 5.4 and in Appendix D as well as the statistical analysis provided in Sections 5.1 through 5.4 and in Appendix C in the paper.

`abandonment_analysis.ipynb` generates Tables 7~10 in Appendix A in the paper.