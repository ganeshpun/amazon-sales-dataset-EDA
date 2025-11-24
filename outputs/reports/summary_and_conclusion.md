# Amazon Sales Dataset EDA

## Project Summary

My insightful exploration of the Amazon Sales dataset, characterized by its remarkable cleanliness and consistency, yielded a treasure trove of findings. Through a series of targeted inquiries, we unlocked detailed answers and shed light on previously veiled aspects of the data and findings as follows:
Q1: What is the average rating for each product category?
Answer 1:
The output shows that most product categories have generally positive customer feedback, with average ratings above 3.50. However, some categories (e.g., 2 and 3) have lower ratings, suggesting potential areas for improvement. Further analysis of these categories could help identify specific reasons for lower feedback and identify potential solutions.
Q2: What are the top rating_count products by category?
Answer 2:
- The output highlights products likely to be popular within their categories based on high review counts, suggesting customer interest and engagement.
- Review counts range from 9 to 15867, implying varying levels of attention and feedback across products.
- Most listed products have ratings above 3.5, indicating a generally positive customer experience.
- Products with the highest review counts within their categories might be considered potential top sellers, even without direct sales data.
Q3: What is the distribution of discounted prices vs. actual prices?
Answer 3:
- The output shows that discounted prices are generally lower than actual prices, with a median discounted price of $200 and a median actual price of $400.
- The discount percentage distribution is skewed to the left, with most products having a discount of 30% or less.
- The output suggests that there may be opportunities to increase discounted prices or discount percentages to attract more customers.
Q4: How does the average discount percentage vary across categories?
Answer 4:
- Average discount percentages vary widely across categories, ranging from 0% to 78.39%.
- Categories 1 and 3 stand out with notably higher average discounts (78.39% and 56.34%), suggesting potential factors like clearance efforts, high competition, or lower-profit margins.
- Categories 0, 206, 207, 210 have average discounts of 0%, indicating consistent pricing or strong demand for products within those categories.
- Other categories exhibit varying discount percentages, likely reflecting diverse pricing strategies and market dynamics.
Q5: What are the most popular product name?
Answer 5:
- Fire-Boltt Ninja Call Pro Plus Smart Watch is the most popular product, followed by Fire-Boltt Phoenix Smart Watch.
- Smart Watches and Charging Cables are the most popular product categories.
- Multiple brands are represented, with boAt appearing twice.
- Fast charging, durability, and functionality are key features.
- Popularity is relatively evenly distributed beyond the leading product.
Q6: What are the most popular product keywords?
Answer 6:
- USB connectivity, charging (especially fast charging), and cables are prominent product features.
- Prepositions and conjunctions like "with", "for", "and", "to" suggest a focus on explaining product compatibility and usage scenarios.
- Cables and smart devices are likely well-represented in the dataset.
- Product names tend to be concise and use common words, potentially benefiting from refined keyword extraction techniques.
Q7: What are the most popular product reviews?
Answer 7:
- The overall sentiment scores are relatively low, suggesting a tendency towards neutral or slightly negative reviews in the sample.
- The review with the highest sentiment score is "I have installed this in my kitchen working fine" (product_id 1463) with a score of -0.170167, indicating a mildly positive sentiment.
- The review with the lowest sentiment score is "tv on off not working, so difficult to battery charge" (product_id 155) with a score of -0.600000, suggesting a strongly negative sentiment.
- Several reviews mention issues with battery charging (product_id 155), product quality (product_id 1237), and ease of use (product_id 1198), highlighting potential areas for improvement.
- Some reviews express both positive and negative aspects within the same text, like "Like and happy,,Please don't buy this heater" (product_id 1237), suggesting a nuanced evaluation of the product.
- The user_id column seems to contain commas, indicating multiple user IDs for some reviews. This might need investigation to ensure accuracy.
- Reviews for product_id 22, 152, and 723 have identical content, suggesting potential data duplication or errors.
Q8: What is the correlation between discounted_price and rating?
Answer 8:
Discounted price and rating have a weak positive correlation. This means that products with higher discounted prices tend to have slightly higher ratings, but the relationship is not very strong.
Q9: What are the Top 5 categories based with highest ratings?
Answer 9:
- The top 5 categories have average ratings between 4.50 and 4.60, indicating overall positive customer satisfaction within these areas.
- Most of the top-rated categories fall within technology-related domains, including tablets, networking devices, photography accessories, media streaming devices, and calculators.
- Within broader categories like "Computers & Accessories" and "Electronics," specific subcategories emerge as particularly well-rated, such as tablets, powerline adapters, film accessories, and streaming clients.
- Four categories share a rating of 4.50, suggesting similar levels of customer satisfaction across these areas.
- The presence of "Basic Calculators" in the top 5 suggests that even relatively simple products can achieve high ratings if they meet customer needs effectively.

## Conclusion

The primary goal of this project is to analyze the Amazon Sales dataset and identify insights based on the data. The Amazon Sales dataset is a valuable resource for businesses and researchers alike. It provides a wealth of information about customer behavior, product trends, and market conditions. By conducting exploratory data analysis (EDA) on this dataset, businesses can gain valuable insights that can help them make better decisions about their products, marketing, and operations.¶
During this EDA exercise, we have achieved several milestones:
- We have cleaned the dataset from null values.
- No duplications found in the data.
