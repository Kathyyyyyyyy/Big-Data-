par(mfrow=c(1,1))
L = 55
dta1 = rnorm(L,1,0.5)
dta2 = dta1 + 1
dta3 = cumprod(dta2)
dta4 = dta3 + 1
plot(dta1, type = "l")
plot(dta2, type = "l", col = "blue")
plot(dta3, type = "l", col = "red")
plot(dta4, type = "l", col = "green")
xlab = "day"
ylab = "price"
main = "marti carlo stimulation"

##### In my understanding, this function uses random data to calculate a possible result(the development trend of the data). Through these simulations and calculations, it can eliminate the wrong results, try a new path in the next simulation, and finally get closer to the correct value. In the stock market, this model can help people simulate the changes and volatility trends of stock prices in order to achieve their expected returns. People can get the possible future development of a certain stock through this simulation, compare it with their own expectations, and then decide whether to buy or when to buy.

