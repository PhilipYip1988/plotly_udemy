# Interactive Python Dashboards with plotly and Dash

This is a collection of JupyterLab notebooks based upon Jose Portilla's course:
[Interactive Python Dashboards with plotly and dash](https://www.udemy.com/course/interactive-python-dashboards-with-plotly-and-dash/).

This course is quite outdated as there have been numerous developments in plotly such as plotly express which is sadly not covered in this course. 

That being said, Joses explanation of the plotly syntax, covers the fundamentals behind graph objects particularly well. Currently use of plotly express is recommended over use of plotly graph objects for most commonly used plot types. However plotly graph objects is still required for advanced plotting and it is still useful to understand the fundamentals and syntax of plotly graph objects.

# Setting up a conda env

This folder can be downloaded as a zip file. The extracted contents can be opened and launched in JupyterLab.
You will need a compatible conda environment.

Install Miniconda or Anaconda.

Launch the Anaconda Powershell Prompt (Windows) or the Terminal (Linux).

Create a new conda environment and active it using:

```
conda create -n jupyterlab-cf
conda activate jupyterlab-cf
```

Install the following libraries using:

```
conda install -c conda-forge jupyterlab
conda install -c conda-forge cython seaborn scikit-learn sympy openpyxl xlrd xlsxwriter lxml sqlalchemy
conda install -c conda-forge nodejs ipywidgets 
conda install -c conda-forge plotly dash jupyter-dash
conda install -c conda-forge jupyterlab-variableinspector ipympl jupyterlab-drawio
```

Launch JupyterLab from the Anaconda PowerShell Prompt or Windows Terminal using:

```
conda activate jupyterlab-cf
jupyter-lab
```

# Section 3 Plotly Graph Objects

These links display the notebooks on notebook viewer:

* [Scatter Plots](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect11_scatter_plots.ipynb)
* [Line Charts](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect12_line_charts.ipynb)
* [Line Charts 2](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect13_line_charts_2.ipynb)
* [Line Charts Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect14_line_charts_exercise.ipynb)
* [Bar Charts](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect16_bar_charts.ipynb)
* [Bar Charts Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect17_bar_charts_exercise.ipynb)
* [Bubble Plots](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect18_bubble_plots.ipynb)
* [Bubble Plots Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect20_bubble_plots_exercise.ipynb)
* [Box Plots](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect22_box_plots.ipynb)
* [Box Plots Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect23_box_plots_exercise.ipynb)
* [Histograms](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect25_histograms.ipynb)
* [Histograms Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect26_histograms_exercise.ipynb)
* [Distplots](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect28_distplots.ipynb)
* [Distplots Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect29_distplots_exercise.ipynb)
* [Heatmaps](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect31_heatmaps.ipynb)
* [Heatmaps Exercise](https://nbviewer.org/github/PhilipYip1988/plotly_udemy/blob/main/lect32_heatmaps_exercise.ipynb)

# Section 4 Dash

These notebooks give a 404 error when displayed on Notebook Viewer. Instead they should be opened in JupyterLab:

* dash layouts 1a
* dash layouts 1b
* dash layouts 2
* converting simple plotly to dash 1a
* converting simple plotly to dash 1b
* converting simple plotly to dash 1c
* create a simple dashboard exercise
* html components
