# Global Open Data Access

 The Global Open Data Access (GODA) project is a package that creates a standardized interface to download spatial and tabular datasets.

 The approach is to have a dataset class, a simple database of datasets, an `about()` function to inspect dataset objects, and a `download()` function that calls a hidden download function for each dataset.

 Class dataset
* name
* Download. URL
* Meta data url
* Methodology url
* Class [vector, raster, tabular]
* Years
* Download function

`Def about(name):
    Return dataset`

`Def download(name, year, save_path)
    Download dataset

    Return GDF, df, or (np.array, rasterio metadata )`


 An eventual goal will be to develop a package for Python (GODApy) and R (GODAr).
