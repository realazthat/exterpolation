# Exterpolation


I hereby define the term **_Exterpolation_**.

_Exterpolation_: The **generalization** of "[interpolation](https://en.wikipedia.org/wiki/Linear_interpolation)" and "[extrapolation](https://en.wikipedia.org/wiki/Extrapolation)". _Exterpolation_ **unifies** both meanings - which share identical equations, but over different domains - to also share identical domains. Both linear interpolation and extrapolation can use the "[lerp](https://en.wikipedia.org/wiki/Linear_interpolation#Programming_language_support)" algorithm, but when $0 \le t \le 1$ it is called "interpolation" and otherwise "extrapolation". _Exterpolation_ lets you refer to both at once, for any $t$.

---

From: [wiki/Extrapolation#Linear](https://en.wikipedia.org/wiki/Extrapolation#Linear)

> If the two data points nearest the point $x_*$ to be extrapolated are $(x_{k-1},y_{k-1})$ and $(x_k, y_k)$, linear extrapolation gives the function:
>
> $y(x\_\*) = y\_{k-1} + \frac{x\_\* - x\_{k-1}}{x_{k}-x\_{k-1}}(y_{k} - y_{k-1}).$
>
> (which is identical to [linear interpolation](https://en.wikipedia.org/wiki/Linear_interpolation) if $x_{k-1} < x_* < x_k$)
