# R Data Analysis Cookbook - Second Edition
This is the code repository for [R Data Analysis Cookbook - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/r-data-analysis-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787124479), published by [Packt Publishing](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book will show you how you can put your data analysis skills in R to practical use, with recipes catering to the basic as well as advanced data analysis tasks. Right from acquiring your data and preparing it for analysis to the more complex data analysis techniques, the book will show you how you can implement each technique in the best possible manner. You will also visualize your data using the popular R packages like ggplot2 and gain hidden insights from it. Starting with implementing the basic data analysis concepts like handling your data to creating basic plots, you will master the more advanced data analysis techniques like performing cluster analysis, and generating effective analysis reports and visualizations. Throughout the book, you will get to know the common problems and obstacles you might encounter while implementing each of the data analysis techniques in R, with ways to overcoming them in the easiest possible way.

By the end of this book, you will have all the knowledge you need to become an expert in data analysis with R, and put your skills to test in real-world scenarios.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
> names(movieTitleDF) <- c("MovieID", "Title", "ReleaseDate",
"VideoReleaseDate", "IMDB", "Unknown", "Action", "Adventure",
"Animation", "Childrens", "Comedy", "Crime", "Documentary",
"Drama", "Fantasy", "FilmNoir", "Horror", "Musical", "Mystery",
"Romance", "SciFi", "Thriller", "War", "Western")
> movieTitleDF$ReleaseDate <- NULL;
> movieTitleDF$VideoReleaseDate <- NULL
> movieTitleDF$IMDB <- NULL
> movieTitleDF <- unique(movieTitleDF)
> names(userDF) <- c("UserID", "ItemID", "Rating")
> userDF <- userDF[,1:3]
```

The steps should be listed in a way that it prepares the system environment to be able to
test the codes of the book:
Software R base
Software MS Office
Software Apache Java (JDK)
Software MySQL
Software MongoDB
Although all the code should run on R base command line, I would suggest you run the
code of the book from R Studio instead of R command line, as it is an IDE and easy to use.
Also, few chapters specifically require the use of R Studio only.

## Related Products
* [Data Manipulation with R - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/data-manipulation-r-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785288814)

* [Practical Data Analysis - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/practical-data-analysis-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785289712)

* [R Data Analysis Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/r-data-analysis-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781783989065)

