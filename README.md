# UK Housing Analysing

This analysis is a groupwork, using Dask to work with big data file. Original dataset: https://www.kaggle.com/hm-land-registry/uk-housing-prices-paid contains <i>>20 million rows</i>

<b>Preview final work in file "UK_housing_PREVIEW"</b>

<b>Final work "UK_housing_Thuong_Pawan_Jui_Sandip.ipynb"</b>:

- Clean and Process data: Thuong
- Analysis part 1: Pawan
- Analysis part 2: Jui & Sandip
- Analysis part 3: Thuong
- Analysis part 4: Thuong

Original seperate work of individual can be traced back to file that ends with individual name.



Notice for loading dataset:
1. download dataset to your computer.
2. In the first part of load and processing data -->Extract data from year 2012 up: uncomment three code cells to load data, up to this point you have the extract dataset 'data2012up.csv' contains <i>4.8million rows</i>. After that, comment those three code cells.
3. Notice: Fix the path if necessary, so your computer can locate to pick the right file. Adjust number of clients and workers in dask.distributed code cell depending on your computer configuration.
