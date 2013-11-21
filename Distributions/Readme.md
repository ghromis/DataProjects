```R
sample <- rnorm(100, mean=1, sd=2)
hist(sample, prob=TRUE, yaxt='n', main="Best fitting normal curve", ylab="", xlab="Data sample")
curve(dnorm(x, mean=mean(sample), sd=sd(sample)), add=TRUE, col="blue", lwd=2.5)
```
