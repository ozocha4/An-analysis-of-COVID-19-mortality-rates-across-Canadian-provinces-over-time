# An-analysis-of-COVID-19-mortality-rates-across-Canadian-provinces-over-time

Project:An analysis of COVID-19 mortality rates across Canadian provinces over time

Purpose:
The purpose of this study is to examine and compare COVID-19 mortality rates across Canadian provinces to understand how the impact of the pandemic varied by region and over time.

Introduction:

COVID-19 is an infectious disease caused by the SARS-CoV-2 virus, first identified in late 2019, which rapidly spread across the world, including Canada. The pandemic affected all Canadian provinces and territories, although the levels of infection, mortality, and fatality varied across regions and over time. To monitor its progression and support public health decision-making, data on confirmed cases, deaths, and population were collected and analyzed. In this study, mortality refers to the number of deaths caused by COVID-19 within the population, often expressed as a death rate per 100,000 people, while fatality refers to the proportion of confirmed cases that resulted in death, commonly measured using the case fatality rate. Examining both mortality and fatality provides a more complete understanding of the impact of COVID-19, as these measures allow for meaningful comparisons between provinces despite differences in population size and number of confirmed cases.

Method:

1) Data source: 

The data used in this analysis was obtained from Statistics Canada (https://www.statcan.gc.ca/en/start).

2) Data cleaning & tools:

RStudio was used to extract data from the webpage, Tableau Prep Builder was used for data cleaning, and Tableau Desktop was used for data visualization.

3) Research questions / analysis approach:
   
I.	How did COVID-19 mortality rates vary across Canadian provinces over time?

II.	How did COVID-19 death rates per 1million population differ between Canadian provinces over time?

III.	What relationship exists between confirmed COVID-19 cases and deaths across Canadian provinces over time?

4) Results / Findings:
 <img width="975" height="500" alt="image" src="https://github.com/user-attachments/assets/8ce8d428-0f9a-4150-8e61-7be6b4ad6877" />


The chart compares COVID-19 fatality rates across Canadian provinces from 2020 to 2023 and shows a clear overall decline over time. The most striking pattern is that 2020 recorded the highest fatality rates and the greatest variation among provinces. In that year, Nova Scotia and Quebec had the most prominent peaks, both exceeding 4%, while Manitoba and Ontario also showed relatively elevated rates. This suggests that the earliest phase of the pandemic was the most severe and unevenly distributed across provinces.
From 2021 onward, fatality rates generally decreased and became more stable. In 2021 and 2022, most provinces recorded rates below 1.5%, with only moderate increases in a few regions such as British Columbia, Quebec, and Saskatchewan. This indicates that, although fatalities continued, the situation became less severe and less volatile compared with 2020.
The 2023 data appear to show the lowest fatality rates overall, with most values close to zero. However, the chart displays fewer data points for 2023, so conclusions for that year should be made cautiously. Overall, the chart suggests a steady reduction in COVID-19 fatality rates across Canada, alongside a narrowing gap between provinces over the course of the pandemic.

 
<img width="911" height="638" alt="image" src="https://github.com/user-attachments/assets/32664e91-e7db-41a8-b2d5-bf8d86c644ab" />


The chart shows that COVID-19 mortality rates varied notably across Canadian provinces, with a few provinces carrying the highest burden. Quebec recorded the highest cumulative mortality rate at approximately 6.1 per 1 million, followed by Manitoba at about 4.7 and Saskatchewan at around 3.8. Alberta and Ontario also showed relatively elevated totals, at roughly 3.4 and 3.0 respectively. In contrast, Nunavut had the lowest mortality level, close to 0.5, while Prince Edward Island and Newfoundland and Labrador remained comparatively low.
By year, the largest visible contributions came from 2020 and 2022, especially in Quebec and Manitoba, indicating that those years were more severe in several provinces. The 2021 values were moderate across most regions, while 2023 contributed very little overall, suggesting a clear decline in mortality by the final year. Overall, the data indicates that COVID-19 mortality was uneven across Canada but generally decreased over time across most provinces.


<img width="908" height="638" alt="image" src="https://github.com/user-attachments/assets/d3f53dd7-09ec-4c58-99ed-2513b108bb10" />

 

The chart shows a positive relationship between confirmed COVID-19 cases and deaths in Canada, but the increase in deaths was not proportional to the rise in confirmed cases. Confirmed cases rose sharply from 590,235 in 2020 to 1,633,593 in 2021 and peaked at 2,304,898 in 2022, while deaths were 15,743 in 2020, 14,611 in 2021, and 19,366 in 2022. This means that although infections increased significantly, deaths did not rise at the same rate. The case fatality rate declined from about 2.67% in 2020 to 0.89% in 2021 and 0.84% in 2022, showing that a smaller proportion of confirmed cases resulted in death over time. By 2023, both confirmed cases and deaths dropped sharply to 3,791 and 10 respectively. Overall, the data suggests that while higher confirmed cases were associated with deaths, the risk of death per confirmed case decreased over time.

Dashboard:

<img width="975" height="636" alt="image" src="https://github.com/user-attachments/assets/bd6996e3-1a0f-4684-a23c-21577fc55151" />











Conclusion:

Overall, the charts show that COVID-19 had its greatest impact in the early years, with provincial variation in mortality and fatality rates. Quebec, Manitoba, and Saskatchewan were among the most affected. Although confirmed cases rose sharply through 2022, deaths increased less proportionally, indicating declining severity and outcomes over time.

