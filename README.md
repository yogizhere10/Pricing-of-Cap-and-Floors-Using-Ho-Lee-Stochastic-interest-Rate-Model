# Pricing-of-Cap-and-Floors-Using-Ho-Lee-Stochastic-interest-Rate-Model
#### Fixed income bonds and derivatives are complicated financial instruments whose pricing is often conditional on the path of interest rates in the future. The assumption that current rates will remain 'static' is overly simplistic, especially when one needs to price a security with embedded options (ex: swaption, cap, floors, etc.).
#### The Ho-Lee model was introduced in 1986 by Thomas Ho and Sang Bin Lee. Generally, it defines a short rate to follow a stochastic process:
                                                   $dr^* = θ(t) dt + σ dZ^*$
#### The drift term, θ(t)dt, is time-varying which allows the model to be calibrated to match a given term structure of interest rates (by varying theta each period). Thus, the model will produce rates that can price a zero coupon bond in any given month to match market prices. One potential downside of this model is that it allows interest rates to become negative, which many practictioners sought to avoid because it seemed unlikely that would ever occur in real markets. However, recent negative interest rate environmetns in Japan and Europe over the past decade could make this model more plausible moving forward.



