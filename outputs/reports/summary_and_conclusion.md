# Amazon Sales Dataset EDA

## Project Summary

My insightful exploration of the Amazon Sales dataset, characterized by its remarkable cleanliness and consistency, yielded a wealth of findings. Through a series of targeted inquiries, we unlocked detailed answers and highlighted previously veiled aspects of the data as follows:

### Q1: What is the average rating for each product category?  
**Answer 1:**  
Most product categories have generally positive customer feedback, with average ratings above 3.50. However, some categories (e.g., 2 and 3) have lower ratings, suggesting areas for improvement. Further analysis could help identify the reasons for lower feedback and potential solutions.

### Q2: What are the top rating_count products by category?  
**Answer 2:**  
- Products with high review counts are likely popular within their categories, indicating strong customer interest and engagement.  
- Review counts range from 9 to 15,867, showing varying attention across products.  
- Most products have ratings above 3.5, indicating generally positive experiences.  
- Products with the highest review counts could be considered potential top sellers, even without direct sales data.

### Q3: What is the distribution of discounted prices vs. actual prices?  
**Answer 3:**  
- Discounted prices are generally lower than actual prices, with a median discounted price of $200 and a median actual price of $400.  
- Discount percentages are mostly 30% or less and skewed to the left.  
- This suggests opportunities to optimize discounts to attract more customers.

### Q4: How does the average discount percentage vary across categories?  
**Answer 4:**  
- Average discounts vary widely, ranging from 0% to 78.39%.  
- Categories 1 and 3 have notably higher average discounts (78.39% and 56.34%), possibly due to clearance efforts, competition, or lower margins.  
- Categories 0, 206, 207, and 210 have 0% discounts, indicating stable pricing or strong demand.  
- Other categories show varying discounts, reflecting diverse pricing strategies.

### Q5: What are the most popular product names?  
**Answer 5:**  
- *Fire-Boltt Ninja Call Pro Plus Smart Watch* is the most popular product, followed by *Fire-Boltt Phoenix Smart Watch*.  
- Smart Watches and Charging Cables are the most popular product categories.  
- Multiple brands are represented, with boAt appearing twice.  
- Key features include fast charging, durability, and functionality.  
- Popularity is relatively evenly distributed beyond the top products.

### Q6: What are the most popular product keywords?  
**Answer 6:**  
- USB connectivity, charging (especially fast charging), and cables are prominent features.  
- Words like "with," "for," "and," "to" indicate product compatibility and usage scenarios.  
- Cables and smart devices are well-represented.  
- Product names are concise and use common words, which could benefit from refined keyword extraction techniques.

### Q7: What are the most popular product reviews?  
**Answer 7:**  
- Overall sentiment scores are relatively low, leaning neutral or slightly negative.  
- The most positive review: *“I have installed this in my kitchen working fine”* (product_id 1463), score: -0.170167.  
- The most negative review: *“tv on off not working, so difficult to battery charge”* (product_id 155), score: -0.600000.  
- Issues highlighted include battery charging, product quality, and ease of use.  
- Some reviews mix positive and negative aspects, e.g., *“Like and happy,,Please don't buy this heater”* (product_id 1237).  

### Q8: What is the correlation between discounted_price and rating?  
**Answer 8:**  
Discounted price and rating have a weak positive correlation. This means that products with higher discounted prices tend to have slightly higher ratings, but the relationship is not very strong.

### Q9: What are the Top 5 categories based with highest ratings?  
**Answer 9:**  
- The top 5 categories have average ratings between 4.50 and 4.60, indicating overall positive customer satisfaction.  
- Most top-rated categories are technology-related, including tablets, networking devices, photography accessories, media streaming devices, and calculators.  
- Within broader categories like "Computers & Accessories" and "Electronics," specific subcategories emerge as particularly well-rated, such as tablets, powerline adapters, film accessories, and streaming clients.  
- Four categories share a rating of 4.50, showing similar customer satisfaction.  
- The presence of "Basic Calculators" in the top 5 suggests that even simple products can achieve high ratings if they meet customer needs effectively.


## Conclusion

The primary goal of this project is to analyze the Amazon Sales dataset and identify insights based on the data. The Amazon Sales dataset is a valuable resource for businesses and researchers alike. It provides a wealth of information about customer behavior, product trends, and market conditions. By conducting exploratory data analysis (EDA) on this dataset, businesses can gain valuable insights that can help them make better decisions about their products, marketing, and operations.¶
During this EDA exercise, we have achieved several milestones:
- We have cleaned the dataset from null values.
- No duplications found in the data.
