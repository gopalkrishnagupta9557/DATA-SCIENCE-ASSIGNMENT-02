🎬 Movie Data Analysis using Python

📌 Project Overview
This project focuses on analyzing a movie dataset using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The dataset includes details like budget, revenue, genres, language, cast, and crew.

The main objectives of this analysis are to explore:

* Movie profitability
* Return on Investment (ROI)
* Popular actors and directors
* Performance across different languages
* Distribution of movie genres

🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

📂 Dataset

* Dataset name: imdb_data.csv
* Contains approximately 3000 movie records

Key attributes include:

* Budget
* Revenue
* Genres
* Language
* Cast & Crew

⚙️ Data Preprocessing

* Removed entries with zero budget

* Created new metrics:
  Profit = Revenue - Budget
  ROI = Profit / Budget

* Extracted key information:

  * Director from crew data
  * Producer from crew data
  * Actors from cast data

📊 Analysis & Results

✅ Q1. Movie with Highest Profit

* Identified the most profitable movie
* Extracted details like director, producer, and cast

✅ Q2. Language with Highest ROI

* Calculated average ROI for each language
* Determined the top-performing language

✅ Q3. Unique Genres

* Extracted all distinct genres
* Analyzed the diversity of movie categories

✅ Q4. Top Producers

* Built a dataset of producers and directors
* Identified the top 3 producers based on average ROI

✅ Q5. Most Frequent Actor

* Found the actor appearing in the highest number of movies
* Analyzed:

  * Their filmography
  * Genre preferences
  * Profit trends

✅ Q6. Directors & Their Preferred Actors

* Selected top 3 directors
* Identified actors they collaborate with most frequently

📈 Visualizations
The project includes a variety of visual insights:

* Bar charts (ROI, top movies, producers)
* Pie chart (language distribution)
* Histogram (profit distribution)
* Scatter plots (budget vs revenue, ROI vs profit)
* Heatmap (correlation analysis)

📌 Key Insights

* A higher budget does not necessarily lead to higher profit
* Certain languages yield better ROI
* Strong collaboration patterns exist between specific actors and directors
* Revenue shows a strong positive correlation with profit

🚀 How to Run

1. Open Google Colab
2. Upload the dataset:
   from google.colab import files
   files.upload()
3. Execute the notebook step-by-step
4. Review outputs and visualizations

📎 Project Structure
├── imdb_data.csv
├── Movie_Analysis.ipynb
└── README.md

🎯 Conclusion
This project showcases how data analysis and visualization techniques can uncover valuable insights from movie datasets. It provides a deeper understanding of profitability trends, language performance, and collaboration patterns in the film industry.

🙌 Author
Gopal Krishna Gupta
