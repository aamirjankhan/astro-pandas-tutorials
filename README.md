# astro-pandas-tutorials
These are tutorials on how to use Pandas Data Frames for professional astronomy.  Import common types of astronomical data, filter, sort, and plot.  Contributions welcome!  Started by <a href="http://www.janerigby.net/">Jane Rigby</a>, Oct. 2016.

Tutorial #0, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Why%20Pandas.ipynb">Why Pandas?</a>, illustrates the power of Pandas for dealing with astronomical data.

Tutorial #1, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Get%20data%20into%20pandas.ipynb">Get data into Pandas</a>, shows examples of importing ascii tables, machine-readable tables from the Astrophysical Journal, binary fits tables, and csv tables.  It relies on astropy.tables to read the astronomy-specific formats, and then convert via <a href="http://docs.astropy.org/en/stable/table/pandas.html">Tables.table.to_pandas()</a>.

Tutorial #2, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Basic%20filtering%2C%20visualization%2C%20and%20math.ipynb">
Basic filtering, visualization, and math</a>, shows how to work with a data frame, do math on it, and make simple plots. The example is a machine-readable table from a recent ApJ paper. 

Tutorial #3, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/MRD%20to%20Pandas%20to%20Seaborn%20plot.ipynb">MRD to Pandas to Seaborn</a>, grabs a machine-readable table from an ApJS journal article, converts to a Pandas data frame (via astropy Tables), filters the data, and plots a density plot using seaborn.

Tutorial #4, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Filter%203D-HST%20catalog%20and%20plot%20R_e%2C%20sersic%20index.ipynb">Filter 3D-HST catalog and plot Re, sersic index</a>, shows off the power of Pandas.  This tutorial reads in two large catalogs, uses the parameters in one catalog to filter the second catalog, and then makes groovy plots.

Tutoral #5, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Plot%20directly%20from%20Pandas.ipynb">Plot directly from Pandas</a>, shows how you can directly plot a Pandas DataFrame, in a matplotlib-compatible way, which may help with quick-look visualization.

Tutorial #6, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Tables%20-%20Pandas%20and%20Astropy.ipynb">Tables - Pandas and Astropy</a>, is in progress.  It shows where astropy and pandas currently don't play well together.

Tutoral #7 is *your chance to contribute!*

Other resources:
The O'Reilly book <a href="http://shop.oreilly.com/product/0636920023784.do">
Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython</a>, by Wes McKinney 
(the creator of Pandas), is getting rave reviews.  

Here's <a href="https://github.com/BrownDwarf/ApJdataFrames">a trove of Brown Dwarf examples 
using Pandas</a>.


