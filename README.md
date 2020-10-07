# SigRepoR version 0.1.0
## OmicSignature & OmicSignatureCollection

### last update
09/24/2020
contact: `vmli@bu.edu`

### installation
`devtools::install_github(repo = "Vanessa104/SigRepoR", auth_token = "...")`  
`library(SigRepoR)`  
`SigRepoR::testRepo(10) # a simple function to test if it’s working`  

### description
**Please go to "/vignettes/OmicSig-vignette.Rmd" to see the vignettes of _OmicSignature_ and _OmicSignatureCollection_ R6 objects**
As high-throughput technology evolves, a large number of omics-signatures are being derived. This package contains _OmicSignature_ and _OmicSignatureCollection_ R6 objects to store signatures efficiently and retrieve them conveniently.

### development notes
Run `roxygen2::roxygenize()` to update help documentation
Run `devtools::build_vignettes()` to build vig.
Run `devtools::check()` to makes sure the package builds and all tests pass
Run `BiocCheck::BiocCheck()` if you’re really ambitious
Run `pkgdown::build_site()` to update the usage documentation / package landing site

