# Market problem detection through smart visualizations in Power BI

# Overview 📖

This project aims to identify and understand the reasons behind Amazon's decline in bicycle sales. Using advanced exploratory data analysis (EDA) techniques and intelligent visualizations in Power BI, it seeks to uncover purchasing patterns, relationships between variables, and possible anomalies that may be negatively impacting the market.

With a strategic approach, the project aims to provide actionable insights that can guide the creation of more effective sales campaigns, targeting the audience with the most significant potential to purchase. Through the analysis of benchmarks, buying patterns, and hypothesis generation, the project provides a clear and detailed view of the dynamics of the bicycle market, allowing for a deep understanding of the factors that influence consumer decisions. In the end, the project presents suggestions for improvements that can be implemented to reverse the trend of declining sales and ensure that bicycles continue to be a popular and accessible choice for consumers.

# Table of Contents 📚

- Introduction
- Situation
- Strategy
- Business Questions
- Exploratory Data Analysis in Power BI:

      -Benchmarks
  
      -Purchasing Patterns
  
      -Generate Hypotheses
  
      -Examine Relationships

      -Check Anomalies
    
- Insights
- Recommendations

# Introduction 📝

In the past, bicycles symbolized freedom, adventure, and a closer bond with nature and community. However, bicycle sales on Amazon have seen a significant drop, leaving managers and analysts puzzled. In this project, we'll use Power BI to investigate the decline, study purchasing patterns, and provide insights to help reverse this trend. Just like a cyclist adjusts their route, we'll adapt our sales strategies to meet this new challenge.

# Situation 🔎

The volume of bicycle sales has dropped significantly on Amazon and the managers would like to understand why and how to fix it.

# Strategy 🎯

- Understand the reasons for the drop and identify insights to create a more efficient strategy to invest in sales campaigns for the audience with the greatest purchasing potential.
- Action plan: Perform Exploratory Data Analysis (EDA) to identify patterns, relationships, and anomalies in the data to define the target audience.

# Business Questions ⚖️

Understanding the characteristics of the data:
- Why is this drop occurring?
- Is it momentary or is it a trend?
- What are the factors that most impact the purchasing decision?
- What factors are influencing this drop. Are there outliers that may be significantly affecting the results?

# Exploratory Data Analysis in Power BI 📑

![image](https://github.com/user-attachments/assets/acb6d5a0-cba3-4376-9c78-b30a5b5f290d)

1) Define Benchmarks / Statistical Summary and Interpretation:
- Median of income: 60k
- Median of children: 2
- Median of age: 43 → 41 (buyer audience) and 44 (non-buyer audience).
- Median of cars: 1 → 1 (buyer audience) and 2 (non-buyer audience).

2) Analyze Purchasing Patterns / Trends Over Time:
- Pattern identified 1: The audience that buys the most are people who work close to home ‘0-1 miles’, ‘1-2 miles’ and ‘2-5 miles’.

![image](https://github.com/user-attachments/assets/4581fe8a-58c8-480c-ab8b-24490ff72ed9)

- Identified pattern 2: People with Bachelor's and Partial College are the ones who buy the most.

![image](https://github.com/user-attachments/assets/ee64243f-a5ed-4e6c-91d1-51352625be3d)

- Identified pattern 3: It is observed that those who have one child have greater purchasing potential than those who have more children, as observed in the graph.
  
![image](https://github.com/user-attachments/assets/2adfae08-8758-4b22-b2ee-37b0865c544a)

- Identified pattern 4: Analyzing the number of cars that people who buy bicycles have, on average, those who buy bicycles have only 1 car, and those who do not buy bicycles have two cars.

Bought:

![image](https://github.com/user-attachments/assets/14017926-d419-4442-816e-f9cca7a3dee4)

Did not buy:

![image](https://github.com/user-attachments/assets/8820b013-2da8-4267-b2fd-75d71f1db62b)

3) Generate Hypotheses:
- Hypothesis 1: Those who have only one car are more likely to buy a bicycle.
- Hypothesis 2: Those who live 0-5 miles from work are more likely to buy a bicycle.
- Hypothesis 3: Those who have only 1 child are more likely to buy a bicycle.

4) Examine Relationships (Identify Relationships Between Variables):
Since the graph shows the same dispersion between the purchased and non-purchased audiences, there is no relationship between the regions, this may just be a question of sample difference between the regions for research.

![image](https://github.com/user-attachments/assets/780e9601-01d9-4f34-ae1e-bd743e695531)

There is no difference between genders for those with greater purchasing potential.

![image](https://github.com/user-attachments/assets/cc8c71bd-c3a2-499c-85f3-2752a1ef3a09)

5) Check Anomalies:

Research was conducted with a larger number of people in Europe, which may change the results relatively due to cultural differences:

![image](https://github.com/user-attachments/assets/d773d0cb-7485-4fb3-9ba8-51c1f748eaa7)


# Insights💡

- It is considered interesting to apply campaigns, for example, covering the health factor, so that people who live closer to work (distance between 0-5 miles) will be encouraged to go to work by bike
- In addition, filtering campaigns for people with only one car is something worth exploring, so you can compare the price of buying a second car with just a simple decision to buy a bicycle

# Recommendations 🛠️

- Why is this drop occurring? Campaigns are not targeted to the right audience. It is important to consider the number of children, the distance between home and work, and the number of cars these people have
- Is this temporary or a trend? It is a permanent trend, since people who have more children will have more cars, and in addition, those who live further from work do not use their bikes to go to work, for example (or if they live far from work, they probably do not have enough time to ride a bike)
- What are the factors that most impact the purchasing decision? Number of children, number of cars, and the distance between home and work

