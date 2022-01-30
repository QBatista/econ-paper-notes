## Hatchondo, Martinez, and Sapriza (2010)

- The topic of this paper is solution methods for default risk models.

- The paper considers models described in Arellano (2008) and Aguiar and Gopinath (2006).

- The paper shows that the choice of solution method matters to accurately solve this model. 

- If one uses a discrete state space technique, a large number of grid points is required to avoid generating spurious movements in interest rates. This implies that this technique is inefficient relative to function approximation methods such as Chebyshev polynomials or spline interpolation.

- In addition, more than half of the spread volatility reported by Aguiar and Gopinath (2006) and Arellano (2008) results from approximation errors.

- This inefficiency depends on the parametrization. It is high when the model features sensitivity of the bond price to the borrowing level for the borrowing levels that are observed more frequently in the simulations.

- The paper makes two observations regarding improvements: (i) find theat equilibrium as the limit of the finite-horizon model and (ii) concentrate grid points in asset levels at which the bond price is more sensitive to the borrowing level and in levels that are observed frequently in simulation.

- The results of the paper cast doubt on the conclusion reached by Arellano (2008) and Aguiar and Gopinath (2006) that income processes with shocks to the growth rate help models of sovereign default generate a countercyclical interest rate.

- The paper also finds that it is computationally costly to eliminate the significant distortions that DSS introduces in the behavior of the interest rate spread for the models presented in Hatchondo and Martinez (2009) and Hatchondo et al. (2007, 2009).

- Finally, the paper describes that iterating jointly on the bond price function and the value function (i.e. "one-loop" algorithm) is significantly faster than iterating on one at a time (i.e. "two-loop" algorithm).
