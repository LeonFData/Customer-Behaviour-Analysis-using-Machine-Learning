# Customer-Behaviour-Analysis-using-Machine-Learning
My project: Applied machine learning methodologies in financial service and banking industry

- In the coming years, robotic financial advisors may come to have a significant role in banking and asset management areas. 
<p align="center">
  <img width="450" src="https://github.com/LeonFData/Customer-Behaviour-Analysis-using-Machine-Learning/blob/master/pics/Forecast-of-robo-advisory-services-adoption-rate.jpg">
</p>

* From a practical point of view, 'robot' works can not replace the real financial adviors rightnow, one of the advantages of this new technology is to narrow the gaps between adviors and customers – according to the report the real time risk exposure to clients' portfolios, make the better decision on asset allocation by using making enough full use of the data source.

- As a **research data analyst** in [**financial data analytics lab**](https://www.cqam.ca/financial-data-analytics-lab), I was working on a project to build a ML system to recognize clients' trading behaviour patterns and make classification of the risk levels. 

- Due to the **Non-Disclosure Agreement**, I am **NOT** able to release the data sources, details of methods, and codes on the pulic platform. Here, by using the other data sources (unrelated to my project), I'd like to share some methodologies which can effectively deal with the time series data, and the mixed type of data source. Also, I would share the feature engineering insights when doing the customer behaviour analysis. 

- **This part of knowledge should be free and shared**:
  * Denoising methods: time series data can be denoisd in order to extract undelying trends (click [**here**](https://github.com/LeonFData/Customer-Behaviour-Analysis-using-Machine-Learning/blob/master/notebook/denoise.ipynb))
    * Wavelet transform
    * Averaging smoothing
  * Feature engineering tips: some general features (usually works, try them first) (click [**here**](pics/feature_engineering.png))
  * K-prototypes (mixed data clusteing): dealing mixed numeric and categorical data in the real world (click here)
  * Dynamic time warping (DTW): clustering of time series data (click here)
  * Time series data modeling
    * Moving Average
    * Exponential Moving Average
    * Holt Linear
    * ARIMA
    * Prophet (Facebook opensource tool)
    * Convolutional Neural Network
    * Long-Short-Term-Memory (LSTM)
