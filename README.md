📺 OTT Web Series Data Analysis
This project performs a detailed data visualization analysis of 2644 web series from various OTT platforms like Netflix, Prime Video, Disney+ Hotstar, Zee5, SonyLIV, and more. Using Python’s powerful libraries like Pandas, Matplotlib, and Seaborn, it uncovers insights about viewer preferences, performer popularity, and platform-wise content trends.

📁 Dataset Overview
File Used: webseries.csv

Total Entries: 2644

Features:

series_name

director_name

genre (includes year and episode count)

ratings (user-based)

performers

ott_platform

🔍 Key Objectives
Explore the landscape of OTT content distribution.

Compare content offerings and quality (ratings) across platforms.

Identify top-rated genres, directors, and performers.

Visualize OTT market trends and patterns.

📊 Visual Analysis Performed
Rating Distribution: Histogram of all web series ratings.

Platform Popularity: Bar chart showing how many series are on each OTT platform.

Netflix vs. Others: Comparative analysis of ratings between Netflix and non-Netflix platforms.

Genre Distribution: Visualization of which genres dominate the OTT landscape.

Top Performers: Bar chart of the most frequently appearing actors across platforms.

Director Analysis: Number of series directed per director.

Rating vs Genre: Scatter plot for visualizing rating trends across genres.

Platform vs Genre: Stacked bar chart showing genre-wise contribution of each platform.

💡 Insights & Observations
Netflix hosts the largest number of web series, making it a strong choice for subscribers.

Top genres include a mix of thriller, drama, and documentaries.

Most influential performers appear across multiple top-rated series.

Series with fewer episodes often receive higher ratings, hinting at tighter storytelling.

Platform-genre preferences vary: some specialize in thrillers, others in documentaries or drama.

🧰 Libraries Used
pandas

numpy

matplotlib

seaborn

🧑‍💻 How to Run the Notebook
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/ott-webseries-analysis.git
cd ott-webseries-analysis
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Launch the notebook:
Open DVP_miniproject.ipynb in Jupyter Notebook or Google Colab.

🚀 Future Work
Add release year extraction and time-series analysis.

Perform sentiment analysis on user reviews.

Develop a recommendation engine based on user ratings and genre.

