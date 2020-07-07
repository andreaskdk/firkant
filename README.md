# graph2table

The goal of this project is to make it easier to work with data that is stored or can be interpreted as a graph. By graph we mean the mathematical notion, which would probably be referred to as a network in everyday language.

More specifically this project provides a tool that allows data in the form of a graph to be mapped onto a table structure with rows and columns.

In 2009 Google Labs launched an experimental project called Google Squared, which had a very similar focus to this. The project was discontinued in 2012 and it is fairly difficult to find much information on how it worked.

## Lists

Let's start with lists

Consider the following series:

2, 4, 6, 8, ?

What is the next number in the series? Most people would answer 10 to this question, because the simplest explanation of the series would be incrementing by two from one step to the next. From a mathematical perspective it is, however, not trivial to formulate what we mean be "simplest explanation". There could be other explanations such as the last digit in the multiplication table for the number 12. In this case the next number in the series would be 0.

Consider another series:

2008, 2012, 2016, ? 

What is the next number in this series? It could be that the rule of the series is to add 4 in every step or it could be leapyears. In both of these cases the next number in the series would be 2020. However if the rule is years in which the Summer Olympics were held, then the next year would be 2021 due to the Corona virus postponement of the 2020 Olympics.

These examples have been concerned with numbers. 

Ronald Regan, George H. W. Bush, ?

The next element of this list could be Bill Clinton if the theme of the list is presidents of the USA, it could be George W. Bush if the theme is republican presidents or it could be Bob Dole if the theme is republican presidential candidates.

The examples so far have had a clear natural order. Consider for example:

Asia, Europe, South America, North America, Antarctica, Australia, ?

We could order the continents of the world alphabetically, by size or population, but the order is less significant fot this list. This is also an example of a closed set, because once we have added Africa to the list it is complete.

## From lists to tables



## A graph interpretation



## Architecture

The system will consist of three parts:

- **Database**: Data is comprised of a graph. Either it is stored in a graph database or in different data repositories in a way that can be interpreted as a graph.
- **Query Engine**: The middle layer responsible for exposing the data to the client in a convenient way.
- **Client Tool**: Browser based application that allows interaction with data.
