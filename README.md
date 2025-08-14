This code was written for the publication Rafter, P. A., Gray, W. R., Hines, S. K. V., Burke, A., Costa, K. M., Gottschalk, J., et al. (2022). Global reorganization of deep-sea circulation and carbon storage after the last ice age. Science Advances, 8(46), eabq5434. https://doi.org/10.1126/sciadv.abq5434.

The dataset this code was written for can be found here: https://www.ncei.noaa.gov/pub/data/paleo/paleocean/global/rafter2022/rafter2022-basin-14c.txt


The code "basin-mean-LOESS" was written in R (base R) to create basin-scale LOESS (LOcally Estimated Scatterplot Smoothing) regression. It takes advantage of the 

The code "cal-age-update-for-planktic-14C" is also written in R (base R) and it takes the same dataset (above) and updates the calendar ages using BACON (an R-based app). Of note is the column titled "chro.meth" which describes the chronological method used to establish the proxy age mode. the guideline for this column is: [1=U-Th; 2=Wood/Tephra; 3=Plk 14C; 3.1=Plk+R 4=Match; 5=Plateau; 6=other]. Generally speaking, this numbering is from most trustworthy / robust and less so...

