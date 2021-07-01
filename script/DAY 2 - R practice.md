par(mfrow=c(1,1))
L = 50
dta1 = rnorm(L,0,0.05)
dta2 = dta1 + 1
dta3 = cumprod(dta2)
matplot(cbind(dta1,dta2,dta3), type = "l", xlab = "Time", ylab = "Price", main = "Marti carlo simulation")

##### In my understanding, this function uses random data to calculate a possible result(the development trend of the data). Through these simulations and calculations, it can eliminate the wrong results, try a new path in the next simulation, and finally get closer to the correct value. In the stock market, this model can help people simulate the changes and volatility trends of stock prices in order to achieve their expected returns. People can get the possible future development of a certain stock through this simulation, compare it with their own expectations, and then decide whether to buy or when to buy.

