# Assignment-05
if (!require("data.table")) install.packages("data.table")
library("data.table")
DF <- fread("PAYEMS.csv", header= "auto", data.table=FALSE)
View(DF)




