# Malaria Project

## Introduction

This project aims to analyse the Malaria datasets collected by the World Health Organisation (WHO) and gain insights into the trends and patterns of Malaria cases across different countries and regions. The analysis revealed that despite the medical advances, the number of cases worldwide keeps increasing due to various factors, including insufficient funding for prevention and control effects, climate change is also believed to contribute to the spread of malaria as higher temperatures are more favourable to mosquitoes. **[Interactive Python Visualisations](https://nbviewer.org/github/k-kabithan/Malaria_Project/blob/main/Malaria_Project.ipynb)**

### Why did you choose to undertake this project?
I chose to undertake this project because I am passionate about global health and the fight against infectious diseases. Malaria is a major public health issue, especially in developing countries, and I wanted to use my skills in data analysis to help shed light on the problem and identify potential solutions. I believe that data analysis can play a crucial role in understanding the complex factors that contribute to the spread of malaria and in developing more effective strategies for prevention and treatment.

## Data

### Brief explanation of the Malaria dataset used in the project.
The dataset was analysed using Python to identify correlations between the number of cases and deaths, and factors such as the region and year. The dataset includes information on the number of new malaria cases per 1000 population at risk per year, reported cases and fatalities per countries alongside the WHO regions, and other various properties.

### Source of the dataset.
Data sets was made by the World Health Organisation (WHO), it contains small variety of data such as the country, WHO region, number of cases and number of deaths. This data was collected between 2000-2017.  **[Kaggle Malaria Data](https://www.kaggle.com/datasets/imdevskp/malaria-dataset)**

### Explanation of the features included in the dataset.
As mentioned both data sets had similar columns: Country, Year, Number of cases, Number of deaths, WHO region. WHO regions are regions in the world that the World Health Organisation divided for the purpose of reporting and analysing. Both data sets had missing values in different countries and time period, "NULL", values which were dropped for the sake of having clean data where it would be easier to manipulate and analyse. For  further analysis, the data types were modified to best represent the column such as converting them to int, this significantly simplified the coding process. No further modifications were necessary, besides changing the column names to make it more clear and to have an easier time for future modifications or analysis.


## Questions to answer

    What are the global trends in Malaria cases and mortality?
    Which countries or WHO regions have the highest burden of Malaria?
    How has Malaria cases and mortality changed over time?
    
### Explain how these questions relate to the project's purpose.
The questions related to the Malaria dataset are closely tied to the project's purpose. The aim of the project is to explore the patterns and trends in Malaria cases, deaths, and other relevant factors to gain insights into the global impact of the disease and inform future prevention and control efforts.

By analysing the number of cases and deaths by region, the project aims to identify regions with the highest cases of Malaria and inform targeted interventions to reduce the burden of the disease in those specific areas. The examination of the correlation between Malaria cases and deaths will help to identify factors that contribute to the severity of the disease and inform treatment strategies. Exploring the impact of climate change on the spread of Malaria and the effectiveness of prevention and control efforts will also inform future public health policies.

## Methodology

### Brief explanation of the methods used to analyse the dataset.
Throughout this project, only Python was used to perform data cleaning, analysis and visualisation. The Pandas library was used to load and manipulate both datasets, and the NumPy library was used for mathematical claculations. Data visualisation was performed using the Matplotlib library to create plots and charts to help identify trends and correlation in the data.

## Results

### Visualisations and graphs used to present the results.
![Figure 1](https://user-images.githubusercontent.com/55809600/223190004-d41bb353-11ea-4fab-8704-eb5b9fbbd310.png) Figure 1: Top 10 countries highest number of cases between 2000-2017

![Figure 2](https://user-images.githubusercontent.com/55809600/223190393-da19ee1e-bd4e-44a1-b60e-ceef77944189.png) Figure 2: Top 10 countries highest number of deaths between 2000-2017

![Figure 3](https://user-images.githubusercontent.com/55809600/223190462-28cbcfba-647e-421a-8f30-6e7c63c58d29.png) Figure 3: Total number of Malaria cases between 2000-2017

![Figure 4](https://user-images.githubusercontent.com/55809600/223190664-f4da26ef-82e9-4b70-829c-22fa73178e23.png) Figure 4: Total number of Malaria deaths between 2000-2017

![Figure 5](https://user-images.githubusercontent.com/55809600/223191088-63e50e48-a13d-411f-bd21-d4d948eda0bd.png) Figure 5: Total Malaria cases and deaths globally

![Figure 6](https://user-images.githubusercontent.com/55809600/223191239-18411881-9519-43a3-baf6-5666df1d2cc6.png) Figure 6: Malaria cases in Republic of the Congo between 2000-2017

### Explanation of the key insights and findings.
In the analysis, it was found that the Republic of the Congo had the highest number of Malaria cases between 2000-2017, with a total of approximately 75 million recorded cases (Figure 1). This indicates that Congo is particularly vulnerable to the disease and may require targeted interventions to reduce this number. Further analysis could potentially explore and uncover the reasons as to abnormal amount of cases when compared to the country with the 2nd highest total cases, Uganda, with a total of ~41 million cases a stark difference by approximately 33 million. The reasons could be due to population density or poor access to healthcare. Uncoincidently, Congo also has the highest mortality rate at ~330k, almost double the mortality rate of United Republic of Tanzania who had the second highest death count (Figure 2). Though the data sets only cover until 2017, we cannot correctly assume whether the incidence and death count would have decreased by now from technological advances.

Figure 3 demonstrates a significant surge in Malaria cases globally between the years 2013-2017. In 2013, there were around 49 million reported cases of Malaria, which increased to approximately 105 million cases in 2017. This clearly indicates that the total number of cases more than doubled in just five years. The analysis also revealed that this surge was not limited to any particular country or region, as the increase was observed worldwide. This suggests that there were underlying factors that contributed to the increase in Malaria cases globally during this time period. There are some possible reasons for the surge, which include a lack of effective prevention and control strategies, increase global travel and migration and the emergence of drug resistant strains of Malaria parasite.

Furthermore, it can be observed that the global malaria deaths chart shows a fluctuating trend between 2002-2017, with the lowest number of deaths recorded in 2000 and the highest number in 2010. This clearly indicates that despite efforts being made to control and eradicate Malaria, there are still significant challenges to be faced. As previously mentioned, there could be many underlying reasons for the mortality rate to fluctuate, one of themost significant factors would be the availability and effectiveness of Malaria preventionand treatment interventions such as bed nets treated by insectides and antimalarial drugs. The global scale-up of these interventions over the past two decades has undoubtedly played a role in reducing malaria deaths, particularly in Africa. However, there have been several setbacks, such as the previously mentioned emergence of drug-resistant strains of the malaria parasite, which have made it more challenging to control the disease.

A global map (Figure 5) displaying the number of Malaria cases and deaths for each country signifies the geographic distribution of the disease and its impact on various regions around thr world. It helps in identifying the areas most affected by Malaria and highlights the need for targeted interventions and resources to control the spread of the disease.

Due to the Republic of Congo having the highest mortality rate and number of cases, I decided to analyse the country further and observe whether the number of cases per 1000 people would have increased between 2000-2017. From Figure 6, we can gather that despite having a roughly constant number of cases every year between 2000 to 2007, it surprisingly started to steadily decrease until 2015 where it started to fluctuate. The decline in number of cases per 1000 population, suggests that Malaria control efforts may have been effective during that time period. However, the recent increase in the number of cases per 1000 population in Congo suggests that malaria control efforts may need to be strengthened in order to maintain the progress that was made. Though the decrease in cases might have been significant, it could stil have left Congo with a higher total number of cases than other countries that did not experience a decrease in cases. 

### How the findings answer the questions posed in the project.
The findings of the Malaria Project reveal important insights into the trends and patterns of Malaria cases and mortality rate across different countries and regions. Despite medical advances, the number of cases worldwide keeps increasing due to various factors, including insufficient funding for prevention and control efforts. The project aimed to explore the patterns and trends in Malaria cases, deaths, and other relevant factors to gain insights into the global impact of the disease and inform future prevention and control efforts.

The project successfully answered the questions posed at the start of the project:

#### What are the global trends in Malaria cases and mortality?
The project identified an increase in both Malaria cases and mortality, despite the chart showing fluctuations, between 2000 and 2017, with the highest number of cases and deaths reported in sub-Saharan Africa.

#### Which countries or WHO regions have the highest burden of Malaria?
The project observed the top ten countries with the highest number of cases and deaths between 2000-2017. The majority of these countries were located in the sub-Saharan African region. Addionationally, the WHO African region had the most number of cases and deaths among other WHO regions.

#### How has Malaria cases and mortality changed over time?
An increasing trend in Malaria cases and deaths between 2000 and 2017 was reported, with the highest number of cases and deaths reported in 2016 and 2010, respectively. However the number of deaths as mentioned previously, fluctuates in terms of number of deaths with 2017 having a lower count of deaths when compared to 2016.

Overall, the project's findings highlight the importance of continued efforts to prevent and control Malaria, particularly in sub-Saharan Africa, where the disease burden is highest. The findings may inform future public health policies and interventions aimed at reducing the global impact of Malaria.

## Conclusion
In conclusion, this project analysed Malaria datasets to gain insights into trends and patterns of the disease across different countries and regions. Despite medical advances during that time, the analysis revealed that the number of cases keeps increasing globally due to various factors, including insufficient funding for prevention and control efforts. Climate change could also be a huge factor to contribute to the spread of Malaria as higher temperatures are more favourable for mosquitoes.

The aim of the project was to explore the patterns and trends in Malaria cases, deaths, and other relevant factors to gain insights into the global impact of the disease and inform future prevention and control efforts. By analysing the number of cases and deaths by region, the project aimed to identify regions with the highest cases of Malaria and inform targeted interventions to reduce the burden of the disease in those specific areas. The examination of the correlation between Malaria cases and deaths helped identify factors that contribute to the severity of the disease.

Overall, this project demonstrates the importance of data analysis in understanding complex factors that contribute to the spread of Malaria and developing effective strategies for prevention and treatment.
