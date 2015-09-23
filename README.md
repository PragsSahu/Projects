# Projects
------Preparing Data------------

reading the sms collection data into the sms_orig data frame
```{r}
sms_orig <- read.csv("sms_spam.csv", stringsAsFactors = FALSE)
str(sms_orig)
```
