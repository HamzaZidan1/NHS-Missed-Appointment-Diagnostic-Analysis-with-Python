# Zidan_Hamza_DA201_Assignment

## Findings from Activity 2

Based on the data analysis, we can see that the dataset contains a total of 106 locations. NHS North West London ICB - W2U3Z, NHS Kent and Medway ICB - 91Q, NHS Devon ICB - 15N, NHS Hampshire and Isle Of Wight ICB - D9Y0V, and NHS North East London ICB - A3A8R have the most records. It's worth noting that these locations are spread out across the United Kingdom.

There are a total of five service settings that could be indicative of different types of medical services provided by the NHS. Likewise, there are three types of contexts, national categories, and appointment statuses. These findings imply that the appointments in the dataset have a limited range of these parameters.

Overall, these findings provide us with an initial understanding of the data and the various parameters used to categorise appointments in the NHS. Further research could be conducted to look into correlations between these parameters and other factors like appointment duration or waiting times.

## Findings from Activity 3

To find the first and last appointment dates in the Actual Duration DataFrame, I used the min() and max() functions on the appointment_date column of the DataFrame. The first appointment date was 2021-12-01 and the last appointment date was 2022-06-30.

Similarly, I used the min() and max() functions on the appointment_date column of the National Categories DataFrame to find the first and last appointment dates. The first appointment date was 2021-01-08 and the last appointment date was 2022-12-06.

To determine the service setting with the highest number of appointments, I used the value_counts() function on the service_setting column of the National Categories DataFrame. The service setting "General Practice" had the highest number of appointments with 1644.

To find the month with the highest number of appointments, I grouped the appointment_date column of the National Categories DataFrame by month using the groupby() method and then used the count() method to count the number of appointments in each month. I then sorted the result in descending order using the sort_values() method. November 2021 had the highest number of appointments with 30,405,070.

To determine the total number of records per month, I grouped the appointment_date column of the AR DataFrame by month using the groupby() method and then used the count() method to count the number of records in each month.

Further questions that arose in the process include:

- Are there any missing values in the appointment_date column of the AR and National Categories DataFrames?
- What is the distribution of appointments across different service settings?
- Are there any trends or patterns in the number of appointments over time?

## Findings from Activity 4

From August 2021 to June 2022, the data provided shows the number of appointments by service setting and context type.

When looking at aggregated monthly appointment counts by service setting, the trend shows a steady increase from August 2021 to March 2022, followed by a decrease from April 2022 to June 2022. Across all months, the General Practice service setting had the most appointments.

There is also a steady increase in aggregated monthly appointment counts by context type from August 2021 to November 2021, followed by a decrease from December 2021 to June 2022. The Care Related Encounter context type had the most appointments across all months.

When it comes to seasonal trends, there is a consistent increase in appointment counts from August to November, followed by a decrease from December to March and an increase from April to June. Across all seasons, the General Practice service setting and Care Related Encounter context type had the highest number of appointments.

## Findings from Activity 5

The most popular hashtag, with a count of 716, appears to be #healthcare, according to the visuals made using the statistics. The hashtags #health, #medical, #ai, and #job are also widely used. The healthcare sector may find the conclusions drawn from this data beneficial since they may use it to track social media conversations and identify the most popular subjects.

By using Seaborn to create a bar plot, the visualisations were enhanced to maximise feedback to the team and the NHS. To show the most popular hashtags, hashtags with a count greater than 10 were included in the plot. This made it possible to portray the data more clearly and spot trends more quickly. Analyzing the correlation between the hashtag usage and the tweet retweet and favourite counts will allow for further investigation. This can offer more information about how hashtag usage affects tweet engagement. Also, analysing the mood of tweets containing particular hashtags might shed light on how social media users feel about healthcare-related subjects.
