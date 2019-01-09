Introducing CPS Enrollment Datasets
================
Charlotte Mack
2019-01-09

CPSenrollment
=============

Exploring enrollment data from the Chicago Public Schools

This repository contains exploratory analysis and visualizations of enrollment data that were extracted from Chicago Public Schools (CPS) public records. The prepared data are available at this repository in Rds and csv formats; at present there are only high school data, with elementary school data forthcoming. The sets span the school years from 2006--2007 through 2016--2017, and will be periodically updated.

A glimpse of the high schools data:

    ## Observations: 1,914
    ## Variables: 10
    ## $ govern      <fct> regular, regular, regular, regular, regular, regul...
    ## $ school_id   <int> 610245, 609695, 609696, 610402, 609708, 609716, 60...
    ## $ common_name <chr> "Douglass HS", "Amundsen HS", "Austin HS", "DeVry ...
    ## $ year        <dbl> 2006, 2006, 2006, 2006, 2006, 2006, 2006, 2006, 20...
    ## $ total       <int> 737, 1500, 580, 223, 1738, 1694, 1439, 4278, 1936,...
    ## $ total_hs    <dbl> 384, 1500, 580, 223, 1738, 1694, 1439, 4278, 1936,...
    ## $ g09         <int> 215, 435, NA, NA, 606, 510, 513, 1103, 578, 254, 2...
    ## $ g10         <int> 119, 438, NA, NA, 504, 419, 331, 945, 546, 254, 30...
    ## $ g11         <int> 50, 361, 367, 107, 380, 371, 291, 1230, 403, NA, 2...
    ## $ g12         <int> NA, 266, 213, 116, 248, 394, 304, 1000, 409, NA, 2...

The original CPS data are available in a series of spreadsheets at [CPS website](http://www.cps.edu/SchoolData/Pages/SchoolData.aspx)[1] Downloadable data files that I have prepared are in this repository with Rds and csv extensions, downloadable through the links below. The Rds files, which are used in R language programming, may have some type designations that are not in the csv files, but there should be no other difference.

[Rds file for all CPS high schools, September 2006 to September 2017](https://github.com/cymack/CPSenrollment/blob/master/enrollment_all_hs.Rds)

[csv file for all CPS high schools, September 2006 to September 2017](https://github.com/cymack/CPSenrollment/blob/master/enrollment_all_hs.csv)

[Rds file of high school locations as of 2014--2015 school year, with enrollments from 2016--2017 school year](https://github.com/cymack/CPSenrollment/blob/master/school_loc_merged.2016.Rds)

[Rds file of high school locations as of 2014--2015 school year, with enrollments from 2006--2007 school year](https://github.com/cymack/CPSenrollment/blob/master/school_loc_merged.2006.Rds)

A more detailed overview of the all-years enrollment data is in the file [CPSenrollment.md](https://github.com/cymack/CPSenrollment/blob/master/CPSenrollment.md).

[1] Membership data are under the heading "Demographics."
