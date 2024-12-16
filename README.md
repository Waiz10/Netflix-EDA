# Netflix Dataset Analysis with PySpark

This project performs exploratory data analysis (EDA) on the Netflix TV Shows & Movies dataset using PySpark. The analysis aims to extract meaningful insights, such as content trends, frequent actors, country-wise content distribution, and rating patterns.

---

## Getting Started

### Prerequisites

Before running the analysis, ensure you have the following installed:

- **Docker**: To create a containerized development environment.
- **PySpark**: For distributed data processing.
- **Jupyter Notebook**: For interactive data exploration.

### Setup

1. **Install Docker**:
   - Download and install Docker from [here](https://www.docker.com/).

2. **Pull the PySpark Docker Image**:
   - Run the following command in your terminal to pull the image:
     ```bash
     docker pull jupyter/pyspark-notebook
     ```

3. **Start the Docker Container**:
   - Use the following command to start the container:
     ```bash
     docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
     ```
   - Navigate to `http://localhost:8888` in your browser to access the Jupyter Notebook server.

4. **Download the Dataset**:
   - Visit the [Netflix TV Shows & Movies Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).
   - Download the dataset and place it in your working directory as `netflix_titles.csv`.

5. **Run the Analysis**:
   - Open a Jupyter Notebook in your browser.
   - Copy and paste the provided analysis code into a new notebook cell.
   - Execute the cells sequentially to perform the analysis.

---

## Results

### 1. Total Content by Content Type
- **Objective**: Analyze the distribution of movies and TV shows.
- **Insight**: Most content in the dataset consists of [insert result].

### 2. Most Frequent Actors in the Dataset
- **Objective**: Identify the top 10 actors with the highest number of appearances.
- **Insight**: The most frequent actors are [insert result].

### 3. Yearly Trend of Content Addition
- **Objective**: Examine how Netflix's catalog has grown over the years.
- **Insight**: Content production has increased significantly since [insert result].

### 4. Top 10 Countries with the Most Content
- **Objective**: Determine the countries producing the highest volume of content.
- **Insight**: The top contributors are [insert result].

### 5. Rating Distribution
- **Objective**: Analyze the distribution of content ratings.
- **Insight**: The most common ratings are [insert result].

### 6. Shortest Title Names
- **Objective**: List the top 10 titles with the shortest names.
- **Insight**: The shortest titles include [insert result].

### 7. Correlation Between Release Year and Content Count
- **Objective**: Explore the relationship between release year and content volume.
- **Insight**: The correlation indicates [insert result].

---

## Contribution

If you'd like to contribute to this project:

1. Fork this repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. For more information, see the [LICENSE](./LICENSE) file.
