# Franken

Fast clustering pipeline for high-thoughtput single-cell data

# Citation

If you use the Franken package please use the following citation:

Laura De Vargas Roditi, Andrea Jacobs, Jan H. Rueschoff, Pete Bankhead, Stephane Chevrier, Hartland W. Jackson, Thomas Hermanns, Christian D. Fankhauser, Cedric Poyet, Felix Chun, Niels J. Rupp, Alexandra Tschaebunin, Bernd Bodenmiller, Peter J. Wild

doi: https://doi.org/10.1101/2021.01.25.428046

# Get the package

Franken can be installed use the devtools package:

devtools::install_github("ldvroditi/Franken")

# Demo

For a demo of how to use Franken please see file TestDataRun.R

The prostate cancer data in the Franken Bioarxiv pre-print will be published upon publication but the data in the demo (and used for benchmarking in the pre-print) is from:

Single-Cell Mass Cytometry of Differential Immune and Drug Responses Across a Human Hematopoietic Continuum
By Sean C. Bendall, Erin F. Simonds, Peng Qiu, El-ad D. Amir, Peter O. Krutzik, Rachel Finck, Robert V. Bruggner, Rachel Melamed, Angelica Trejo, Olga I. Ornatsky, Robert S. Balderas, Sylvia K. Plevritis, Karen Sachs, Dana Pe’er, Scott D. Tanner, Garry P. Nolan
Science06 May 2011 : 687-696 

Please download the demo cytof data from figshare repo and save it in a folder of your choosing (the path to your data folder will henceforth be referred in TestDataRun.R as *yourdatafolder*):

https://figshare.com/articles/Levine_32dim_fcs/11295719

This demo data has been pre-processed according to :

Weber, L.M. and Robinson, M.D. (2016), Comparison of clustering methods for high‐dimensional single‐cell flow and mass cytometry data. Cytometry, 89: 1084-1096. doi:10.1002/cyto.a.23030



