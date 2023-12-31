<h1 align = "center"> AI Stock Picker </h1> 

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
</p>

While traditional investment in stocks is a laborious, arduous, confusing, demanding,
and time-consuming task, this project aimed to optimize, fasten, and smoothen the process.
With this project, an investing Artificial Intelligence has been created which could pick
stocks for the user. The stocks are picked based on the user's financial power.
To this end, core Python, a plethora of machine learning algorithms, and libraries have been used. This is a data-driven approach to the world of stock markets. The consumer gets to
choose how aggressive or defensive one wants to be when investing. The end user
needs to worry least about losses while celebrating assured profits with each investment
and trade. Value investing strategy has been devised which has been proven to work over
time, notably by prominent investors like Warren Buffett and Charlie Munger.

<h2 align = "left"> Tools and Tech Used </h2> 

* Python
* Jupyter Notebook
* Python Libs:
  * Numpy
  * Pandas
  * Keras
  * CV2
  * Matplotlib
  * Scipy
  * Scikit-learn
* ML Algos:
  * Linear Regression
  * Elastic-Net Regression
  * K-Nearest Neighbors
  * Support Vector Machine Regressor
  * Decision Tree Regressor
  * Random Forest Regressor
    
  
    
<h2 align = "left"> What did the AI do? </h2>
* Selected stocks from March 2021 to be held for one year
* 2020 stock selection: https://www.blockchain.com/btc/tx/4234bd073d7c261b490789ddb59bf2adc3192b89cfc22ca84ed04d353cf69396
* 2021 stock selection: https://www.blockchain.com/btc/tx/e01ce40222389e3af2a8356961f096033f2568d72202097f4aa779fb0ea60589


<p align = "center">
<img src = "/mindmap.png" alt="mindmap" height = 300 width = 500/>
<h5 align = "center"> Project Mindmap </h5> 
</p>

<h2 align = "left"> Goals Achieved </h2>
  1. Obtained Financial Data and Stock Performance Data of the previous years(historical data). <br>
  2. Used existing algorithms to see if we have any predictive power between financial data 'now' and the stock performance 'a year from now'. <br>
  3. The financial data was used to create our features(X matrix) and the stock performance over the year after that financial data was released was the y vector. <br>
  4. Checked the models to see if they have predictive power, for the ones that did, used those models to create value-investing AIs. <br>
  5. Then, backtested the investing methods with the historical data to identify the best-performing algorithms. <br>
  6. Picked the winner and tweaked it further for performance improvements. <br>

<h2 align = "left">Few Visualizations </h2>
<h3 align = "left">Prediction Analysis </h3>

<p align = "center">
<img src = "/Visualizations/lr.png" alt="lr" height = 300 width = 300/>
<h5 align = "center"> Linear Regression Prediction </h5> 
</p>
<br>

<p align = "center">
<img src = "/Visualizations/enr.png" alt="enr" height = 300 width = 300/>
<h5 align = "center"> Elastic Net Regression Prediction </h5> 
</p>
<br>

<p align = "center">
<img src = "/Visualizations/knn.png" alt="knn" height = 300 width = 300/>
<h5 align = "center"> K-Nearest Neighbors Regression Prediction </h5> 
</p>
<br>

<p align = "center">
<img src = "/Visualizations/svm.png" alt="svm" height = 300 width = 300/>
<h5 align = "center"> Support Vector Machine Regression Prediction </h5> 
</p>
<br>

<p align = "center">
<img src = "/Visualizations/dec_Tree.png" alt="dec_Tree" height = 300 width = 300/>
<h5 align = "center"> Decision Tree Regression Prediction </h5> 
</p>
<br>

<p align = "center">
<img src = "/Visualizations/rfr.png" alt="rfr" height = 300 width = 500/>
<h5 align = "center"> Random Forest Regression Prediction </h5> 
</p>
<br>
<br>

<h3 align = "left">AI Backtesting </h3>
 <p align = "center">
<img src = "/Visualizations/portfolio_backtest_returns.png" alt="portfolio backtest returns" height = 300 width = 300/>
<h5 align = "center"> Portfolio Backtest Returns </h5> 
</p>
<br>

<p align = "center">
<img src = "/Visualizations/plot_backtest_with_sp500.png" alt="plot backtest with sp500" height = 300 width = 300/>
<h5 align = "center"> Plot Backtest with S&P500</h5> 
</p>
<br>
<br>

<h3 align = "left">Result </h3>
<p align = "center">
<img src = "/Visualizations/final.png" alt="final" height = 300 width = 500/>
<h5 align = "center"> The model picks stocks!</h5> 
</p>
<br>

<h2 align = "left">Disclaimer </h2>
No guarantee or other promise as to any results that may be obtained from using the content. You should never make any investment decision without first consulting with your financial advisor and conducting your research and due diligence.

# License
```xml
Designed and developed by 2023 semani01 (Sai Emani)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
