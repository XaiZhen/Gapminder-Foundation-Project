# Gapminder-Foundation-Project
A project that focused on Visual Data Analytics (VDA) and Exploratory Data Analysis (EDA)

All the dataset that I used to conduct data analysis are all from Gapminder Foundation. I've uploaded all the dataset as well.

For coding, Please Refers to `Gapminder Foundation Project.ipynb` File

<h2>Introduction</h2>
The main objective is to enhance the understanding regarding the relationship among the metrics of GDP growth aligned with Health spending, Income, Human Development Index (HDI) and Life Expectancy of different countries by visual data analytics.


<br>
<br>

<h2> Section 1: Overall analysis on all the datasets </h2>

Key statistics also known as basic statistics, it refers to data sets’ display descriptive statistics (Peck, Olsen & Devore, 2015).  For example, the count of how many variables have been collected, and the mean, maximum and minimum in specific timeframe or from a country. 

The following table is an example of a key statistic analysis for the GDP dataset. However, this example only contains data from 1960 to 1964, and is only intercepted here as an Example.

<p align="center">
<img width="500" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/5b48cd44-52c9-4dff-841f-61c01ccaecbe">
</p>

<p align="center">
Table 1: Descriptive Statistics of GDP csv file
</p>

From the analysis and visualization of key statistics for the five data sets, it can be concluded that all four dimensions are maintaining an upward trend except for the fluctuating per capita spending on health spending. The graph below shows the trend of Total Health Spending as a percentage of per capita GDP.

<p align="center">
<img width="700" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/0960b06d-7333-4d10-a239-450cd2990d4c">
</p>
<p align="center">
Figure 1: Minimum, maximum, and mean of Total Health Spending Percent of GDP from 1995 to 2010
</p>


<h2> Section 2: The effect of GDP on other metrics </h2>
 As can be observed from Figure 2, GDP has a positive linear correlation with all the other four metric, implying that the growth of GDP can lead to the growth of other aspects.
 <p align="center">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/e4a705ca-1db4-4955-bba6-f13deeeddffe">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/cd1c5d0b-7f0a-4835-a729-f6b97b19b959">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/ff647dc1-e9ba-472c-82ed-7c882cdef56d">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/719d529b-6a27-498e-9a9a-2ff650a57078">
</p>
<p align="center">
Figure 2: Correlation between GDPs and other metrics
</p>

<h2> Section 3: Comparison of changes in each metrics for each region </h2>
In this section, South Africa, Germany, China, and Australia will be selected as the representative countries of their region for the comparison of the corresponding indicators, respectively. The time series diagrams of the changes and distributions of the above four countries regarding the five indicators will be plotted separately. 

My method to produce these plots is to generate some DataFrame for the purpose of compare and contrast, and then sketch each plot one by one.
<p align="center">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/35463966-66e2-4dc5-bdbf-ce47ed23eca5">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/9d8d9e88-b6b5-42ba-8e51-a017bfaadbf7">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/19abab77-341d-483f-927d-e7adb37117c2">
<img width="450" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/3fa79d36-f474-475e-b2be-846a3d9a974f">
  </p>
  <p align="center">
Figure 3: Changes and distributions of the four countries regarding the five indicators except GDP growth.
</p>

<h2> Conclusion </h2>

As shown from Figure 3, from the graph on the upper left corner ‘changes in total health spending percent of gdp from 1995 to 2010’，Germany has remained at a high standard, Australia is relatively close to South Africa, and China is at a lower level, with the level gap remaining largely unchanged.

From the time series plot of 'Changes in income', it can be noted that Germany and Australia have maintained a high growth trend after 1950, while China has maintained a high growth trend since 2000, and South Africa has maintained a growth trend but at a slower rate, and the gap with the other three countries has gradually widened.

From the 'Changes in HDI index' time series figure, it can be revealed that the level of Germany and Australia is comparatively higher, and the level of China and South Africa is relatively lower, all four countries show growth, but China and South Africa are growing faster, and the level gap is gradually narrowing.

The time-series plot of 'Changes in life expectancy year' shows that Germany, Australia and China have relatively advanced levels after 2010, while South Africa has a relatively weak level, and the gap is more obvious.

Lastly, from Figure 4, the trend of changes in GPD, it is obvious that the GDP per Capita of every country, except South Africa, indicates a tendency to increase. Certainly, this is related to the development of the country (Clark & Senik, 2011), which can be inferred from the fact that both Germany, Australia and China have made efforts for the development of their respective countries during these 60 years.

  <p align="center">
<img width="600" alt="image" src="https://github.com/XaiZhen/Gapminder-Foundation-Project/assets/157572976/c47dbc66-299b-4c43-8c36-fff5b835ec7c">
</p>

  <p align="center">
Figure 4: Changes in GDP per Capita
</p>

<h2> Reference List </h2>

Clark, A., & Senik, C. (2011). Will GDP growth increase happiness in developing countries?.

Peck, R., Olsen, C., & Devore, J. L. (2015). Introduction to statistics and data analysis. Cengage Learning.

