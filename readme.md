# Interactive Python Dashboards with plotly and dash

This repository is a set of JupyterLab notebooks, I made while following along with Jose Portilla's Udemy course Interactive Python Dashboards with plotly and dash. The course was made in 2018 and is a bit outdated as alot of developments have been made in the plotly and dash libraries since that time. I took the course in 2022 and had to slightly tweak the code to get it to work in a JupyterLab with the latest version of plotly and dash. Jose's explanation of the plotly syntax, covers the fundamentals behind graph objects particularly well. Currently use of plotly express is recommended over use of plotly graph objects for most commonly used plot types. However the course was made before the release of plotly express and therefore does not cover plotly express. That being said, plotly graph objects is still required for advanced plotting and so the course is still a useful resource when it comes to understanding the fundamentals and syntax of plotly graph objects.

Jose Portilla's Udemy course:
[Interactive Python Dashboards with plotly and dash Udemy](https://www.udemy.com/course/interactive-python-dashboards-with-plotly-and-dash/).

Jose Portilla's GitHub files:
[Interactive plotly dashboards with dash GitHub](https://github.com/Pierian-Data/Plotly-Dashboards-with-Dash)

# Perquisites

Before beginning the course, ensure you are comfortable with the Python programming language especially concepts such as for loops, list comprehension and dictionary comprehension), as well as the data science libraries numpy and pandas. Jose has a very small intro section covering this in the plotly and dash course but a beginner will likely struggle without a deeper understanding.

Jose has a begineer Python course and an intermediate datascience course which covers these libraries.

Ensure you take the **updated 2022 courses**:

[Python Bootcamp 2022 Udemy](https://www.udemy.com/course/complete-python-bootcamp/)

[Python for Machine Learning Data Science Masterclass 2022 Udemy](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/)

And not the **outdated 2018 course**:

[Python for Data Science and Machine Learning Bootcamp 2018 Udemy](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)

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
conda install -c conda-forge plotly dash pandas-datareader
conda install -c conda-forge jupyterlab-variableinspector
```

Launch JupyterLab from the Anaconda PowerShell Prompt or the Linux Terminal using:

```
conda activate jupyterlab-cf
jupyter-lab
```

# Plotly Graph Objects

The plotly graphs for these notebooks will not render on GitHub however will render in [nbviewer](https://nbviewer.org/).

For best results these notebooks should be opened and run in JupyterLab:

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

These notebooks should be opened and run in JupyterLab:

* [dash Layouts 1a](./lect35_dash_layouts_1a.ipynb)
* [dash Layouts 1b](./lect35_dash_layouts_1b.ipynb)
* [dash Layouts 2](./lect36_dash_layouts_2.ipynb)
* [Converting Simple plotly to dash](./lect37_converting_simple_plotly_to_dash.ipynb)
* [Simple Dashboard Exercise](./lect38_simple_dashboard_exercise.ipynb)
* [html Components](./lect41_html_components.ipynb)
* [core Components](./lect42_core_components.ipynb)
* [Using help](./lect44_using_help_with_dash.ipynb) 
* [Single Callback for Interactivity](./lect45_single_callback.ipynb)
* [Callbacks for Graph](./lect46_dash_callbacks_for_graph.ipynb)
* [Multiple Inputs](./lect47_multiple_inputs.ipynb)
* [Multiple Outputs](./lect48_multiple_outputs.ipynb)
* [Interactive Components Exercise](./lect49_interactive_components_exercise.ipynb)
* [Controlling Callbacks with State](./lect51_controlling_callbacks_with_state.ipynb)
* [Hover Over Data](./lect52_hover_over_data.ipynb)
* [Click Data](./lect53_click_data.ipynb)
* [Selection Data](./lect54_selection_data.ipynb)
* [Updating Graphs on Interactions](./lect55_updating_graphs_on_interactions.ipynb)
* [Milestone Project](./lect58_milestone_project.ipynb)
* [Layout Updating](./lect59_layout_updating.ipynb)
