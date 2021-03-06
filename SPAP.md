# Structured Pyramid Analysis Plans
The rationale for using a structured plan is to avoid the very inefficient process of exploring a data set aimlessly, without hypotheses. This is especially true for analytics teams, that would have a difficult time collaborating without roadmap to use for direction.
 An SPAP is outlined in the following image. The terms are defined beneath it.
 
 
 ![sasp_ideal](https://user-images.githubusercontent.com/60514533/74491635-35a29900-4e9a-11ea-9df6-32c54d0a7e5a.PNG)

## SPAP for the Dataset:

![WhatsApp Image 2020-02-13 at 9 02 49 PM](https://user-images.githubusercontent.com/60514533/74494913-55d75580-4ea4-11ea-8783-52891622b6a3.jpeg)


#### SMART Goal:
Analyzing the different aspects such as growth of the country, population density, Economic condition, Mortality rates of the country and various other factors which can lead to the increment or decrement of the life expectancy.
#### Dependent Variables:
Life Expectancy
#### Specific Questions to Investigate:
1. Impact of life expectancy on developing countries.                                                                                       
2. Impact of life expectancy on developed countries.
#### Independent Variables:
Status, Adult Mortality, infant deaths, percentage expenditure, Hepatitis B, Measles, Polio, Diphtheria, under-five deaths, Alcohol, HIV/AIDS, BMI, Total expenditure, GDP, Population, thinness 1-19 years, thinness 5-9 years, Income composition of resources, Schooling.

# Key Performance Indicator:


|Sr No. |Variable Name            |Description                                                                                  |
|-------|-------------------------|---------------------------------------------------------------------------------------------|
|1.	    |Life expectancy          |Life Expectancy in age                                                                       |
|2.	    |Status                   |Developed or not Developed Country                                                           |
|3.	    |Adult Mortality          |Mortality Rates of both sexes                                                                |
|4.	    |Alcohol                  |Alcohol, recorded per capita (15+) consumption                                               |
|5.	    |Percentage expenditure   |Expenditure on health as a percentage of Gross Domestic Product per capita(%)                |
|6.     |BMI                      |Body Mass Index of entire population                                                         |
|7.     |Total expenditure        |General government expenditure on health as a percentage of total government expenditure (%) |
|8.    |HIV/AIDS                 |Deaths per 1 000 live births HIV/AIDS (0-4 years)                                            |
|9.    |GDP                      |Domestic Product per capita (in USD)                                                         |
|10.    |Population               |Population of the country                                                                    |
|11.    |thinness 5-9 years                      |Prevalence of thinness among children for Age 5 to 9(%)                             |
|12.    |thinness 1-19 years               |Prevalence of thinness among children and adolescents for Age 10 to 19 (% )           |
|13.    |Income composition of resources      |Income composition of resourcesHuman Development Index                                       |
|14.    |Schooling                |Number of years of Schooling(years)                                                          |

## Hypothesis testing:
In this project we are analyzing the factors that affects the life expectancy of many countries across the globe from the year 2000 to 2015.

#### Hypothesis: - 1
H0 = In this hypothesis we consider that how economic factors contribute to life expectancy i.e. Life expectancy rate is expected to be less if the economy of a country is low.

H1= In this hypothesis we consider that not only economic factor contributes to life expectancy but also other factors like literacy, health, income etc. can affect life expectancy.

#### Hypothesis: - 2
H0 = In this hypothesis we consider that how health affects the life expectancy i.e. Diseases like HIV, Measles, diphtheria, polio etc. can reduce life expectancy of a country.

H1= In this hypothesis we consider that not only health affects life expectancy but also other factors like Schooling, GDP, economy can contribute to life expectancy.

#### Hypothesis: - 3
H0 = In this hypothesis we consider how the literacy of the country affect life expectancy i.e. How well educated the people are in the country, the life expectancy is higher.

H1= In this hypothesis we consider that not only literacy affects life expectancy but, also other factors like health, revenue etc. contribute towards the life expectancy.


## Summary Analysis:
This provides the summary distribution of dataset of how widely the data has been spread.

![summary](https://user-images.githubusercontent.com/60514533/74390812-5999a800-4dd0-11ea-8bac-2545ac6d2dca.PNG)

## Regression Analysis:

We know that lower the p-value (<0.05), more is the significance. From the below analysis we can observe the p values which may play more significant role than the others.

![WhatsApp Image 2020-02-13 at 2 17 20 PM](https://user-images.githubusercontent.com/60514533/74492121-c29a2200-4e9b-11ea-8037-8cde16504fa7.jpeg)


# Correlation Scatter Plot matrix:
This plot shows the correlation of target variable vs all dependent variables.Correlation ranges from -1 to 1.Value towards -1 are negatively correlated and values towards 1 are positively correlated and if the correlation is 0 then there is no relationship between the variables. Positive and negative determines the direction of the relationship of the given two variables, While the number indicates the strength of the relationship between two variables.

We can observe that Income composition, Schooling, Alcohol, Percentage expenditure, GDP, BMI are positively correlated while Adult mortality and HIV aids and thinness are negatively correlated. Population, Infant deaths and Under five deaths are less correlated.

![WhatsApp Image 2020-02-13 at 7 53 32 PM](https://user-images.githubusercontent.com/60514533/74492594-6932f280-4e9d-11ea-9b34-6aeb79a275d2.jpeg)
![WhatsApp Image 2020-02-13 at 8 02 22 PM](https://user-images.githubusercontent.com/60514533/74494063-ec564780-4ea1-11ea-82ca-439e0106809d.jpeg)

#### Code:                                                                                            

![WhatsApp Image 2020-02-12 at 7 32 40 PM](https://user-images.githubusercontent.com/60514533/74390220-982e6300-4dce-11ea-95b2-21970f0119e1.jpeg)
