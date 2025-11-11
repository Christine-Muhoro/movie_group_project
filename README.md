# **Movie Production Analysis**

## **Overview**
This project analyzes trends in various movie datasets to form meaningful insights that shed light on a film's success in the film industry and thus inform the company on the most influential factors in the film-making industry.

## **Business Understanding**
The company's head of the movie studio requires meaningful insights from the data analysis in order to take important factors into consideration to ensure a sustainable profit in the newly dived in film-making business.The core questions to be answered are:

1. The genres which have the best returns from investments.

2. The effect of movie ratings and how they affect the gross from a film.

3. The range of the production budgets used in film-making and the expected returns scaled across a certain time frame.

4. The variations of film response from audiences in relation to release dates and months.

These questions form the base on how the project objectives are tackled.

## **Data Understanding and Analysis**

### **Source of data**
The datasets utilized in this project are *Box Office Mojo*, *IMDB* and *The Numbers* with information from the 19th century to the current date.

### **Data Description**
The utilized columns in the *Box Office Mojo* dataset are title, studio, domestic_gross, foreign_gross and year.
The data cleaning process included dropping null values from the Studio and Domestic_gross columns and filling of the missing values in the Foreign_gross column in relation to the median.

The utilized columns in the *IMDB* dataset are movie_id,   primary_title, original_title, start_year, runtime_minutes, genres, averagerating and numvotes which are a result of combining the movie_basics and movie_ratings tables.
The data cleaning process resulted in the dropping of null values in the genres column and the null values in the runtime_minutes were filled in relation to the median.

The utilized columns in the *The Numbers* dataset are release_date, movie, production_budget, domestic_gross and worldwide_gross.
This dataset required no cleaning.


### **Data Visualizations**

#### **Genre Rankings**

![image_one](./Images/img-1.png)


#### **Production Budget and Gross Trends over Time**

![image_three](./Images/img-3.png)


#### **Average Profit Across Differentv Months**

![image_five](./Images/img-5.png)



## **Conclusion**
1. According to our rank, the best performing genre in the film industry is Animation, followed by Adventure and Sport. Thriller, Horror and Romance are the least rewarding genres to invest in. Therefore, we recommend that Urban Productions invests more in Animation, Adventure and Sport genres.

2. As studios spend more on movies' production budget, the gross earned increases too. It is recommendable to allocate high budgets for films since viewers reward the spending, which ensures return of profits.

3. Movies do best within the May to July period. On the other hand, January, September and October are the least performing months in the film industry. It is hence ideal to have movie releases during the May to July period.


Overall, the project provided valuable insights into the factors influencing movie success in the film industry. By analyzing genres, production budgets, and release periods, we identified trends that affect a film’s performance. The findings show that a movie's success is determined by genre selection, sufficient budgeting and strategic release timing. Therefore, this analysis guides Urban Productions in making informed decisions in venturing into the film industry.
