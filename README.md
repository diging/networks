# Programming for Network Research
**[Erick Peirson, PhD](https://asu.academia.edu/ErickPeirson)** | erick.peirson@asu.edu | [@captbarberousse](https://twitter.com/captbarberousse)

Last updated 20 January, 2016

## 0. Introduction

This notebook series provides an introduction to programming for network research using the [Python programming language](https://www.python.org/).

Network models have become a ubiquitous component of quantitative research in the sciences and humanities. Many research problems in the area of complexity science are framed in terms of networks, since network models provide tractable ways of reasoning about complex systems. The purpose of this series is to equip scholars with no prior programming experience with tools and techniques for analyzing networks in a computational framework.

The Python programming language has become extremely popular for data science due to its relatively high level of abstraction, and the availability of powerful scientific and numerical packages.

The early sections of this series will deal with the basics of any introduction to programming course: variables, data types, logical operators, flow control, and functions. We will then move quickly into using numerical and scientific packages like [NumPy](http://www.numpy.org/), [SciPy](http://www.scipy.org/), and [Pandas](http://pandas.pydata.org/). Once we have a good command of general data manipulation in Python, we will explore network analysis packages like [NetworkX](networkx.github.io), [igraph](http://igraph.org/redirect.html), and [graphtool](https://graph-tool.skewed.de/). Along the way, we'll also employ external network analysis and visualization software like [Cytoscape](http://cytoscape.org/) and [Gephi](https://gephi.org/).

### 0.1. How to use these notebooks.

These are [interactive Python notebooks](http://ipython.org/). Most of the content is just marked-down text that provides expository on some concept or technique. Some of the cells are "code" cells, which look like this:

```python
In [1]: print "This is a code cell!"
```

You can execute the code in a code cell by clicking on it and pressing Shift-Enter on your keyboard, or by clicking the right-arrow "Run" button in the toolbar at the top of the page. You can run many cells in quick succession by repeatedly pressing Shift-Enter (or the "Run" button). It's a good idea to run all of the code cells in order, from the top of the tutorial, since many commands later in the tutorial will depend on earlier ones.

To work through these notebooks in interactive mode, you'll need to clone this repository (https://github.com/diging/networks). For an introduction to using the IPython notebook platform, see the [IPython documentation](https://ipython.org/ipython-doc/3/notebook/index.html).

As we work through the notebooks, you'll have plenty of opportunities to manipulate code, and insert new code of your own. You should experiment and play! Try changing values and parameters, and re-run the code-cell to see the result. That's what's great about iPython notebooks: you can play around with specific chunks of code without having to re-run the entire script.

### 0.2. How to get help.

If you run into trouble, or simply have questions, please feel free to submit an [issue on the Github repository for this course](https://github.com/diging/networks/issues). I'll respond as quickly as I can!

### 0.3. License.

The notebooks in this series are made available under the GNU General Public License v3.0. For the full text of the license, please see the [LICENSE](https://github.com/diging/networks/blob/master/LICENSE) file in the root directory of this repository.

![](assets/images/gpl.png)

### 0.4. Table of Contents

This table will be updated as new notebooks are added.

* [0. Introduction](0.%20Introduction.ipynb).
* [1. First steps with Python](1.%20First%20steps%20with%20Python.ipynb).
* [2. Objects and types](2.%20Objects%20and%20types.ipynb).
* [3. Flow control: if, elif, else, and friends.](3.%20Flow%20control.%20if%2C%20elif%2C%20else%2C%20and%20friends.ipynb)
* 4: Functions and functional programming.
* 5: I/O: working with data! Numpy and Pandas.
* 6: Our first tabular graph. Layout and visualization in Cytoscape.
* 7: Intro to NetworkX. GraphML. Advanced visualization in Cytoscape.
* 8: Blockmodels in NetworkX.
* 9: Properties of graphs: whole-graph statistics in NetworkX and Cytoscape.
* 10: Properties of nodes: centrality statistics.
* 11: ...
