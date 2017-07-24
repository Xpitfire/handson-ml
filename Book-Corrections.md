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
93 | wrong code: plot\_roc\_curve(fpr\_forest, tpr\_forest, "Random Forest") and plt.legend(loc="bottom right") | add label: plot\_roc\_curve(fpr\_forest, tpr\_forest, label="Random Forest") and change: plt.legend(loc="lower right")
98 | missing function / reference: plot_digits | Indicate that the function is only available within the GitHub repo or so
101 | code lines are inversed and code is assigned but not used: noise = ...; noise = ... | noise = ...; X\_train\_mod = X\_train + noise
102 | code missing: plot_digit is not defined | either refer to the GitHub repo or define the function; this might seem picky, but up until now I was able to use the book as a guid and implement the code on my own step-by-step
- | math_linear_algebra.ipynb: Calculating the angle between vectors: Note that if u⋅v=0, it follows that  θ=π/4 | θ=π/2
- | math_linear_algebra.ipynb: Matrix multiplication: It is also distributive over addition of matrices, meaning that (Q+R)S=QS+RS | Square matrix are distributive over addition
- | math_linear_algebra.ipynb: Matrix multiplication – Projection onto an axis: Now let's look at the dot product P⋅U | U⋅P