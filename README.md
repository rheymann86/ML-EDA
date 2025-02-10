Dataset Overview
This dataset provides insights into users' app usage, demographics, preferences, and challenges related to dating applications. It includes information on primary and secondary app choices, usage frequency, satisfaction levels, and desired features.

| Column Name                   | Data Type | Description |
|--------------------------------|----------|-------------|
| User_ID                        | int      | Unique identifier for each user |
| Age                            | int      | Age of the user |
| Gender                         | category   | Gender identity of the user |
| Location                       | category   | City where the user is based |
| Education                      | category   | Highest level of education completed |
| Occupation                     | category   | Employment status or job role of the user |
| Primary_App                    | category   | The main dating app the user prefers |
| Secondary_Apps                 | category   | Other dating apps the user uses |
| Usage_Frequency                | category   | How often the user engages with dating apps (e.g., daily, weekly, monthly) |
| Daily_Usage_Time               | category   | Time spent on the apps in hours/minutes format |
| Reason_for_Using               | category   | The user's motivation for using dating apps (e.g., finding a partner, casual dating) |
| Satisfaction                   | category      | Satisfaction rating on a scale (e.g., 1-5) |
| Challenges                     | category   | Issues faced while using dating apps (e.g., safety concerns, time-wasting) |
| Desired_Features               | category   | Features users wish to have in dating apps |
| Preferred_Communication        | category   | The most preferred mode of communication (e.g., text, voice notes, video calls) |
| Partner_Priorities             | category   | The order of priority for selecting a partner (e.g., values > personality > appearance) |
| Daily_Usage_Time_in_Minutes    | category    | Numeric representation of daily usage time in minutes |

Data Cleaning Steps
-Handled Missing Values: Used the mode to fill missing values, as the value distribution across columns was balanced. This prevents over-representation of rare values.
  Ensured Data Type Consistency: Converted object columns to categorical data types, including the "Satisfaction" column.
-Checked for Duplicates: Verified the dataset for duplicates but found none.
-Standardized Gender Categorization: Ensured consistency in categorical labels to avoid discrepancies.
