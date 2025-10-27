# Restaurant Tips Analysis
## 1. Project Summary
This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. We will examine the relationship between different variables and the tips given.

The dataset consists of information from 244 restaurant bills, collected in the US in 1987.

It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.
## 2. Data Description
### Data Source
https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv
### Data Details
As you can see each observation represents a customer who left a tip at a restaurant.
We can see information about:

`id` : Unique identifier for each bill

`total_bill`: The total bill

`tip`: Tip amount

`sex`: The gender of the person

`smoker`: If they were a smoker or not

`day`: Day of the week it occurred

`time`: Time of day (Lunch or Dinner)

`size`: The size of the party

### How to access
You can access the data using:

```python
df = pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
```
## 3. Main goals
**Examine the distribution of tips and its relationships with other factors.**

**Compare tipping behavior between smokers and non-smokers, males and females, weekend and weekday, Lunch and Dinner.**

**Visualize the data using statistics and histogram charts**

**Gain insights about what factors have strong impacts on tip behavior**

## 4. Results
### Central tendency
The tip values range from $1.00 to $10.00, with a mean of approximately $3.00.

The distribution of tip values exhibits a right-skewed pattern, indicating that most observations fall on the lower end with a few high-value outliers.
### Smokers vs. Non-Smokers
The tip distributions across the two charts are similar and exhibit right-skewness, indicating that most tips are small while a few are considerably higher.

Non-smokers tend to leave tips more frequently than smokers.

### Males vs. Females
Male customers tend to leave tips more frequently and of higher value than female customers. 

### Day and Time
Tip amounts are generally higher on weekends and during dinner service.



For detailed analysis and all visualizations see the 









