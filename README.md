![cover](https://github.com/iqbalstilllearning/sales-analysis-adidas-US/assets/105572256/b9dd6516-fdc9-4a89-8a60-fa453d2203ed)
# **Problem Statement**

In navigating the dynamic retail landscape of the United States, Adidas faces the imperative to conduct a comprehensive analysis of sales and forecasting to comprehend market trends, influential factors, and future growth potential. Presently, the company encounters several challenges, including fluctuating customer demand, seasonal variations, and intense competition within the footwear and sportswear industry. Uncertainties in evolving consumer trends and external factors that may impact sales necessitate an innovative and targeted solution. Therefore, the objective of this project is to compile an in-depth analysis of past sales data, identifying patterns and key factors influencing Adidas sales in the United States. This project also aims to develop an accurate and reliable forecasting model, leveraging machine learning techniques and statistical analysis. Thus, the company can make informed decisions regarding inventory, marketing, and sales strategies, minimizing risks and enhancing operational efficiency. Through a better understanding of consumer behavior, market trends, and potential risk factors, Adidas expects to optimize their sales strategies, increase market share, and achieve sustainable growth in the U.S. market.

- The dataset utilized originates from Kaggle ([Here](https://www.kaggle.com/datasets/bcnishantreddy/adidas-us-sales-datasets)).

# **Research Questions**
1. What is the overall sales performance in Adidas product and retailer in the US?
2. What is the overall trend in Adidas sales in the US over the specified time period?
3. Is there a variation in product preferences at each retailer and which retailer in the US contributes the most to Adidas profit for each product?
4. Which city, state, and region in the US contribute the most to Adidas sales, and are there any regional variations in product preferences?
5. Is there a correlation between the Units Sold, Total Sales, and Operating Profit for Adidas products in the US?
6. What is the most effective sales method to use, and what is the variation in sales methods for Adidas across different retailers?
7. How to sales Forecast w/ Arima, Sarima, & ExponentialSmoothing Holt-Winters?
   
# **Data Preparation**
The data analysis is performed using Python in Jupyter Notebook to gain insights about the data. This involves various data preprocessing, cleaning, transformation, analysis, forecasting, and visualization tasks to prepare the data for further analysis.

Notebook: [Link](https://github.com/iqbalstilllearning/sales-analysis-adidas-US/blob/main/Adidas%20Sales%20Analysis%20%26%20Forecasting%20in%20US.ipynb)

# **Conclusion**

1. The results shows that the performance of Adidas products in the United States is evaluated based on Units Sold, Total Sales, and Operating Profit. Men's Street Footwear emerges as the best-selling product with 593,320 units sold. On the other hand, Men's Apparel is the least popular product with only 30,683 units sold. Additionally, Men's Street Footwear stands out with the highest sales and profit, amounting to $208,826,244.00 and $82,802,260.62, respectively.

2. The overall trend in Adidas sales in the US over the specified month-wise and year-wise analysis indicates that, on a month-wise basis, both sales and profit exhibit a fluctuating pattern. July emerges as the best-performing month and August based on profit, while March stands out as the least favorable. On a year-wise analysis, sales and profit in 2021 show improvement compared to 2020.

3. Based on Units Sold, Adidas products are predominantly sold through Gear Wear, except for Men's Street Footwear, which sees the highest sales through Foot Locker. In terms of profit, Foot Locker contributes the highest profit for Men's Street Footwear. Sports Direct leads in profit for Women's Apparel, while Gear Wear tops the list for Women's Street Footwear, Women's Athletic Footwear, Men's Athletic Footwear, and Men's Apparel.

4. The cities that contribute the most to Adidas sales in the US are Charleston, New York, and San Francisco, while the leading states are New York, California, and Florida. Additionally, the West region stands out as the top-performing region for Adidas sales in the US. Men's Street Footwear exhibits the highest sales in every region except the South, where Men's Apparel takes the lead as the best-selling product.

5. Overall, the correlation matrix suggests strong positive correlations between all three variables. This means that as Units Sold, Total Sales, and Operating Profit increase, the other two variables tend to increase as well. Here's a breakdown of the specific correlations:
    - Units Sold and Total Sales: The correlation coefficient of 0.98 indicates a very strong positive correlation. This means that as the number of units sold increases, the total sales amount also increases, and vice versa.
    - Total Sales and Operating Profit: The correlation coefficient of 0.96 also suggests a very strong positive correlation. This implies that as total sales increase, operating profit also tends to increase, and vice versa.
    - Units Sold and Operating Profit: The correlation coefficient of 0.91 represents a strong positive correlation. This suggests that as the number of units sold increases, operating profit also tends to increase, although not as strongly as the correlation between Total Sales and Operating Profit.

6. Online is the most prevalent sales method used by Adidas, this is likely due to the increasing popularity of online shopping among consumers. In-store is the second most common sales method used by Adidas, this is likely due to the convenience of shopping at physical stores and the opportunity to try products on directly. Outlets are the least common sales method for Adidas, this is likely due to the lower prices at outlets, which may attract bargain-hunting consumers.

# **Suggestions (Based  on Conclusions)**
**1. Sales and Profit Optimization Based on Best-Least Product**

By observing that Men's Street Footwear emerges as the best-selling product and Men's Apparel is the least popular, Adidas can focus on marketing strategies and boosting sales for these products. This may involve:
    
**for Men's Street Footwear (Best-Selling):**
- Keep Men's Street Footwear fresh with innovative designs and collaborations.
- Launch limited editions to create exclusivity and drive demand.
- Develop targeted campaigns emphasizing unique features.
- Implement exclusive loyalty programs for Men's Street Footwear buyers.
- Explore variations within Men's Street Footwear for market diversity.

**for Men's Apparel (Least Popular):**
- Revamp Men's Apparel with new styles aligned with trends.
- Create promotions bundling Men's Apparel with other products.
- Develop strategies to appeal to a broader audience.
- Introduce limited-time discounts to boost Men's Apparel sales.

**2. Month and Year (wise) Optimization**

Adidas should align marketing strategies with seasonal trends, implementing targeted campaigns and managing inventory effectively to address the month-wise fluctuations observed in sales and profit. Specifically, focusing on peak months like July can capitalize on increased consumer activity. For year-wise improvements, the brand should analyze successful factors contributing to the growth in 2021 and develop a strategic plan accordingly.

**3. Best Products at the Top Retailers**

Adidas can strategically enhance its performance across different retailers by tailoring approaches to each key partner. Firstly, with Gear Wear serving as the overall sales leader, Adidas should intensify collaboration by introducing exclusive releases and joint marketing initiatives. This concerted effort aims to broaden the consumer reach and solidify the brand's presence in the market. Simultaneously, with Foot Locker dominating in Men's Street Footwear sales, Adidas should capitalize on this success through exclusive collaborations. Such collaborations can not only sustain the demand for Men's Street Footwear but also attract Foot Locker's specific customer base, creating a mutually beneficial relationship. Additionally, recognizing Sports Direct as the leader in Women's Apparel profitability, Adidas should prioritize collaborative efforts to optimize the Women's Apparel product line.

**4. Regionalized Triumph: Tailored Strategies for Adidas Sales in US**

Each location represents diverse consumer preferences and lifestyles, necessitating tailored marketing approaches. For instance, New York may benefit from exclusive collections and dynamic in-store experiences, while California could focus on active lifestyle campaigns. In Florida, season-specific promotions emphasizing athleisure wear for warm climates may be key. The West region's success indicates an opportunity for Adidas to tap into the innovation-driven and outdoor-focused culture, introducing technologically advanced sports gear. Additionally, in the South, where Men's Apparel leads in sales, a strategic emphasis on expanding and promoting this product line can enhance overall performance. This region-specific approach enables Adidas to strengthen its market presence, cater to diverse consumer demands, and sustain success across key cities, states, and regions in the United States.

**5. Capitalize Units Sold, Sales, and Profit Correlations**

To capitalize on these correlations, a strategic focus on driving Units Sold becomes pivotal. This could involve targeted marketing campaigns, product promotions, and enhanced distribution channels to stimulate sales growth. Furthermore, given the robust connection between Total Sales and Operating Profit, a holistic approach to revenue generation and cost management is essential. Strategies that optimize pricing, streamline operational efficiency, and leverage economies of scale can contribute to maximizing both Total Sales and Operating Profit. The correlation between Units Sold and Operating Profit, though slightly less strong, still underscores the importance of operational efficiency in converting sales into profitability. In essence, a comprehensive strategy that aligns marketing efforts with driving sales, while concurrently optimizing operational aspects, can harness these correlations for sustained business success.

**6. Improve and Optimize Sales Method**

To leverage this prevalent method, continuous enhancements to the online shopping experience, such as user-friendly interfaces, personalized recommendations, and efficient order processing, can be implemented. Additionally, targeted digital marketing campaigns and exclusive online promotions can further capitalize on the popularity of e-commerce, engaging with consumers and driving online sales growth. While online sales dominate, the acknowledgment of in-store shopping as the second most common method highlights the enduring importance of physical retail spaces. Adidas can optimize this channel by prioritizing an immersive in-store experience, incorporating innovative technologies like augmented reality for virtual try-ons, and organizing exclusive in-store events to attract foot traffic. Furthermore, emphasizing the seamless integration of online and in-store experiences, such as click-and-collect services and online-exclusive products available for in-store purchase, can create a cohesive shopping journey for consumers. Lastly, for outlets, exploring strategies to highlight the unique value proposition of outlet purchases, such as exclusive discounts or limited-edition releases, may attract bargain-seeking customers and increase the appeal of this sales channel.

![close](https://github.com/iqbalstilllearning/sales-analysis-adidas-US/assets/105572256/bd764ebb-5c8f-4e4f-bc58-2fc0098c5378)

**Links: [[Linkedin](https://www.linkedin.com/in/muhammadiqbal-/)] [[Github](https://github.com/iqbalstilllearning/)] [[Gmail](muhammadiqbal4edu@gmail.com)]**
