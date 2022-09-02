# Interactive Python Dashboards with plotly and dash

Jose Portilla's Udemy course:
[Interactive Python Dashboards with plotly and dash Udemy](https://www.udemy.com/course/interactive-python-dashboards-with-plotly-and-dash/).

Jose Portilla's GitHub files:
[Interactive plotly dashboards with dash GitHub](https://github.com/Pierian-Data/Plotly-Dashboards-with-Dash)

The course and original files were made in 2018 and are quite outdated as there have been numerous developments in plotly such as plotly express which is sadly not covered in this course. 

That being said, Joses explanation of the plotly syntax, covers the fundamentals behind graph objects particularly well. Currently use of plotly express is recommended over use of plotly graph objects for most commonly used plot types. However plotly graph objects is still required for advanced plotting and so the course is still a useful resource when it comes to understand the fundamentals and syntax of plotly graph objects.

These are my notes as JupyterLab notebooks when working through the course, four years later in 2022.

# Perquisites

Before beginning this course, ensure you are comfortable with the Python programming language especially concepts such as for loops, list comprehension and dictionary comprehension), as well as the data science libraries numpy and pandas. Jose has a very small intro section covering this in the plotly and dash course but a beginner will struggle without a deeper understanding.

Jose has a begineer Python course and an intermediate datascience course which covers these libraries.

Ensure you take the **updated 2022 course**:

[Python Bootcamp 2022 Udemy](https://www.udemy.com/course/complete-python-bootcamp/)

[Python for Machine Learning Data Science Masterclass](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/)

And not the **outdated 2018 course**:

[Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)

# Setting up a conda env

This folder can be downloaded as a zip file. The extracted contents can be opened and launched in JupyterLab.
You will however need a compatible conda environment.

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

# Plotly Graph Objects

These links display the notebooks on notebook viewer. The [Notebook Viewer](https://github.com/PhilipYip1988/plotly_udemy/blob/main/readme.md) has wider compatibility than GitHub natively when it comes to viewing commonly used objects in JupyterLab such as plotly graph objects:

* [Scatter Plots](./lect11_scatter_plots.ipynb)
* [Line Charts](./lect12_line_charts.ipynb)
* [Line Charts 2](./lect13_line_charts_2.ipynb)
* [Line Charts Exercise](.lect14_line_charts_exercise.ipynb)
* [Bar Charts](./lect16_bar_charts.ipynb)
* [Bar Charts Exercise](./lect17_bar_charts_exercise.ipynb)
* [Bubble Plots](./lect18_bubble_plots.ipynb)
* [Bubble Plots Exercise](./lect20_bubble_plots_exercise.ipynb)
* [Box Plots](./lect22_box_plots.ipynb)
* [Box Plots Exercise](./lect23_box_plots_exercise.ipynb)
* [Histograms](./lect25_histograms.ipynb)
* [Histograms Exercise](./lect26_histograms_exercise.ipynb)
* [Distplots](./lect28_distplots.ipynb)
* [Distplots Exercise](./lect29_distplots_exercise.ipynb)
* [Heatmaps](h./lect31_heatmaps.ipynb)
* [Heatmaps Exercise](./lect32_heatmaps_exercise.ipynb)

# Dash

These notebooks give a 404 error when displayed on Notebook Viewer as the Notebook Viewer is not able to view the dash server. Instead they should be opened in JupyterLab:

* [dash Layouts 1a](./lect35_dash_layouts_1a.ipynb)
* [dash Layouts 1b](./lect35_dash_layouts_1b.ipynb)
* [dash Layouts 2](./lect36_dash_layouts_2.ipynb)
* [Converting Simple plotly to dash](./lect37_converting_simple_plotly_to_dash.ipynb)
* [Simple Dashboard Exercise](./lect38_simple_dashboard_exercise.ipynb)
* [html Components](./lect41_html_components.ipynb)
* [core Components](./lect42_core_components.ipynb)
* [Using help](./lect44_using_help_with_dash.ipynb) 
* 
* [Callbacks for Graph](./lect46_dash_callbacks_for_graph.ipynb)
* [Multiple Inputs](./lect47_multiple_inputs.ipynb)
