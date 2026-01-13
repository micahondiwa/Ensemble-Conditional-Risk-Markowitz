# Ensemble-Conditional-Risk-Markowitz

- This is a Capstone project for *the [MSc in Financial Engineering at WorldQuant University](https://www.wqu.edu/mscfe)*

- Jupyter Notebook with Complete Code: [Smart_Portfolio_CVaR_Optimization_Complete.ipynb](Smart_Portfolio_CVaR_Optimization_Complete.ipynb)

**TL;DR**:  *We present a novel approach of jointly foresating covariance matrix and returns using deep ensemble models and feeding the forecasts as inputs to a classical Markowitz model.* 

### **Abstract**
Portfolio optimization is a key aspect in investment management, yet popular techniques like Markowitz still struggle with setbacks such as handling market drawdowns, estimating errors,  and using suitable covariance estimation methods. Researchers have leveraged machine and deep learning to estimate returns used as inputs in Markowitz. However, this recently popular approach of estimating only the returns is proven to be prone to setbacks such failure to fully capture market drawdowns. This study introduces a novel approach, the Smart Ensemble Conditional Risk (ECR) Markowitz framework, that uses deep learning ensemble architectures to jointly forecast returns and covariance matrix in market-aware conditions. The approach addresses the limitations in the conventional approaches such as the Ledoit-Wolf Shrinkage and EWMA by incorporating conditional value at risk (CVaR) for tail risk management and using portfolio-aware regularization. Prior to implementing the ECR method, the study focuses on a thorough asset pre-selection where 100 assets are arbitrarily selected from diverse markets and asset categories for the period between 2015 and 2025, and then using both greedy selection and cluster-based selection, the portfolio is reduced to 22 investable assets and 1 asset representing the market returns. The models were trained on daily returns aggregated to monthly returns and 30 days rolling window to capture short-term noise and consistent trends. The backtesting results reveal a superior performance of the smart ensemble variant, achieving the highest Sharpe ratio (1.114), with a maximum drawdown of -0.087, and CVaR(95%) of -6.3%, outperforming the individual models. This study is an advancement to the ongoing research on portfolio construction, and offers practical implications for risk-averse investors in a dynamic market. 

Contributors:
1. [Micah Ondiwa](https://github.com/micahondiwa)
2. [Charles Etim](https://github.com/chefet)
3. [Maurice Ogedegbe](https://github.com/ogedegbem)
