# robot_learning_and_control
Notes and codes about robot learning and controls
Gaussian distribution(normal distribution)

1. What is Gaussian distribution?
- 
2. Why Gaussian distribution?
- Only two parameters are required, mean and variance, which are easy to compute and visulaize
- Good mathematical properties: (multiplication of two gaussian is a gaussian)
- Central limit theorem: expectation of mean of any random variable is a gaussian distribution
- These points make gaussian a suitable choice for modelling noise and uncertainity
3. Maximum likelihood estimate of gaussian model parameters
- Estimate mean and variance given the observed data
- Likelihood:  $p({x_i} |  \mu, \sigma )$ where $x_{i}$ is observed data and $\mu$ and $\sigma$ are unknown parameters.
- Objective: $\hat{\mu} , \hat{\sigma} = arg max p({x_i} |  \mu, \sigma )$
- assuming independence of observations: $p(x_i |  \mu, \sigma ) = \prod_{i=1}^{n}p(x_i |  \mu, \sigma )$
- The detailed solution is given in the coursera course: It gives the derivation for $\hat{\mu}$ and $\hat{\sigma}$ . The formal one that we use for statistical calculations
4. Multivariate gaussian
- ![image](https://github.com/Shreyash007/robot_learning_and_control/assets/23632463/d8bb90e3-5887-4f8a-9c54-18d1c187d1a4)
- covariance matrix properties
  ![image](https://github.com/Shreyash007/robot_learning_and_control/assets/23632463/381fc4bf-8af9-4076-8d4d-2308fdad95ec)
5. Gaussian mixture model
- ![image](https://github.com/Shreyash007/robot_learning_and_control/assets/23632463/15fb6e65-6807-4c44-820c-ddb45140c91b)
- ![image](https://github.com/Shreyash007/robot_learning_and_control/assets/23632463/92f06a64-80eb-4aa9-b8b7-3f039aba463b)



