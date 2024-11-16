# Crunchbase Funding Analysis: Trends, Insights, and Patterns using-python-and Power BI

## **Introduction**
In this project, I set out to uncover insights into the complex world of startup funding. Startups rely heavily on funding to grow and innovate, but understanding the trends and patterns in this space is critical for investors, entrepreneurs, and decision-makers. My goal was to answer important questions about how funding flows across sectors and countries and highlight successes and failures in the startup ecosystem.

### **Disclaimer**

The data used for this project was sourced from publicly available datasets and third-party platforms. While every effort has been made to ensure its accuracy and completeness, the data may contain errors, omissions, or outdated information.  

This project is for research and educational purposes only. The findings and insights are based on historical data and do not guarantee future trends or outcomes. They should not be used as the sole basis for making investment, business, or policy decisions.  

The analysis and visualizations reflect the scope and limitations of the data available and may not capture all startups, funding activities, or global trends. For critical decisions, additional research and validation from authoritative sources are recommended.  

## **Key Questions I Investigated**
1. The number of startups that received funding between 1906 to 2014
2. The total amount all the startups have raised altogether
3. The average funding by sector
4. The most funded sectors
5. Companies that received funding but have closed down
6. The top-funded initial public offering (IPO) companies
7. The total amount received in funding between the years 2000 and 2014

## **Data Collection**
The dataset on funded companies was sourced from Crunchbase to analyze and uncover meaningful trends and insights.

## **Data Cleaning**
The Python code used for data cleaning and preparation is available [here](https://github.com/isah-suleiman/crunchbase-funding/blob/main/data_collection_and_cleaning.ipynb) for you to look over

Using the pandas library, I focused on preparing the Crunchbase funding data for analysis. I started by loading the raw data, cleaning up inconsistencies, filling in missing values, and organizing everything into a neat, structured format. This process ensured that the data was reliable and ready for me to create meaningful insights and visualizations later in the project.

## **Data Analysis and Insights**
After cleaning the data set I exported it in a .csv format. so I could import it into Power BI
```{r}
df.to_csv('cleaned_research_data.csv', index=False )
```
---
![Dashboard](/images/crunch_page-0001.jpg)
---
![Dashboard](/images/crunch_page-0002.jpg)

## **Insights**
1. Between 1906 to 2014 $413 Billion was raised by startups across the world
2. The biotech sector received the most funding at $67 Billion
3. 2007 was the year with the most funding as a total of $32 billion was raised from investors across all industries.
4. Verizon Communications Inc. is the most funded company that went public with its shares. Many companies closed down even after receiving large amounts of funding over many rounds. United Mobile raised a total of $515 million dollars but later closed down.

Feel free to connect with me on LinkedIn [here](https://www.linkedin.com/in/isah-suleiman/)
---

![Dashboard](/images/thank-you.png)
