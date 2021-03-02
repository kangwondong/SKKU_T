# SKKU_T
hi
install.packages(c("usethis","remotes"))
remotes::install_github("rstudio/rmarkdown")
install.packages("postcards")

library(postcards)
create_postcard()

install.packages("distill")
library("distill")
create_website(dir=".",title="iyo-distill",gh_pages=TRUE)