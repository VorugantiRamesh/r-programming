# R programming
all for loop programms
x<- c (151,174,138,186,128,136,179,163,152,131)
y<- c (63,81,65,91,47,57,96,76,72,62)
#relation<-lm(x~y)
lm=(formula=y~x)
plot(x,y,col="blue",main="height and weight regression ",abline(lm(x~y)),cex=1.3,pch=16,xlab="weight in kg",ylab="height in cm")
