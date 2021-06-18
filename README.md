# Amazons-SEO-Plan-And-It's-Impact-On-Sales
As part of this article, we'll analyze how search engine optimization (SEO) can affect product sales in five different categories. We'll explore these products by finding an overlap correlation between the product's title &amp; description against the reviews and/or question and compare these results with Amazon's "best seller rank" or BSR.
# Data Sources
Using the Selenium module and Python, all the data is scraped from hundreds of products listed in Amazon. The titles, descriptions, reviews, and questions are processed using NLTK. Whereas correlations are found using Python's native library, Counter. After cleaning and processing all our data, we've used MatplotLib to visualize it.

# Data Analysis:
 The five categories we’ve decided to analyze are:
●              Health & Household
●              Kitchen & Dining
●              Carry-On Luggage
●              Antitheft Keyless Entry System
●              Acoustic Guitar Stands & Hangers

We'll scrap all the data we can from non-sponsored, ranked products.To have better results and cleaner data to handle, we'll be saving our work, non-processed data into JSON, and we'll scrap our products procedurally:

●              Product listings > listing_scraper.py
●              roduct posts > product_scraper.py
●              Product ranking > bsr.py
●              Reviews > scrap_reviews.py
●              uestions > scrap_questions.py

# Analysis results
The data visualisation is interesting as it will help find relationships and trends! We will follow the process by using MatplotLib script. Now let us consider our results to explore the correlation between review overlaps under the carry-on luggage products. 

# Summary
After analyzing the visuals, it is safe to say that the reviews and questions overlap. However, this is not always the case. There are also a few products that showcase low or no correlation between their ranking and overlap. Therefore, we can say that SEO for products and titles will help boost the rank of products, but this is not the sole cause of their current ranking.

# How Can MindTrades help?
MindTrades Consulting Services, a leading marketing agency provides in-depth analysis and insights for the global IT sector including leading data integration brands such as Diyotta. From Cloud Migration, Big Data, Digital Transformation, Agile Deliver, Cyber Security, to Analytics- Mind trades provides published breakthrough ideas, and prompt content delivery. For more information, check [https://www.mindtrades.com].

