# SF-Real-Estate-Investment-Analysis

Proptech, the application of technology to real-estate markets, is an innovative domain in the fintech industry. I am assuming an analyst role at a proptech company, they want to offer an instant, one-click service for people to buy properties and then rent them. The company wants to have a trial of this offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.

The goal is to use data visualization, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

---

## Technologies


Python 3.7.10

Jupyter Lab 3.0.11

Jupyter Notebook 6.2.0

Pandas 1.2.3

Pyviz - Plotly 4.13.0

Pyviz - hvPlot 0.7.1

Mapbox API 

python-dotenv

---

## Installation Guide

To install required libraries run the following commands:

    pip install pandas

    pip install python-dotenv

Install Jupyter with Anaconda. Then create and activate your conda environment to install Pyviz and set it up to work with Jupyter

    conda create -n dev python=3.7 anaconda

    conda activate dev

    conda install -c plotly plotly=4.13.

    conda install -c pyviz hvplot

    jupyter labextension install jupyterlab-plotly@4.13.0

    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0

    jupyter labextension install @pyviz/jupyterlab_pyviz

    jupyter lab build


To run Jupyter Notebook run this command in directory with notebook file:

    jupyter notebook financial_planning_tools.ipynb

You must also generate your own Mapbox API keys and place them in a .env file in the same directory as the project. 

Example text in file:

    MAPBOX_ACCESS_API_KEY = "Your API access key here"

---


## Usage

Once you run the Jupyter Notebook, click on the first cell then hit:

    Shift + Enter

keys to run the first cell. Keep hitting those keys to run each cell after that or click the Run button to run the entire program.

---

## Example

Running this cell will generate a scatter mapbox where the size of the cirles is based on the sale per square foot, while the color is based on the gross rent for neighborhoods in San Francisco. 

![Example]()

---
## License

[Click here to view](https://github.com/talibkateeb/SF-Real-Estate-Investment-Analysis/blob/main/LICENSE)
