
## 📱 Overview

This project analyzes Google Playstore apps to understand trends in app development, usage, and user engagement. It explores aspects such as app categories, user ratings, number of installs, content ratings, and pricing models to extract insights—such as the most common app types, trends in app ratings, and how pricing may relate to user reviews.

---

## 📂 Dataset Details

The dataset used in this analysis contains 13 columns:

| Column Name    | Description                                             |
|----------------|---------------------------------------------------------|
| App            | Name of the application                                 |
| Category       | Category under which the app is listed                  |
| Rating         | User rating of the app (out of 5)                       |
| Reviews        | Number of user reviews                                  |
| Size           | Size of the app (as displayed in the Playstore)         |
| Installs       | Total installs (formatted with + and commas originally) |
| Type           | Whether the app is Free or Paid                         |
| Price          | Cost of the app (if Paid)                               |
| Content Rating | Target audience (Everyone, Teen, etc.)                  |
| Genres         | Subcategories or genres of the app                      |
| Last Updated   | Last update date of the app                             |
| Current Ver    | Current version of the app                              |
| Android Ver    | Minimum Android version required                        |

🔹 **Download the dataset**: [Google Playstore Dataset – CSV](https://raw.githubusercontent.com/krishnaik06/playstore-Dataset/main/googleplaystore.csv)
🔹 **Cleaned Dataset**: The cleaned version of the dataset used for analysis is available in this repository as [`google_cleaned.csv`](google_cleaned.csv).


---

## 📌 Key Insights

### 🛠 Handling Data Issues

✅ Cleaned the `Installs`, `Price`, `Size`, and `Reviews` columns by removing extra characters and converting them to numeric formats.  
✅ Removed rows with missing or invalid values in key columns (like `Rating`).  
✅ Removed duplicate entries to maintain data consistency.

---

### 📊 App Trends & Patterns

📌 **Top Categories**: Found the most common app categories by count.  
📌 **Rating Distribution**: Analyzed user ratings and identified the most frequent rating ranges.  
📌 **Paid vs Free**: Compared ratings and review trends between Free and Paid apps.  
📌 **Content Ratings**: Visualized which content ratings dominate the app ecosystem.  
📌 **Genres Analysis**: Found the most common app genres.  
📌 **Size Distribution**: Examined app size spread to understand storage needs.

---

### 💰 Pricing and Reviews

Analyzed how app price relates to user reviews and ratings.  
Scatter plots and box plots were used to compare distributions between Free and Paid apps and their engagement metrics.

---

## 🛠️ Technologies Used

🐍 **Python** (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`)  
📓 **Jupyter Notebook** for data analysis and visualization
