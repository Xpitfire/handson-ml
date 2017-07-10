Book Issues
==========================

This is a list of issues that where found within the book and may be reported to the author for correction.

Page | Error | Correction
---- | ----- | ----------
45 | Code example issue in ln [6]: housing.info | Missing parenthesis ln [6]: housing.info()
57 | Deprecated code: from pandas.tools.plotting import scatter_matrix | Use the new namespace: from pandas.plotting import scatter_matrix
67 | Suggestion: DataFrameSelector is missing on code and only explained at the bottom | Indicate in a comment that the DataFrameSelector is a custom code (I was searching 15 min for the package until I continued reading and found the code)
79 | Code results to error due to mldata.org server HTTPError: HTTP Error 500: INTERNAL SERVER ERROR | Solution from stackoverflow: https://stackoverflow.com/questions/43149272/cannot-get-mnist-database-through-anaconda-jupyter
86 | wrong variable usage in code block: precision_score(y\_train\_5, y\_pred) | replace with: precision_score(y\_train\_5, y\_train\_pred)