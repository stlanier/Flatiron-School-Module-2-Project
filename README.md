# Understanding King County Housing Prices

For my second Flatiron School project, I've been tasked with producing a model of the relationship between a house's price in King County, Washington and a number of predictors––square footage, number of bathrooms, year built, etc.––using multiple linear regression. The model has been built for the purpose of inference moreso than prediction.

## Getting Started
### Contents of Repository

* **analysis.ipynb** is a Jupyter Notebook contain
* **Presentation.pdf** contains my powerpoint presentation for a non-technical audience.
* **Data** is a directory containing:
  * **kc_house_data.csv** contains all data provided by Flatiron School.
  * **column_names.md** contains explanations for each feature in the kc_house_data set.
  * **zipcodes.csv** contains a list of [all zipcodes in King County](https://gis-kingcounty.opendata.arcgis.com/datasets/e6c555c6ae7542b2bdec92485892b6e6_113). Only used for the final figure in my analysis.
  * **wa_washington_zip_codes_geo.min.json** contains [GeoJSON data for all zipcodes in Washington State](https://github.com/OpenDataDE/State-zip-code-GeoJSON). Only used for the final figure in my analysis.
* **Images** is a directory containing images used in this README.

### Prerequisites

The standard packages for data analysis are required–[NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), and [Matplotlib](https://matplotlib.org/)–as well as [SciPy](https://www.scipy.org/), [scikit-learn](https://scikit-learn.org/stable/index.html), and [StatsModels](https://www.statsmodels.org/stable/index.html) for linear regression. Below are examples of their installations using Anaconda for all but Matplotlib, for which Brew is used.

```
$ conda install -c anaconda numpy
$ conda install pandas
$ conda install -c anaconda scipy
$ conda install scikit-learn
$ conda install -c conda-forge statsmodels
```

## Built With

[Jupyter Notebook](https://jupyter.org) - Documents containing live code and visualizations.

## Contributing

Due to the nature of the assignment, this project is not open to contributions. If, however, after looking at the project you'd like to give advice to someone new to the field and eager to learn, please reach out to me at [stephen.t.lanier@gmail.com]

## Author

**Stephen Lanier** <br/>
[GitHub](https://github.com/stlanier) <br/>
[Datalingo](https://datalingo.wordpress.com)



## Acknowledgments

<a href="https://flatironschool.com"><img src="Images/flatiron.png" width="80" height="40"  alt="Flatiron School Logo"/></a>
Special thanks to Jacob Eli Thomas and Victor Geislinger, my instructors at [Flatiron School](https://flatironschool.com), for their encouragement, instruction, and guidance.
