# Part I-Dataset Exploration Homicide Reports Dataset
### by Layla Alsaabna


## Introduction

The dataset is from kaggle, [Homicide Reports, 1980-2014](https://www.kaggle.com/datasets/murderaccountability/homicide-reports)

This dataset includes murders from the FBI's Supplementary Homicide Report from 1976 to the present and Freedom of Information Act data on more than 22,000 homicides that were
not reported to the Justice Department. This dataset includes the age, race, sex, ethnicity of victims and perpetrators, in addition to the relationship between the victim and perpetrator and weapon used.


This dataset contains detailed information on homicide reports. Each row represents a single incident. Below is a description of each variable in the dataset:

| Variable              | Description                                                                  |
|-----------------------|------------------------------------------------------------------------------|
| **Record ID**         | A unique identifier for each record in the dataset.                          |
| **Agency Code**       | The code assigned to the law enforcement agency that reported the homicide.  |
| **Agency Name**       | The name of the law enforcement agency that reported the homicide.           |
| **Agency Type**       | The type of the law enforcement agency (e.g., Municipal Police, Sheriff's Office). |
| **City**              | The city where the homicide occurred.                                        |
| **State**             | The state where the homicide occurred.                                       |
| **Year**              | The year when the homicide occurred.                                         |
| **Month**             | The month when the homicide occurred.                                        |
| **Incident**          | A 3-digits unique identifier for the incident.                                        |
| **Crime Type**        | The type of crime committed (e.g., Murder or Manslaughter).                  |
| **Crime Solved**      | Indicates whether the crime was solved (`Yes` or `No`).                      |
| **Victim Sex**        | The sex of the victim (`Male` or `Female`).                                  |
| **Victim Age**        | The age of the victim.                                                       |
| **Victim Race**       | The race of the victim (e.g., White, Black, Asian, Native American).         |
| **Victim Ethnicity**  | The ethnicity of the victim (e.g., Hispanic, Non-Hispanic).                  |
| **Perpetrator Sex**   | The sex of the perpetrator (`Male`, `Female`, `Unknown`).                    |
| **Perpetrator Age**   | The age of the perpetrator.                                                  |
| **Perpetrator Race**  | The race of the perpetrator (e.g., White, Black, Asian, Native American).    |
| **Perpetrator Ethnicity** | The ethnicity of the perpetrator (e.g., Hispanic, Non-Hispanic).         |
| **Relationship**      | The relationship between the victim and the perpetrator (e.g., Acquaintance, Stranger, Family). |
| **Weapon**            | The type of weapon used in the homicide (e.g., Firearm, Knife, Blunt Object).|
| **Victim Count**      | The number of additional victims (not counting the victim included in the currentrecord) |
| **Perpetrator Count** | The number of additional offenders (not counting the offender included in thecurrent record)    |
| **Record Source**     | The source of the record (e.g., FBI).                                        |


### How does the distribution of ages differ between victim and perpetrator?
![1output](https://github.com/user-attachments/assets/13dce111-54e0-4d4d-b32d-c6f431d90610)



### Which city has the highest number of homicides?
### And
### Which state has the highest total number of homicides?
![output2](https://github.com/user-attachments/assets/6c510c81-efcd-4702-99bf-cf4b3889eed6)



### Are there any particular years with a higher concentration of victims within specific age ranges?
![output3](https://github.com/user-attachments/assets/37927f29-2934-4da1-b2eb-0fb16b3862e8)



### Are there any particular years with a higher concentration of perpetrators within specific age ranges?
![output4](https://github.com/user-attachments/assets/66e6ec71-620a-48bb-b038-3af97e35d009)



### How does the relationship between victim age and perpetrator age vary across different weapon types?
![output55](https://github.com/user-attachments/assets/f701e1df-5fca-4526-b32f-d817310bfa09)


## **Conclusion**


Through a detailed analysis of the homicide data, several critical insights have emerged, highlighting patterns in victim and perpetrator demographics, weapon usage, and geographic distribution. These findings provide a deeper understanding of the dynamics surrounding homicides, particularly in relation to age, gender, and location.

**Key Findings**:


1- Temporal Patterns:

* *Peak Homicide Records*: The period from 1992 to 1993 witnessed the highest number of homicide records, indicating a significant spike in violent crimes during these years.
Geographic Distribution:

2- High Homicide Cities: Los Angeles and New York stand out as the cities with the highest number of homicides, likely due to their large populations and urban density.

3- State-Level Insights:
  * California: This state recorded the highest number of homicides, reflecting its large population and numerous major cities.
  * Texas and New York: Both states closely follow California, also reflecting significant urban populations and associated crime rates.
  * Low Homicide States: States like North Dakota and Vermont show significantly lower homicide counts, indicative of their smaller populations and more rural settings.

4- Victim and Perpetrator Age Dynamics:

  * Victim Age Distribution: The highest frequency of victims falls between the early 20s and early 30s, with notable peaks at ages 32, 22, 20, 25, and 21. This suggests that individuals in this age group are particularly vulnerable to homicide.
  * A decline in victim numbers is observed beyond the early 30s, which is expected as population size decreases in older age groups.
  * Elderly victims (ages 88-90) are rare, reflecting their smaller population size and lower involvement in violent crime.
* Perpetrator Age Distribution: The most frequent ages for perpetrators are between 20 and 30, with age 21 being the most common. The frequency drops sharply after age 30, with very few perpetrators above age 50.


5- Weapon Usage:

  * Handguns are the most commonly used weapon in homicides.
  * Rifles, Firearms, and Shotguns: These weapons show a pattern where male victims are more widely distributed across ages, while female victims show a more specific age-related pattern.
  * Explosives: There is a distinct concentration of female victims in their late 20s, suggesting a demographic concentration.
  * Drowning & Suffocation: These methods exhibit unique age-related patterns, particularly for female victims, with specific vulnerabilities observed in infants and adults aged 34-36.
6- Victim-Perpetrator Relationships: The most common relationships between victims and perpetrators are "Acquaintance" and "Stranger," indicating that investigators often start with people who know the victim.

7- Gender-Specific Patterns:

  * Male Victims: Perpetrators of male victims tend to be younger adults, predominantly aged 18-32 years.
  * Female Victims: Female victims show a broader distribution in the ages of perpetrators, extending into the late 30s and beyond, indicating that females may be more at risk from a wider age range of perpetrators.


**Limitations and Further Investigation**:
* Data Coverage: The analysis is limited by the time period and geographic scope of the dataset. Expanding the dataset to include more recent years and additional regions could provide more comprehensive insights.
* Gender Analysis: The dataset shows that male perpetrators are predominant, which might obscure patterns among female perpetrators. Further investigation is needed to explore gender-specific trends in greater detail.
  
* Victim-Perpetrator Relationships: While "Acquaintance" and "Stranger" relationships dominate, a deeper dive into less common relationships (e.g., family or intimate partner) could uncover important nuances.
Age Dynamics in Homicides:

The study reveals specific age ranges where both victims and perpetrators are more common. However, further research is needed to understand the underlying causes, such as social, economic, or psychological factors, driving these patterns.
