# Mongoose: managing relations

## Learning objectives

* use mongoose schemae and models; populate 
* discuss one-to-few, one-to-many, and one-to-squillions modeling choices, including pros and cons of each approach
* implement different relations via embedding or referencing, two-way referencing, and denormalization
* add relations to the data stores of our app (CRUD functionality)
- common mongoose queries
* agree on what the canonical blog posts mean by __application-level join__ or at least explain what it means in the context of related data

## Introduction

### SQL ways

In contrast to NoSQL, relational databases talk about many-to-many or one-to-many relationships. That's because traditional SQL is table-based, and certain data call for their relationships to be modeled in key ways. Mongo, being document based, has adapted those concepts into the sort of best practices for different ways slash scenarios of structuring data and relations in your data.

#### N-to-N

![A diagram showing a Many to Many database relationship](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/CPT-Databases-ManytoMany.svg/460px-CPT-Databases-ManytoMany.svg.png)
> One book can be written by many authors. One author can write many books.

> [Wikipedia: Many-to-many (data model)](https://en.wikipedia.org/w/index.php?title=Many-to-many_(data_model)&oldid=726249648)

###### Can you think of other data relationships that call for a many-to-many model?

#### One-to-one
![A diagram showing a One to One database relationship](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/CPT-Databases-OnetoOne.svg/500px-CPT-Databases-OnetoOne.svg.png)
> A country has only one capital city, and a capital city is the capital of only one country.

> [Wikipedia: One-to-one (data model)](https://en.wikipedia.org/wiki/One-to-one_(data_model))

#### N-to-one
![A diagram showing a One to One database relationship](https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/CPT-Databases-OnetoMany.svg/500px-CPT-Databases-OnetoMany.svg.png)
> A mother may have many children, but a child has only one mother.

> [Wikipedia: One-to-many (data model)](https://en.wikipedia.org/wiki/One-to-many_(data_model))

#### In practice (follow link to scary UML diagram)


### Important blog post series

#### Part one

* three basic schema designs
    - embedding
    - child-referencing
    - parent-referencing
  
##### What is meant by __application-level join?__

We think it has to do with calling on the relations between the different collections that make up our app. Consider the examples

## Step 1

* start with a fake example
* a scenario of many to many

## Step 2

* add something to our existing example


## Step 3

* prepare to build your own CRUD app!
