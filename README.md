**Netflix Movie Data Analysis**

This Python script allows you to analyze Netflix movie data using the Pandas and Matplotlib libraries. By running this script, you can gain insights into the distribution of movie durations across different release years, visualizing them with color-coded genres. Below is a brief guide on how to use the script effectively.

**Getting Started**

*Prerequisites:*  Ensure you have Python installed on your system along with the necessary libraries: Pandas and Matplotlib. 

*Dataset:*  Make sure you have the Netflix movie dataset (netflix_data.csv) placed in the same directory as the script. If not, modify the script to specify the correct file path.

**Understanding the Script**

The Python script begins by importing the required libraries, Pandas and Matplotlib. 

It then reads the Netflix dataset into a Pandas DataFrame (netflix_df). The columns of the DataFrame are printed to confirm successful loading.

Next, the unique values of the "type" column are printed to identify how movies are categorized in the dataset.

The script then filters the DataFrame to include only movies and selects relevant columns for analysis: title, country, genre, release year, and duration.

For visualization, the script assigns colors to movies based on their genres. Movies categorized as "Children" are marked in red, "Documentaries" in green, "Stand-Up" in yellow, and all other genres in black.

Finally, the script creates a scatter plot using Matplotlib, visualizing the relationship between movie duration and release year. Each data point is color-coded based on its genre.

**Running the Script**

Upon execution, the script will generate a scatter plot visualizing movie durations by their release years, with colors representing different genres.

**Conclusion**

This Python script provides a straightforward approach to analyzing Netflix movie data, offering insights into movie durations and their distribution across different genres and release years. By customizing the script or extending its functionality, you can further explore and analyze the dataset to gain deeper insights into Netflix's movie catalog.
