# hier_bar
Python module that produces a bar chart (or histogram) from a pandas dataframe and hierarchical list of column names. 
The bar heights count the number of rows (elements) that appear in the subgroups defined by the elements of the cartesian product of the elements of the hierarchical list.  The last values of the last element run along the X-axis.

The main function is
'''
  make_bar_plot()
''', which takes arguments (1) a pandas dataframe and (2) a list of column names of that datafram from which to make 

This version currently supports bar charts of up to 20 different subgroups.  Updates will allow more subgroups and make the titles prettier.

