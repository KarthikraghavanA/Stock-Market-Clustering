# *Machine Learning 5 - Stock Market Clustering*

In this project, we will be extracting live stock market data from Yahoo finance. We will find similarities among various companies using their stock market prices and then cluster them into differeent clusters using **K Means Algorithm**
<br>

This is an **Unsupervised learning problem**, we will use clustering a algorithm.

We will also use *pandas_datareader* to extract live data from Yahoo finance site.
We will be visualizing the data along with preprocessing, see trends, We will do a real time comparison between or Analysis and Data from Yahoo Stock Market.

------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/112689649/211175557-1e43909c-1948-46dc-9228-cad85bbfed09.png)

"pandas_datareader" extract data from variouse internet sources into a Dataframe. Curently the following sources are supported

* Yahoo! Finance
* Google Finance
* St. Louis FED (FRED)
* Kenneth French's data library
* World Bank
* Google Analytics


You can visit https://finance.yahoo.com/ to search for companies<br>
Refer https://stackoverflow.com/questions/74832296/typeerror-string-indices-must-be-integers-when-getting-data-of-a-stock-from-y in case there are issues while loading pandas_datareader

![image](https://user-images.githubusercontent.com/112689649/211181396-a067e95e-dfba-4961-a97a-6ed76d4a7fdf.png)


If there are any issues with pandas_datareader, we can use yfinance

![image](https://user-images.githubusercontent.com/112689649/211180738-0267c497-510f-437f-a7da-c480486b61fb.png)
![image](https://user-images.githubusercontent.com/112689649/211180718-55cd893c-a811-4787-91a6-8bc6dee077cd.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

* data_source = 'yahoo'
* start_date = '2015-04-25' - YY-MM-DD
* end_date = '2020-04-25' - YY-MM-DD

![image](https://user-images.githubusercontent.com/112689649/211184856-73eaf084-cb32-4fcc-8886-b318e8d16a94.png)


We also used PCA to reduce the dimensions after normalizing the dataset

![image](https://user-images.githubusercontent.com/112689649/211185153-8a6f06eb-b620-459e-8f48-fd2767dc9095.png)

