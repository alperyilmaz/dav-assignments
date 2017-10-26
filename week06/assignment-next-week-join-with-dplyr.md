# Joining Data in R with dplyr

# Chapter 1 Mutating joins

Mutating joins add new variables to one dataset from another dataset, matching observations across rows in the process. This chapter will explain the various ways you can join datasets together and what happens when you do.

## The advantages of dplyr

## Keys

## Primary keys

## Secondary keys

## Multi-variable keys

## Joins

## A basic join

## A second join

## A right join

## Variations on joins

## Inner joins and full joins

## Pipes

## Practice with pipes and joins

## Choose your joins

# Chapter 2 Filtering joins and set operations

Filtering joins and set operations combine information from datasets without adding new variables. Filtering joins filter the observations of one dataset based on whether or not they occur in a second dataset. Set operations use combinations of observations from both datasets to create a new dataset.

## Semi-joins

## Apply a semi-join

## Exploring with semi-joins

## A more precise way to filter?

## Anti-joins

## Apply an anti-join

## Apply another anti-join

## Which filtering join?

## Set operations

## How many songs are there?

## Greatest hits

## Live! Bootleg songs

## Multiple operations

## Unique values

## Comparing datasets

## Apply setequal

## Apply setequal again

## Comparing albums

# Chapter 3 Assembling data

This chapter will show you how to build datasets from basic elements: vectors, lists, and individual datasets that do not require a join. dplyr contains a set of functions for assembling data that work more intuitively than base R's functions. The chapter will also look at when dplyr does and does not use data type coercion.

## Binds

## Differences between dplyr and base R

## Which bind?

## Bind rows

## Bind columns

## Danger

## Build a better data frame

## data_frame

## Make a data frame

## Lists of columns

## Lists of rows (data frames)

## Working with data types

## Atomic data types

## dplyr's coercion rules

## dplyr and coercion

## Determining type

## Results

# Chapter 4 Advanced joining

Now that you have the basics, let's dive deep into the mechanics of joins. This chapter will show you how to spot common join problems, how to join based on multiple or mismatched keys, how to join multiple tables, and how to recreate dplyr's joins with SQL and base R.

## What can go wrong?

## Spot the key

## Non-unique keys

## Two non-unique keys

## Missing keys

## Defining the keys

## Which keys?

## A subset of keys

## Mis-matched key names

## More mismatched names

## Joining multiple tables

## Multiple joins

## Join multiple tables

## Filter multiple tables

## Other implementations

## SQL

## Base R

# Chapter 5 Case study

You know the ins and outs of two-table verbs with dplyr, but your knowledge is untried! Let's cement what you've learned with a real world application.

## Lahman's Baseball Database

## Universal keys?

## Common keys

## playerID

## Salaries

## Who are the players?

## Missing salaries

## Unpaid games?

## How many games?

## How many at-bats?

## Introducing the hall of fame

## Hall of fame nominations

## Hall of fame inductions

## Awards

## Salary

## Retirement
