Repo for work in the Johns Hopkins Data Science spec

# Level 1 Heading
## Secondary Heading
### Tertiary Heading
#### Level 4 Heading
##### Level 5 Heading
###### Level 6 Heading (lowest level heading)

Unordered List
* First
* Second
* Third


#R Packages
--
## Sources
* Cran
* Bioconductor Project

## List available packages on CRAN

```
a <- available.packages()
head(rownames(a), 3)
```

### Install new packages from CRAN
```
install.packages("slidify", "other_package", "another_package") # install specific packages
```
### Install new packages from Bioconductor
```
source("http://bioconductor.org/biocLite.R")
biocLite() # install basic set of packages
biocList(c("package_name", "another_package_name")) # install specific packages
```

## Loading Installed Packages
```
# Load the ggplot2 package:
library(ggplot2) # NOTE: package is NOT in quotes!!!
```

