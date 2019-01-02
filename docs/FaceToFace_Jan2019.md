# Face to Face Meeting: Baltimore Jan 10-11, 2019

## Resources (for reference)

- Previous slides: https://docs.google.com/presentation/d/1rhffdH_uG6tyPZt67ie4P_NKyWJIk6DqMOgGrA8dnyI/edit?usp=sharing

- Informal notes from first face-to-face meeting https://docs.google.com/document/d/1expHfjCHqgU2FqacQK7R5G_OiZDZ12xvZUhwYUw5emU/edit

- 'Ideal AnVIL architecture'

## Platform and expertise


- Bioconductor recap -- 'Statistical analysis & comprehension'; interactive; core and contributed packages; typical use with some but far from all packages used.

- Primary use is INTERACTIVE, through RStudio or Jupyter

## Role in AnVIL

Recap of our role, possibly show an updated 'Ideal AnVIL architecture' graphic

Road map

- Standardized, correct containers for essential Bioconductor packages through RStudio & Jupyter. 'Release' and 'devel' flavors. See https://github.com/Bioconductor/AnVIL_Docker (work in progesss)

- R-based Leonardo REST interface -- primarily to help developers. See https://github.com/Bioconductor/AnVIL (nitesh_dev branch until merged)

- Single RStudio / Jupyter instance user interface to AnVIL

  - Access to user and protected data using standard R idioms. Maybe data resources are just 'files' on the file system and no special implementation is required; maybe data resources need to be 'discovered' and presented to the user through some kind of R / Bioconductor based interface.
  
  - Access to 'standard' (??) Firecloud / Terra services -- discover & run services on user and protected data from within R. E.g., perform https://software.broadinstitute.org/firecloud/documentation/article?id=11115 but from an R script.
  
  - Implement R / Bioconductor based firecloud / terra services

Longer-term road map -- 'Ideal AnVIL architecture'

## Demo

- Nitesh
- Vince and BJ

