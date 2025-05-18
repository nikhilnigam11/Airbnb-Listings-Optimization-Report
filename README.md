##Airbnb Listings Optimization Analysis##

📌 Project Overview
  - This project analyzes Airbnb listing data to determine:
  - Minimum number of images required to ensure bookings.
  - Optimal number of images to maximize bookings.

Key Insights:
  - Listings with 6–15 images attract the most bookings.
  - 11–15 images are optimal for maximizing bookings.
  - Minimum 6 images ensure at least 1 booking/month.

🛠️ Tools & Technologies
    Languages: Python
    Libraries: Pandas, NumPy, Matplotlib, Seaborn
    Visualization: Tableau
    Data Sources: Airbnb 

🔍 Key Findings
  Open Listings:
    - Listings with 0–5 images had the highest unfilled rates (~30%).
    - 6–15 images had the lowest open listings (highest bookings).

Redundant Listings:
    -  11–15 images had only 5% redundancy (vs. 30% for 0–5 images).
    -  Bookings Distribution:
    -  Regular hosts: 12–13 images → highest median bookings.
    -  Superhosts: 11–23 images → optimal performance.

📈 Recommendations for Airbnb
    - Set a minimum of 6 images for all listings.
    - Recommend 11–15 images to maximize bookings.
    - Host-specific guidance:
    - Regular hosts: 11–15 images.
    - Superhosts: 11–23 images (flexible).
