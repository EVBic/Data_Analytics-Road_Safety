
## <h4 align=center> **PROJECT Nº2**</h4>
### <h2 align=center> Data Analytics Project: Road Accidents in CABA <h2>

<h2 align=center>🚨🚵🚧🚗🛵🛣️🚙🚌🚓🚑🚒🚚🚦🚜🚲🚕🛴🚛🏍️🛤️🚸🚳🚴🚎🛑🚥<h2>

<h2 align=center>📊 ** Data Analysis - ETL-EDA-KPI-Dashboard ** 📊</h2>
<h3 align=center> Henry's Labs</h3>
<h2 align=center> By Maria Eva Bichi</h2>

## Approach:  :white_circle:
Cleaned and prepared the data.

## Key Insights: :white_circle:

Understanding accident patterns and high-risk areas.
Identifying factors contributing to accidents.

## Data Preprocessing: :white_circle:

The project employs a meticulous data cleaning process.

Extract
The first step in the ETL process is data extraction. This involves obtaining raw data from various sources. 
For a project on road accidents in CABA, these sources could include:

Public databases provided by the government.

Transform
Once the data is extracted, we transformed into a format that can be easily analyzed. This involved several sub-steps:

Cleaning: Removing duplicates, filling missing values, correcting errors.
Formatting: Converting data types, standardizing date and time formats.
Aggregating: Summarizing data, creating new calculated fields.
Normalizing: Adjusting values measured on different scales to a common scale.

Throughout this ETL process, we have conducted a comprehensive analysis of the data pertaining to road accidents in Buenos Aires. Through data extraction, transformation, and loading, we have not only identified trends and patterns related to road safety but also significant instances of missing data in key columns of our dataset.

The metric of missing data has emerged as a critical indicator signifying a statistical and sampling issue that demands immediate attention. Specifically, the lack of information in the age and death date columns for road accident victims has drawn our focus. These missing data points not only hinder our analysis but also raise crucial questions about the coordination and tracking of victims within the healthcare system.

The absence of complete data in these areas indicates a need for improved communication and coordination between traffic authorities and healthcare centers. The ability to identify and track road accident victims is vital not only for understanding the severity of the situation but also for providing necessary support and assessing the effectiveness of road safety policies.

In this context, this analysis not only highlights the statistical challenges we face in evaluating road safety but also underscores the importance of closer collaboration between different government entities and healthcare systems. Addressing the missing data in the victims’ ages and death dates should be a priority to enhance the quality of available information and ultimately make more informed and effective decisions in reducing road accidents and protecting the lives of our citizens.

This ETL process has served as a starting point to understand the significance of data and the need to tackle the challenges they present while emphasizing the relevance of inter-institutional coordination for improving road safety in Buenos Aires."

## EDA: :white_circle:

Histograms: Effectively depict the distribution of numerical data (e.g., number of injuries) to identify potential skewness or outliers.

Scatter Plots: Reveal relationships between two numerical features (e.g., time of day vs. accident count).

Boxplots: Compare distributions of numerical data across different categories (e.g., accident severity based on road type).


## KPI1: Traffic Homicide Rate :white_circle:

<img src="https://github.com/EVBic/Data_Analytics-Road_Safety/blob/main/PI02-DataAnalysis/Images/KP%C3%8F1-10output.png" alt="DAkpi1" width="500" height="300">

Objective: Reduce the traffic homicide rate in CABA by 10% in the last six months, compared to the rate of the previous semester.

Definition: The number of fatal victims in traffic accidents per 100,000 inhabitants in a geographical area during a specific period.

Formula: Homicide rate = (Number of homicides in traffic accidents / Total population) * 100,000

Identify geographical areas with higher rates and focus preventive measures in those areas.
Evaluate the effectiveness of road safety campaigns.

Results
Year: 2021, Semester: 1, Accidents: 54, Increase: 10.204082%
Year: 2021, Semester: 2, Accidents: 42, Decrease: 22.222222%

Conclusion:
The traffic homicide rate in CABA has decreased by 10.204082% in the last six months, compared to the rate of the previous semester. This is a positive result, but there is still room for improvement. It is important to continue to identify geographical areas with higher rates and focus preventive measures in those areas. It is also important to evaluate the effectiveness of road safety campaigns and make necessary adjustments.

Recommendations:
Continue to identify geographical areas with higher rates and focus preventive measures in those areas.
Evaluate the effectiveness of road safety campaigns and make necessary adjustments.
Implement new measures to reduce the number of fatal accidents.
Invest in road infrastructure to improve road safety.

## KPI2: Motorcycle Fatal Accidents :white_circle:
<img src="https://github.com/EVBic/Data_Analytics-Road_Safety/blob/main/PI02-DataAnalysis/Images/kpi2output.png" alt="DAkpi2" width="500" height="300">

Objective: Reduce the number of motorcycle fatal accidents in CABA by 7% in the last year(2021), compared to the previous year.

Definition: The absolute number of fatal accidents involving victims riding motorcycles in a time period.

Formula: Reduction (%) = [(Motorcycle fatal accidents previous year - Motorcycle fatal accidents current year) / Motorcycle fatal accidents previous year] * 100

Result
2020: 27 fatal accidents
2021: 45 fatal accidents
Increase: 66.67%

Conclusions
There has been a significant increase in the number of motorcycle fatal accidents in CABA. The measures implemented have not been effective in improving road safety. It is important to review and improve the prevention and control measures to reverse this trend.

Recommendations
Review and improve the current prevention and control measures.
Implement new measures to reduce the number of fatal accidents.
Conduct studies to identify new risk factors.
Invest in road infrastructure to improve motorcycle safety.

## Power BI: :white_circle:
<img src="https://github.com/EVBic/Data_Analytics-Road_Safety/blob/main/PI02-DataAnalysis/Images/dbPBI1.png" alt="DSB1" width="500" height="300">
<img src="https://github.com/EVBic/Data_Analytics-Road_Safety/blob/main/PI02-DataAnalysis/Images/tempv2.png" alt="DSB2" width="500" height="300">
## Conclusion: :white_circle:
    
   IMPROVEMENT:

    Particular area, urban areas: The maximum speed limit on the avenues of the Autonomous City of Buenos Aires (CABA) is generally 60 km/h. However, there are exceptions for some avenues such       as Figueroa Alcorta, del Libertador, 27 de Febrero, Brigadier General Juan Facundo Quiroga, and Costanera Rafael Obligado, where the maximum limit is 70 km/h. How:
    It is proposed that the speed limit on avenues in CABA be reduced to 50 km/h. This proposal is based on research indicating that lower speed limits can significantly reduce the risk and          severity of accidents.
    Implementing this change would involve a comprehensive approach, including updating road signage to reflect the new speed limits, conducting public awareness campaigns to inform road users       about the change, and enforcing the new limits through traffic policing and speed cameras.

    Particular demographic group: It is beneficial to launch awareness and information campaigns to ensure that all stakeholders are well informed about the conditions and take them into             consideration. It’s important to note that almost 60% of victims are 40 years old or younger, and 81% are male. How:
    Therefore, these campaigns should be specifically targeted towards this demographic to maximize their effectiveness. Control speeding. Raise awareness about the importance of helmet use.         Conduct alcohol and drug tests. Provide road safety courses for motorcyclists. Improve road conditions.

    Sustainable public transport: Can significantly improve weekend traffic by providing an efficient and convenient alternative to driving. How:
    Reduced Traffic Congestion: When more people opt for public transport, fewer cars are on the road. This can significantly reduce traffic congestion, especially during peak travel times like      weekends when people are more likely to go out.
    Environmentally Friendly: Public transport is generally more fuel-efficient per passenger than private vehicles. This means less pollution and a smaller carbon footprint.
    Cost-Effective: Using public transport can be more cost-effective than owning and maintaining a car, considering fuel, parking, insurance, and maintenance costs. This can be a significant        incentive for people to choose public transport.
    Increased Accessibility: Good public transport systems can make the city more accessible. People can travel to different parts of the city without the need for a car, which can be                particularly beneficial for those who do not own a car.
    Safety: Traveling by public transport is statistically safer than traveling by car. Reduced traffic can also potentially lead to fewer accidents.   

Another possible actions:

Speeding: Speeding is a key factor in approximately 30% of fatal traffic accidents and exacerbates most accidents. It is recommended to apply safe speed limits, consistent with the “Safe System” approach for all types of roads.

On-board Technologies: There is a promotion of on-board technologies to aid in choosing safe speeds (Intelligent Speed Adaptation systems).

Infrastructure for Pedestrians and Cyclists: It is crucial to develop quality requirements for infrastructure for pedestrians and cyclists, in order to address the insufficient level of safety for active road users.

Modal Shift: It is important to recognize the importance of a modal shift towards active modes, such as walking and cycling, and sustainable public transport modes as important instruments to reduce the level of danger on the roads.

Furthermore, it would be beneficial to compare these results with other similar metrics or KPIs. Understanding these details can help pinpoint specific areas for improvement and tailor interventions more effectively.

Lastly, it’s important to remember that while numbers and percentages are useful for tracking progress and making comparisons, each victim represents a human life. The ultimate goal should always be to reduce these numbers to zero, ensuring the safety of all road users.





Tools and Libraries:

Python libraries like Pandas, NumPy, Matplotlib, and Seaborn

Info from : 
[LINK ARG GOB](https://www.argentina.gob.ar/)
