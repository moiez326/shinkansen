# Shinkansen Passenger Satisfaction Analysis

## Introduction
The Shinkansen, also known as the bullet train, plays a pivotal role in Japan's transportation system, famed for its punctuality and speed. Despite this, passenger satisfaction reports show only a 56% satisfaction rate. This project delves into various factors affecting passenger satisfaction with the goal of providing actionable insights to improve the overall travel experience.

### Objective
The main objective is to analyze factors such as travel distance, delays, and demographic variables to uncover their impact on passenger satisfaction. The insights from this analysis aim to assist the travel industry in enhancing service quality and the passenger experience.

### Key Questions
- What factors most influence passenger satisfaction on the Shinkansen?
- Is there a noticeable difference in satisfaction levels across different demographic groups?
- How do travel distance and delay times correlate with passenger satisfaction?

## Repository Structure
- `shinki_EDA.ipynb`: The Jupyter notebook containing the exploratory data analysis and visualizations.
- `Shinkansen.csv`: The cleaned and processed dataset resulting from the analysis.
- `README.md`: An overview of the analysis and findings.

## Data Dictionary
| Variable                  | Description                                      | Type      |
|---------------------------|--------------------------------------------------|-----------|
| ID                        | Unique identifier for each survey response       | int64     |
| Overall_Experience        | Satisfaction level (1: Satisfied, 0: Not)        | int64     |
| Seat_Comfort              | Comfort of the seat                              | object    |
| ...                       | ...                                              | ...       |

## Insights and Recommendations
- **Service Quality Over Distance and Delays**: Travel distance and delays had a negligible correlation with passenger satisfaction, suggesting that service quality and onboard amenities might play a more crucial role.
- **Demographic Impact**: Gender and age significantly impact satisfaction levels. Elderly and younger demographics show differing levels of satisfaction, highlighting a potential need for targeted service improvements.
- **Focus Areas for Enhancement**: With service quality identified as a key driver of satisfaction, focusing on aspects such as onboard comfort, catering, and entertainment could yield positive results in passenger satisfaction scores.

## Conclusion
The analysis underscores the complexity of passenger satisfaction, which is influenced by various factors, often qualitative in nature. For Shinkansen, the path to enhancing satisfaction may lie in elevating service quality and tailoring the travel experience to meet the unique needs of different passenger groups.

## Future Directions
- **Deep Dive into Qualitative Aspects**: Further investigation into qualitative feedback from passengers could offer more detailed insights into specific areas for improvement.
- **Customized Passenger Services**: Developing services catered to the preferences of different age and gender groups could enhance satisfaction levels, especially among those currently less satisfied.
