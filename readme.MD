```math
softmax(x_i) = \frac{e^{x_i}}{\sum_{j}{e^{x_j}}} = \frac{e^{x_i -x_{max}}}{\sum_{j}{e^{x_j-x_{max}}}} = \frac{e^{x_i-x_{max}}}{\sum_p{\sum_{k}{e^{x_k-x_{max}}}}} \tag{3}
```
```math
x_{max} = MAX_p(MAX_k(x_k)) \tag{4}
```
