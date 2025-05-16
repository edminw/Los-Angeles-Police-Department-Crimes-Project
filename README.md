


# Project Background

The Los Angeles Police Department holds a task force of more than 8,500 sworn officers covering a jurisdiction of over 4 million residents. This dataset published by the LAPD department and used in this project includes a comprehensive summary on incident-level crime in all Los Angeles police districts from the years 2021 to 2023. The purpose of this project was to provide useful insights with an easy-to-use dashboard for anyone interested in understanding more about the ins and outs of crime activity in Los Angeles. This could include residents currently living in the city or even inidividuals who are planning to move to LA and want to know more about each district area and other useful statistics. 

Some key objective questions I would like to address are listed below:
- What are the neighborhoods in LA with the highest crime rate?
- Which year, month, or time of day show the highest level of crime activity?
- How long does it take for a crime that was committed to be reported to the police department?
- What is the most targeted age group? Is there a correlation between victim sex and age?
- Which ethnicity was targeted the most? Do the victim's age and ethnicity have a correlation?
- What are the most common types of crime committed? Theft? Battery? Verbal threats? Assult?
- Where do most crimes occur? In a household? At a business? Or in the public?

# Data Structure / Methods Used

The original dataset was loaded onto a Jupyter Notebook for data cleaning and exploration. The file can be found here [link].

Using the 


# Executive Summary / Overview

<div align="center">
  <img width="600" alt="LACrimesOverviewPage" src="https://github.com/user-attachments/assets/025caaf7-9700-4b23-a952-78cc708939b4" />\
</div>

- 2022 and 2023 had increased crime rates of 71K total crimes compared to 2021 with 64K.
- Crimes are committed most frequently at night from 9PM-4AM compared to any other time of day. In terms of season, the later summer months to early fall (July-October) show the most activity. 
- 58.8% of crimes reported for this dataset at the time have been ongoing investigation. This number may have changed from when this dataset was released compared to today. However, having over half of investigations ongoing shows the sheer number of cases that do not get resolved in Los Angeles.
- When observing Los Angeles's police districts, the highest number of crimes are reported in a centralized section of neighboring districts consisting of 77th Street, Central, Southwest, Newton, and Southeast. These districts show roughly a 2x increase in number of crimes compared to other parts of LA.  

<div align="center">
  <img width="600" alt="LACrimesTrends" src="https://github.com/user-attachments/assets/3e671958-cfe0-4cef-b66b-e05e9e654576" />\
</div>

- When comparing the victim's age group with gender, female young adults (18-40 years) are targeted the most. This overall age group (18-40 years) have predominantly the most number of crimes compared to any other age group, with the Adults (40-65 years) group coming in second.
- Approximately half of the crimes committed (103K) involve victims of Hispanic/Latin/Mexican ethnicity, with victims of Black ethnicity coming in second (47K), and victim of White ethnicity coming in 3rd (36K).
- There is a negative correlation between the average victim age and total number of crimes based on ethnicity. As the ethnicity group has a higher rate of crime, the average age of the victim goes down.  


# Recommendations

Based on the insights and findings above, below are some general recommendations and guidelines I would suggest to the LAPD community based on their dataset: 
- Focus on allocating funds and efforts on preventing crimes during peak months of July to October. Instead of having the same number of officers on duty all-year round, recruit more officers during these months and patrol more areas for early prevention.
- Ethnic groups experiencing higher crime rates generally have younger victims. Certain early prevention programs or mentorships should be created in schools and youth programs to protect at-risk youth.
- Central LA districts (77th, Central, Newton) report approximately twice the number of crimes. Prioritize funding and strategic policing in these districts combined with community organizations.
- 58.8% of crimes remain under investigation. A more streamlined investigative process needs to be implemented in order to bring this dangerously high number down. Different solutions can be tested including more accurate closing resolution records, increased staffing on crime documentation, etc.

# Future work

Although this dataset provides a general view on what kind of crimes are committed, when these crimes are committed, who these crimes are targeting, and where these crimes are primarily located, it fails to provide more information on more specific insights that can be found. One major shortcoming is that there is a lot of information on what kind of victims fall prey to these crimes, but there is little to no description on the assailants. For instance, although we know the Hispanic/Latin/Mexican community accounts for half of LA's crimes, are these crimes committed within the same Hispanic community? Or do these communities just live in areas where higher crime exists regardless of ethnicity? The highest crime rate is recorded on victims falling in the young adult female group, but which group commits the most crime? Furthermore, over half of the incidents are marked as "under investigation", which signifies that most likely a considerable portion of these records are missing final updates. Finally, there is an apparent lack of socioeconomic data to go along with the demographic data this dataset has provided. Variables including income levels, education, employment rates, and housing stability are often key contributors to crime, and combining such factors with demographics can paint a much clearer picture.
