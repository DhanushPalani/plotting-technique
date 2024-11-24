# Ex.No:3. Visualize data using basic plotting techniques in Python
## Aim
To visualize data using basic plotting techniques like bar plots, scatter plots, and histograms with Python.

## Procedure

1.Install Python libraries: Pandas and Matplotlib.
2.Load a dataset into a Pandas DataFrame.
3.Use the DataFrame .plot methods for various visualizations.
## code:
```
import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv("https://waf.cs.illinois.edu/discovery/football.csv")

# Create visualizations
df.plot.box()
df.plot.scatter(x="IlliniScore", y="OpponentScore")
plt.show()
```
## Result
Generated visualizations including box plots and scatter plots for the dataset.
