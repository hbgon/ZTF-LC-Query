#Created by hbgon on 10 July 2023.


# ZTF LC Query


**Version 1.0:**

A simple way to obtain a light curve (g, r and i band when available) from Zwicky Transient Facility's data given just a coordinate (ra, dec). I recommend you to also search for the object on IRSA Gator (https://irsa.ipac.caltech.edu/cgi-bin/Gator/nph-dd) and certify that the coordinate is right, there could be close by objects.

----------------------

**Version 2.0:**

A more sophisticated way to retrieve data from the Zwicky Transient Facility given a coordinate. This code takes a table as input containing 'ra' and 'dec' in degrees and returns four files: The light curve plot with separate g, r, and i bands, and three ".dat" files corresponding to the three bands, with columns divided into mjd, mag, and mag_err. Now, you also can choose whether you want to check the light curve before downloading or if you prefer to download everything at once, just by modifying some highlighted parts of the code. 

Use "teste_sample.xlsx" as an example.

----------------------

**Version 2.5:**

There is no longer the option to download with approval and now the legend of the plots shows the RMSD of the band and "reliability" which means "(RMSD/average error)". The plot nomenclature is written as "{g band rmsd}-ra{ra},dec{dec}.png". If the query does not present data, the plot name will start with 1.0.


Use "teste_sample.xlsx" as an example.

----------------------
