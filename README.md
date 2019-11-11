remove.packages("rstan")
if (file.exists(".RData")) file.remove(".RData")
Sys.setenv(MAKEFLAGS = "-j4") # four cores used
install.packages("rstan", type = "source")
