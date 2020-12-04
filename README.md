# DS 200 Research Methods Plot Assignment
This Repository is for the credit requirement of DS 200: Research Methods. All the plots in this repository was made possible with the data from [https://data.gov.in](https://data.gov.in) **A Digital India Initiative**. All the data used here is only relevant to India.

## Bar plot

### Data description: 

[State/UT wise Accidents Victims Killed according to classification of Age and Sex during 2017]()

This data contains state wise statistics about number of fatal road accidents that happened in the year 2017. The data is further categorized by Age groups and Sex.

Below is the screen shot of the columns in the data.

*Dataset 1* ![alt text](https://github.com/bikipanda/DS-200-Research-Methods-Plot-Assignment/blob/main/Bar%20Plot/columns_bar.PNG)

### Plot:

Below is the plot comparing number of road accidents of different Age groups and between different Sex.

![alt text](https://github.com/bikipanda/DS-200-Research-Methods-Plot-Assignment/blob/main/Bar%20Plot/Fatal%20Accidents%20by%20Age%20and%20sex%20in%202017%20plot.jpg)

### Observations:
1. The number of men killed in road accidents is more than number of women killed for every age group.(This could be due to the fact that there are more male drivers than female drivers.)
2. By carefully observing the two largest age groups **18-25** age group and **25-35** age group, we can conclude that the Average number of Accidents per "year age" in the **age group 18-25 (Male:30148/7 = 4307 | Female: 4096/7 = 585)** is the greater than the **age group 25-35 (Male: 34728/10 = 3473 | Female: 4821/10 = 482)**. Infact it is the highest among all age groups, regardless of the gender
3. So,we can say younger inexperienced drivers are the cause for higher rate of accidents across both genders.

## Box plot

### Data description: 

[State/UT wise Per Capita Consumption of Petroleum Products from 2012-13 to 2018-19](https://data.gov.in/resources/state/ut-wise-per-capita-consumption-of-petroleum-products-from-2012-1)

This data contains state/UT wise statistics about consumption of Petroleum Products from 12-13 to 18-19.

Below is the screen shot of the columns in the data.

*Dataset 2* 

![alt text](https://github.com/bikipanda/DS-200-Research-Methods-Plot-Assignment/blob/main/Box%20Plot/Petroleum%20column.PNG)

```bash
Telangana data is not available for 2012-13 and 2013-14 because it was formed in June 2014.So I copied Andhra Pradesh's data into it.
```

### Plot:

Below is the Box plot comparing the trends of Petroleum Products usage in our country from 2012-13 to 2018-19.

![alt text](https://github.com/bikipanda/DS-200-Research-Methods-Plot-Assignment/blob/main/Box%20Plot/Per%20capita%20consumption%20of%20petroleum%20Products%20in%20Kg%2012-18.jpg)

### Observations:
1. The average usage of petroleum products in our country has increased by a very thin margin from 2012 to 2018.
2. Observe the two farthest outliers for each Year, they are the union Territories, **Dadar and Nagar Havelli**(farthest) and **Daman and Diu** (closer).For these two union territories, the per capita in Kg usage of petroleum products has almost close to doubled from 706(2012) to 1160(2018) for Dadar and Nagar Havelli and 532(2012) to 910(2018) for Daman and Diu.
3. Apart from 'Dadar and Nagar Havelli' and 'Daman and Diu' , there are two more union territories which also are outliers but not to much extent.Those are **Goa** and **Puducherry**.

## Scatter plot

### Data description: 

[Bio-chemical (CAB) 2014 Survey data of the district Jajapur (Odisha)](https://odisha.data.gov.in/resources/clinical-anthropometric-bio-chemical-cab-2014-survey-data-district-jajapur-odisha#web_catalog_tabs_block_10)

This data contains medical data of the people living in the Jajapur district of Odisha.I have used this data to see the correlation between age and BMI for the people in that district.

I have removed all the entries which had Nan in their Height or Weight catergory.
I have removed all the entried which had Weights and lenght calculated for unborn babies.
I have removed some of the columns which I didn'nt need for calculating the BMI.
I converted the Height in centimeters to meters and calculated the BMI by the formula BMI = Weight in Kg / (ht in mtrs)^2

Below is the screen shot of the columns in the data.The columns **BMI** and **Height_m** are calculated and added by me.

*Dataset 3* 

![alt text](https://github.com/bikipanda/DS-200-Research-Methods-Plot-Assignment/blob/main/Scatter%20Plot/columns%20scatter.PNG)


### Plot:

Below is the Box plot comparing the trends of Petroleum Products usage in our country from 2012-13 to 2018-19.

![alt text](https://github.com/bikipanda/DS-200-Research-Methods-Plot-Assignment/blob/main/Scatter%20Plot/Age%20vs%20BMI%20in%20People%20of%20Jajapur%20(Odisha)%202014.jpg)

### Observations:
1. The average usage of petroleum products in our country has increased by a very thin margin from 2012 to 2018.
2. Observe the two farthest outliers for each Year, they are the union Territories, **Dadar and Nagar Havelli**(farthest) and **Daman and Diu** (closer).For these two union territories, the per capita in Kg usage of petroleum products has almost close to doubled from 706(2012) to 1160(2018) for Dadar and Nagar Havelli and 532(2012) to 910(2018) for Daman and Diu.
3. Apart from 'Dadar and Nagar Havelli' and 'Daman and Diu' , there are two more union territories which also are outliers but not to much extent.Those are **Goa** and **Puducherry**.