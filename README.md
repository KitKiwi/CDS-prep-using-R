# CDS-prep-using-R
CDSSectionsABCDEGHJ_20-21.Rmd is an R markdown file that takes California State University Enrollment Reporting System submission files and create Common Data Set for 2020-2021.  In Section B, graduation rates are not broken down by Stafford loan or Pell grant receipt status.  In Section C, high school class rank is excluded.  Sections F and I are also excluded as the data are not available from the ERS files.  

The codes were developed by using East Bay's data.  Other campuses may need modifications based on the specific student characteristics unique to the campus.  The methodology used here may not necessarily be a "correct" way to compute the statistics.  Rather, the file is meant to be an example of using an R markdown document to ease the data entry as it can produce html, word, or PDF output directly from the program.

Need COSAR table, included in this repository as commonc-cosarcipcodefxvw-prd-1.csv to produce section J.  This file can also be downloaded from the Chancellor's Office's web site.  CIPCategory.csv, which was created from CDS form Section J, is also necessary to run the above R markdown files.
