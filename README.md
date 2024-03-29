# Introduction

This jupyter notebook illustrates a template workflow for creating and analyzing PIV data of migrating cells in a scratch wound assay. This approach was used in:

$\alpha$-catenin middle- and actin-binding domain unfolding mutants differentially impact epithelial strength and sheet migration<br>
Quinn JM, Wood M, Wang Y, Flozak AS, Le PM, Yemelyanov A, Oakes PW, and Gottardi CJ<br>
*Submitted 2024*

### Example Data included
Example Data can be found at this google drive link: https://drive.google.com/drive/folders/1B9DDFyDq_eGfYQ67aGSZsH4bZiV1iUwT?usp=sharing

It represents 5 frames taken from a DIC movie of MDCK cells migrating and a binary mask of those frames. These frames come from the middle of such an experiment. 

### Dependencies
This code was tested with the following packages and versions. There should be nothing specific about these particular versions and it should run in other environments, but if issues arise try reverting to these settings:
* python - 3.9.18
* numpy - 1.26.3
* scikit-image - 0.22.0
* scipy - 1.12.0
* matplotlib - 3.8.2
* openpiv - 0.24.2
* jupyter - 1.0.0 