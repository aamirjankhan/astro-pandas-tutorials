# astro-pandas-tutorials
These are tutorials on how to use Pandas Data Frames for professional astronomy.  Import common types of astronomical data, filter, sort, and plot.  Contributions welcome!  Started by <a href="http://www.janerigby.net/">Jane Rigby</a>, Oct. 2016.

Tutorial #1, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Get%20data%20into%20pandas.ipynb">Get data into Pandas</a>, does just that -- it shows examples of importing ascii tables, machine-readable tables from the Astrophysical Journal, binary fits tables, and csv tables.  It relies on astropy.Tables to read the astronomy-specific formats, and then convert via <a href="http://docs.astropy.org/en/stable/table/pandas.html">Tables.table.to_pandas()</a>.

Tutorial #2, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/MRD%20to%20Pandas%20to%20Seaborn%20plot.ipynb">MRD to Pandas to Seaborn</a>, grabs a machine-readable table from an ApJS journal article, converts to a Pandas data frame (via astropy Tables), filters the data, and plots a density plot using seaborn.

Tutorial #3, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Filter%203D-HST%20catalog%20and%20plot%20R_e%2C%20sersic%20index.ipynb">Filter 3D-HST catalog and plot Re, sersic index</a>, is the first tutorial tha really shows the power of Pandas.  This tutorial reads in two large catalogs, and use the parameters in one catalog to filter the second catalog.  It then makes groovy plots.

Tutoral #4, <a href="https://github.com/janerigby/astro-pandas-tutorials/blob/master/Plot%20directly%20from%20Pandas.ipynb">Plot directly from Pandas</a>, shows how you can directly plot a Pandas DataFrame, in a matplotlib-compatible way.  May be faster than pyplot.plot() for quick-loock visualization.

Tutoral #5 is *your chance to contribute!*