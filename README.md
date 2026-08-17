[README.md](https://github.com/user-attachments/files/31135441/README.md)
# Sports_Revenue_Analysis
Guided DataCamp project: Analysis of Sports Brands revenue across listing price
# Analyzing Online Sports Revenue

Business analysis of ~3,100 sportswear products (Adidas and Nike): how pricing tiers relate to revenue, and whether product description length is associated with customer ratings and review volume.

## Questions
- How do product volume and average revenue differ across price tiers (Budget / Average / Expensive / Elite) for each brand?
- Do longer product descriptions go together with better ratings or more reviews?

## Data
Four related tables (product info, finance, reviews, brands) joined on `product_id`. Data provided with the DataCamp project.

## Method
Merged the four tables with pandas, removed incomplete records, segmented listing prices into quartile-based tiers (`qcut`), and aggregated product counts, average revenue, ratings and review volume per segment. Visualized with seaborn.

## Key findings
- Adidas dominates the catalogue in every price tier, and its average revenue rises steeply with price: Elite-tier products average roughly 4x the revenue of Budget-tier products (≈8,300 vs. ≈2,000).
- Nike's products cluster in the Budget tier; its mid- and upper-tier segments are thin and comparatively low-revenue in this dataset.
- Ratings are broadly flat (≈3.1–3.4) across description lengths of 200–600 characters — longer descriptions alone show no clear link to better ratings.

## Tools
Python · pandas · seaborn · matplotlib

## Origin
Based on a DataCamp guided project ("Analyzing Online Sports Revenue"). Code tidied and visualizations added.
