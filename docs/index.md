# Bioconductor / AnVIL Project Activities

**Note** All resources on this page are under development.

## About

This site summarizes ongoing [_Bioconductor_][] development activities
related to _AnVIL_.

[_Bioconductor_][] is a successful open-source project for the
statistical analysis and comprehension of high throughput genomic
data. _Bioconductor_ is based on the _R_ programming language. It
consists of more than 1600 [_R_ packages][] contributed by more than
1000 maintainers world-wide. _Bioconductor_ packages are downloaded to 1/2
million IP addresses annualy. There are more than 29,000
[PubMedCentral citations][] to _Bioconductor_. _Bioconductor_ has an
active [support site][] and [community slack][].

[_AnVIL_][] is a US National Institutes of Health / National Human
Genome Research Institute initiative to develop a Genomic Data Science
Analysis, Visualization, and Informatics Lab-space (AnVIL).

Ultimately, _AnVIL_ will provide the ability to launch RStudio,
Jupyter notebook, and other _R_ / _Bioconductor_ resources in a
computational cloud. The _AnVIL_ environment will provide secure access
to large-scale as well as individual data resources, and to scalable
cloud-based computational environments.

[_Bioconductor_]: https://bioconductor.org
[_AnVIL_]: https://www.genome.gov/27569268/genomic-analysis-visualization-and-informatics-labspace-anvil/
[_R_ packages]: https://bioconductor.org/packages
[PubMedCentral citations]: https://www.ncbi.nlm.nih.gov/pmc/?term=bioconductor&sort=ePubDate
[support site]: https://support.bioconductor.org
[community slack]: https://bioc-community.herokuapp.com/

## Current activities

[AnVIL package][]

- This _R_ package currently provides both developer-oriented and
  user-oriented AnVIL-specific functionality.
  
- (available) Developer-oriented access to major AnVIL components (Terra,
  Leonardo, Dockstore, and Gen3) REST APIs.
  
- (under development) Developer- and user-oriented facilities for
  interacting with the Google cloud, e.g., `localize()`,
  `delocalize()`, `sync()`.
  
- (under development) User-oriented facilities for package
  installation from precompiled binaries.

[AnVIL package]: https://github.com/Bioconductor/AnVIL

[_Bioconductor_ containers][]

- (available) These Docker containers provide the system dependencies (e.g.,
  software libraries) to install 'all of' _Bioconductor_. The
  containers can be used locally or deployed in the _AnVIL_ /
  _Leonardo_ application. 
  
- (under development) Because the software environment is fixed by the
  container, packages can be pre-built and rapidly installed simply by
  copying from an online repository. We are developing the tooling to
  support this repository (as folders in google buckets) and to
  facilitate easy installation (via the [AnVIL package][] `install()`
  function).

[_Bioconductor_ containers]: https://github.com/Bioconductor/bioconductor_full

## Project management

Some visibility into _Bioconductor_-specfic project management,
including current developement effort and short term (1 year) plans
are available as [github projects][].

[github projects]: https://github.com/Bioconductor/AnVIL_Admin/projects
