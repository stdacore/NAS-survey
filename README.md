# NAS-survey
> A survey on Neural Architechture Search 



## Gradient-based
- [DARTS: DIFFERENTIABLE ARCHITECTURE SEARCH](https://arxiv.org/pdf/1806.09055.pdf)
![](assets/2019-09-20-14-40-58.png)
bilevel optimization problem
![](assets/2019-09-20-14-42-04.png)
approximate $w^{∗}(α)$ by adapting w using only a single training step, without solving the inner optimization
![](assets/2019-09-20-14-42-23.png)
chain rule
![](assets/2019-09-20-14-42-57.png)
finite difference approximation
![](assets/2019-09-20-14-43-29.png)
Evaluating the finite difference requires only two forward passes for the weights and two backward passes for α, and the complexity is reduced from O(|α||w|) to O(|α| + |w|).

- [Progressive Differentiable Architecture Search: Bridging the Depth Gap between Search and Evaluation](https://arxiv.org/pdf/1904.12760.pdf)
![](assets/2019-09-20-14-53-09.png)

- [PC-DARTS: Partial Channel Connections for Memory-Efficient Differentiable Architecture Search](https://arxiv.org/pdf/1907.05737.pdf)
![](assets/2019-09-20-15-21-40.png)

- [SNAS: STOCHASTIC NEURAL ARCHITECTURE SEARCH](https://openreview.net/pdf?id=rylqooRqK7)
- [DARTS+: Improved Differentiable Architecture Search with Early Stopping](https://arxiv.org/pdf/1909.06035.pdf)
![](assets/2019-09-20-12-15-52.png)
![](assets/2019-09-20-12-17-01.png)
## Others

- [PROXYLESSNAS: DIRECT NEURAL ARCHITECTURE SEARCH ON TARGET TASK AND HARDWARE](https://arxiv.org/pdf/1812.00332.pdf)
![](assets/2019-09-20-12-37-25.png)
![](assets/2019-09-20-12-38-50.png)
![](assets/2019-09-20-12-53-49.png)
![](assets/2019-09-20-12-40-14.png)
![](assets/2019-09-20-12-39-48.png)
![](assets/2019-09-20-12-41-17.png)
![](assets/2019-09-20-12-41-37.png)
![](assets/2019-09-20-12-43-37.png)
- [FairNAS: Rethinking Evaluation Fairness of Weight Sharing Neural Architecture Search ](https://arxiv.org/pdf/1907.01845.pdf)
- [MANAS: Multi-Agent Neural Architecture Search](https://arxiv.org/pdf/1909.01051.pdf)
- [Network Pruning via Transformable Architecture Search](https://arxiv.org/pdf/1905.09717.pdf)
- [Understanding and Simplifying One-Shot Architecture Search](http://proceedings.mlr.press/v80/bender18a/bender18a.pdf)







#### New image
1. `Cmd+Ctrl+Shift+4`
2. `Cmd+Alt+V`

#### Preview
`Cmd+K V`
