## 2022 MCM (Problem C): Trading Strategy Design for Bitcoin and Gold

### **Highlights**
- Used traditional technical analysis, GFTD timing signal and rotation strategy to design basic trading strategies <br>
- Proposed dynamic fusion method from portfolio optimization to optimize the weight allocation <br>
- Performed robustness checking and sensitivity analysis towards transaction costs <br>

### **Results Overview**
- Rotation strategy

  <img src="./images/rotation.png" width="700">

- GFTD signal hyperparameter grid search (bitcoin only) with RoMaD metric

  <img src="./images/gftd_heat_bitcoin.png" width="600">

- Dynamic strategy fusion pipline

  <img src="./figures/fusion.png" width="700">

- Proportion of individual strategy in the fused version

  <img src="./figures/scale-component-ready.png" width="700">

- Cumulative return of investors with different levels of risk preferences

  <img src="./figures/gamma.png" width="700">

- Effect of commission fee with portfolio terminal value

  <img src="./figures/scale-update-return-alpha.png" width="750">


- Commission fee ratio and transaction frequency

  <img src="./figures/commission-gamma.png" width="700">




