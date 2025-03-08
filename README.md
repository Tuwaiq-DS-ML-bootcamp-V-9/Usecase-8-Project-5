# 📊 Coursera Courses Analysis

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of a Coursera courses dataset. The goal is to uncover insights about course subjects, institutions, trending skills, and popular course topics.

## 📂 Dataset Information
- **File Name:** `Coursera.csv`
- **Contains:** Course titles, subjects, institutions, ratings, reviews, gained skills, and levels.
- **Source:** [Kaggle - Coursera Courses and Skills Dataset 2025](https://www.kaggle.com/datasets/yosefxx590/coursera-courses-and-skills-dataset-2025)

## 🛠️ Technologies Used
- **Python Libraries:** Pandas, Matplotlib, Seaborn
- **Jupyter Notebook:** For interactive data analysis, visualization and web scraping

## 📊 key Insights
✔ **Number of Courses by Subject** – The most popular subjects are Business, Computer Science, Data Science, and Information Technology. Business and Computer Science have the highest number of courses.
<img src="images/image.img" alt="Number of Courses by Subject" width="200">
✔ **Top 10 Most Common Words in Course Titles** – The most frequent words in course titles are "data," "ai," and "learning," indicating a strong focus on data-related and AI topics.
<img src="images/image1.img" alt="Top 10 Most Common Words in Course Titles" width="200">
✔ **Top 10 Institutions with Most Courses** – IBM and Coursera Project Network offer the highest number of courses. Universities like the University of Michigan and the University of Colorado Boulder also have a significant presence.
<img src="images/image2.img" alt="Top 10 Institutions with Most Courses" width="200">
✔ **Top 10 Skills Gained For All Courses** – The most sought-after skills include Data Analysis, Machine Learning, and Artificial Intelligence. Skills like Generative AI and Data Ethics are also prominent, reflecting current trends in technology.
<img src="images/image3.img" alt="Top 10 Skills Gained For All Courses" width="200">
✔ **Number of Courses by Level** – The majority of courses are at the Beginner level, followed by Intermediate and Mixed levels. Advanced courses are the least common, indicating a focus on foundational and intermediate knowledge.
<img src="images/image4.img" alt="Number of Courses by Level" width="200">
✔ **Number of Courses by Learning Product Type** – The most common learning product type is "Course," followed by "Specialization" and "Guided Project." Professional Certificates are less common compared to other types.
<img src="images/image5.img" alt="Number of Courses by Learning Product Type" width="200">
✔ **Number of Courses by Duration** – Most courses have a duration of 1 - 4 weeks or 1 - 3 months. Longer courses (3 - 6 months) and very short courses (Less Than 2 Hours) are less common.
<img src="images/image6.img" alt="Number of Courses by Duration" width="200">
✔ **Relationship Between Ratings and Reviews** – There is a positive correlation between the number of reviews and the rating of courses. Courses with higher ratings (4.0 - 5.0) tend to have more reviews, suggesting that well-received courses attract more feedback.
<img src="images/image7.img" alt="Relationship Between Ratings and Reviews" width="200">

## 📈 Visualizations
The project includes multiple visualizations, such as:
- **Bar Charts**: Distribution of courses by subject
- **Count Plots**: Popular institutions and skills
- **Word Clouds**: Common words in course titles

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/coursera-eda.git
   ```
2. Navigate to the project folder:
   ```bash
   cd coursera-eda
   ```
3. Install required dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Open and run `project.ipynb` in Jupyter Notebook:
   ```bash
   jupyter notebook project.ipynb
   ```

## 📜 Project Files
- `web Scraping.ipynb` – Jupyter Notebook For Scraping the data
- `EDA_explain_template.ipynb` – Documentation explaining the analysis process
- `Coursera.csv` – The dataset used for analysis

## 📌 Machine Learning Methodology
### Model Selection
Two different unsupervised machine learning models were trained for the task.

### Feature Engineering
Steps taken to enhance model performance:
- **Encoding categorical data**
- **Feature scaling and normalization**
- **Extracting new features from existing ones**

### Hyperparameter Optimization
Tuning was performed to improve model accuracy and efficiency.

### Performance Evaluation
- Various metrics and visualizations were used to compare models.
- The best-performing model was selected based on key performance indicators.

## 👥 Contributors
- **Mushal Alshagha**
- **Emtnan Alomireni**
- **Naser Almanaa**
- **Yousef Alharbi**
