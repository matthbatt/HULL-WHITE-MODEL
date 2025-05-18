# HULL-WHITE-MODEL

The Hull-White model is a widely used short-rate interest rate model in quantitative finance. It extends the Vasicek model by allowing a time-dependent mean reversion level, making it more flexible for calibrating to the current term structure of interest rates. The model is defined by the following stochastic differential equation:

$$dr(t) = [\theta(t) - ar(t)]dt + \sigma dW(t)$$

where:
- $r(t)$ is the short rate at time $t$,
- $a$ is the mean reversion speed,
- $\sigma$ is the volatility,
- $\theta(t)$θ is a function that ensures the model fits the initial yield curve,
- $W(t)$ is a standard Brownian motion.

Thanks to its analytical tractability, the Hull-White model is commonly used to price interest rate derivatives such as caps, floors, swaptions, and Bermudan options.
