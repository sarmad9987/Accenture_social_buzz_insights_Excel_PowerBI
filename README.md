# Accenture_social_buzz_insights_Excel_PowerBI

![accenture-logo](https://user-images.githubusercontent.com/90148389/216854479-4858e08e-0f6a-4f7b-89da-d32615bf792c.png)

### Accenture data analytics and visualization virtual internship
This repository is part of my virtual inetrnship in data analytics and visualization intersnhip and I have explained how I carried out and completed the project.

## Introduction:
As a data analyst, I have been tasked with analyzing the client's data to uncover insights, create visualizations, and present my findings. To accomplish this, I utilized Microsoft Excel for data cleaning and generating insights, Microsoft Power BI for data visualization, and Microsoft PowerPoint for creating presentation slides. Due to their rapid growth, the client lacks the internal resources to effectively manage their data.


### Insights:

1. The top 5 most popular categories, in descending order, were animals, science, healthy eating, technology, and food. Animals had an aggregate score of 74965. Healthy eating is more popular than food and science and technology also rank high, indicating a preference for factual and informative content.

![Screenshot 2023-02-06 002733](https://user-images.githubusercontent.com/90148389/216855684-02af44a9-bef1-4c05-9f6d-d9bfb807ca1e.png)



2. The chart illustrates the popularity split among the top 5 categories. The categories are close in popularity, but animals have a slightly larger share, 1.1% more, than the second-ranked category, science. This suggests that animals may continue to grow more popular than the other categories. To maintain a fair balance of content on the platform, it's important to use algorithms that distribute the categories evenly.

![Screenshot 2023-02-06 003145](https://user-images.githubusercontent.com/90148389/216856227-9c95c868-98c4-4e23-b464-a5908644ad07.png)


### Complete Dashboard:

![Screenshot 2023-02-06 003607](https://user-images.githubusercontent.com/90148389/216856369-4619e2dd-82a7-43de-8788-2cfdbc0c68d6.png)



## Skills and concepts Used to carry complete the project. (EXCEL and PowerBI)

**1. Joining the Data**

```Vlookup```

**2. Aggregating scores with top 5 categories**

```SUMIF```

**3. Count of top scoring cateogry**

```COUNTROWS(FILTER (Reactions, Reactions[Category] = "Animals"))```

**4. Count of unique categories**

```distinct_categories = CALCULATE(DISTINCTCOUNT(Reactions[Category]))```



