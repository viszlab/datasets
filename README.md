# ![Datasets](docs/datasets_github_banner.png)

Code for cleaning, transforming and analyzing data from the methodologies used in the thesis project. This includes data from the survey questionnaire among building occupants, data logs from the air quality monitors installed within the meeting rooms and data and coding from the evaluation sessions of the prototype.

Written in Python ([Jupyter Notebook](https://jupyter.org/) format, .ipynb), the notebooks utilize libraries such as [Numpy](https://numpy.org/) and [Pandas](https://pandas.pydata.org/) for data cleaning. Visualization libraries like [Seaborn](https://seaborn.pydata.org/) are employed to create graphs and plots, offering an overview of the collected data, exploring patterns, and gaining insights into understanding the occupants.

The data used within the notebooks are _not publicly available_ and are thus not part of this GitHub repository. Only aggregated datasets and data frames of cleaned outputs are visible within the notebooks. Please contact the researcher for the possibility of getting access to the raw unstructured data used in this research.

The notebooks can be viewed using [JupyterLab](https://jupyter.org/try) or using the below set-up with the native implementation within VSCode as described below in the install guide.

## Install

1) Install a code editor such as [VSCode](https://vscode.dev/).
2) Install [Python](https://www.python.org/) using the [Anaconda distribution](https://docs.anaconda.com/free/anaconda/install/index.html)
3) Clone this repository to your local machine.

```zsh
$ git clone git@github.com:viszlab/datasets.git
```
4. Set-up your VSCode environment using the [official guide](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
5. Run (all) the cells to display the output and plot the graphs


## Project Structure
```
├── docs                    # Images and documentation for the repo
├── monitor-charts          # Output graphs of the monitor notebooks
├── monitor-data            # Raw .csv logs from the monitors (not included)
├── survey-data             # Raw .csv export from qualtrics (not included)
├── survey-charts           # Output graphs of the survey notebooks
├── monitor-notebooks       # Notebooks to analyse monitoring data
└── survey-notebooks        # Notebooks to analyse survey data
```

## Project
[**Viszlab**](https://wwww.viszlab.github.io) is a tangible physical data visualization for the [Lab42](https://lab42.uva.nl/) building. An interactive experience using environment sensor data to offer Human Building-Interaction. Viszlab is developed as a Thesis and Graduation project for the Master (MSc) Information Studies: [Information Systems](https://www.uva.nl/shared-content/programmas/en/masters/information-studies/information-studies.html) (track) at the [University of Amsterdam](https://www.uva.nl/en) by part-time student [Danny de Vries](https://www.dandevri.es/).

* **Master**: Master Information Studies: Information Systems (track)
* **University**: University of Amsterdam (UvA)
* **Institute**: Informatics Institute
* **Faculty**: Faculty of Science (FNWI)
* **Research Group**: Digital Interactions Lab (DIL)
* **Student**: BSc Danny de Vries (14495643)
* **Supervisor**: Dr. H. (Hamed) Seiied Alavi PhD

[Viszlab](https://www.viszlab.github.io) © 2024 by [Danny de Vries](https://wwww.github.com/dandevri) is licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1). 
