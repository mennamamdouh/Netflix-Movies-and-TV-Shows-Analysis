# Netflix-Movies-and-TV-Shows-Analysis
## __Table of Contents__ ##
<ul>

[1. About the project](#about-the-project)

[2. About the dataset](#about-the-dataset)

[3. Tools and libraries](#tools-and-libraries)

[4. Phases of the project](#phases-of-the-project)

<ul>

  [4.1. Data Exploration](#1-data-exploration)

  [4.2. Data Cleaning](#2-data-cleaning)

  [4.3. Data Analysis and Visualization](#3-data-analysis-and-visualization)

</ul>

</ul>

<hr>

## __About the project__ ##
This project is a self-study project, its main objective is to help me practice on a real dataset and strength my analysis skills in Python.
<br>

It is about cleaning and analyzing Netflix movies and tv shows data, and getting insights about the countries where they were filmed, their ratings and release years.
<br>

The detailed notebook of the project is [here](Analyzing%20Netflix%20Data.ipynb).

<hr>

## __About the dataset__ ##
This project's dataset is an open-source data from __Kaggle__.
<br>

> [You can find it here.](https://www.kaggle.com/datasets/shivamb/netflix-shows)

<u>
The dataset contains one "csv" file which has 7787 entries with the following information:
</u>

* __Type__: Movie or TV Show
* __Title__: The name of the movie/tv show
* __Director__
* __Cast__: The names of the movie/tv show's cast
* __Country__: The country(s) which this movie/tv show was filmed
* __Date added__: The date when the movie/tv show was added on Netflix
* __Release year__
* __Rating__: Age-based media reviews
* __Duration__: The number of minutes for movies or number of seasons for tv shows
* __Listed in__: The category(s) which this movie/tv show is listed in
* __Description__: A sentence which describes this movie/tv show on Netflix

<hr>

## __Tools and libraries__ ##
This project was done in Python using Jupyter Notebooks.

The libraries used are:
* __Pandas and Numpy__: for exploration, cleaning and analysis
* __Matplotlib and Seaborn__: for visualizations

<hr>

## __Phases of the project__ ##
### 1. Data Exploration ###

<ul>

After reading the data I have to explore it, its columns, and the info it contains. So, I've gained information about:

1. The dataset size
2. The datatypes of the columns
3. What each column represents
4. What are the information inside the categorized columns such as  __type__, __listed_in__, __rating__ and __country__.

</ul>

<hr>

### 2. Data Cleaning ###

<ul>

After exploring the data, I need to check it if there are any issues.

1. Search for duplicates
  
    * Fortunately, it has no duplicates.

2. Search for nulls

    2.1. Columns with few nulls

   * Solution 1: Get the missing information by searching for them
   * Solution 2: Drop them
    
    2.2. Columns with many nulls

    * Solution: I wasn't interested in those columns so I left them as they're

3. Change the incorrect datatypes into appropriate datatypes

</ul>

<hr>

### 3. Data Analysis and Visualization ###

<ul>

<u>
The questions I was interested to know are:
</u>

1. The percentage of movies and tv shows in this data

  <ul>
  
  ![image](https://user-images.githubusercontent.com/70551007/222007443-a711f14f-7d65-4149-97bf-0f33afc9ae99.png)

  > The dataset has 70.7% of its entries movies and the rest are tv shows.
  
  </ul>


2. The growth of content creations over the years

  <ul>
  
  ![image](https://user-images.githubusercontent.com/70551007/222007386-455595d6-92fa-4f07-bf9b-733f9f85434a.png)

  > The results shows that the year which has the highest number of content creations is 2018 which means that the data may be not complete.
  
  </ul>

3. Monitor content creations along the months
  <ul>
  
  ![image](https://user-images.githubusercontent.com/70551007/222007273-1352b673-4c90-4e8d-a07c-445333d3be0d.png)

  > December is the month when the highest number of content occurs.
  
  </ul>

4. The oldest 10 tv series and movies
  <ul>
  
  4.1. The oldest 10 tv shows
  
  ![image](https://user-images.githubusercontent.com/70551007/222007153-a06c604d-2f47-44e7-acbb-9c53a5869854.png)

  4.2. The oldest 10 movies
  
  ![image](https://user-images.githubusercontent.com/70551007/222007184-d4adfe53-377f-4444-bc8a-a70e44317a75.png)

  </ul>

5. The highest 10 countries contributed in contect creation
  <ul>
  
  ![image](https://user-images.githubusercontent.com/70551007/222006781-0a5e77a2-6564-41c1-9d86-eba8100c9341.png)
  
  > United States is the top 1 country contributed in both movies and tv shows
  
  </ul>
  
6. The most frequenct categories
  <ul>
  
  ![image](https://user-images.githubusercontent.com/70551007/222006721-3aaac1cc-3851-4a1a-b752-9ff7ce5ddd09.png)

  </ul>

7. Number of movies and tv shows by MPA rating for top 10 MPA ratings
  <ul>
  
  ![image](https://user-images.githubusercontent.com/70551007/222007002-48d47f5d-ce4d-457f-85d5-ccee0a769532.png)

  </ul>

</ul>

<hr>