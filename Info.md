# Projects on Option Pricing

## European Option Pricing

Pricing a Call or Put Option using Black-Scholes for the formula : 
d1 = [ln(S/K) + (r + (σ^2)/2) * T] / (σ * √T) d2 = d1 - σ * √T Calculate the option price for a European call option (C) and a European put option (P) as follows:

For a European call option: C = S * N(d1) - K * e^(-r * T) * N(d2) For a European put option: P = K * e^(-r * T) * N(-d2) - S * N(-d1) Where:

N(x) is the cumulative distribution function (CDF) of the standard normal distribution. e is the mathematical constant approximately equal to 2.71828. Return the calculated option price (C for call, P for put).
