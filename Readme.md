# Bike Sales Dashboard

## Project description
I used [bike sales data](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx) to create this project in **Excel.** After cleaning the data, I built several interactive charts showing the number of customers who purchased a bike vs those who didn't, based on their gender, income, age and commute distance. Additionally, the filters on the right-hand side allow drilling down the data even further by marital status, education, region and more.

## The process

I started by exploring the data, followed by some **cleaning** and **categorizing**. Here are some of the main steps that I took:

- Removed duplicates.
- Tidied up the *Marital Status* and *Gender* columns (made the values more descriptive instead of being just one-letter values).
- Formated the *Income* column to exclude decimal places.
- Added a new *Age Brackets* column using **nested IF functions**.

Next, I created several **pivot tables** that I later used in my **Dashboard**. These provide answers such as:

- What is the average income of people who purchased bikes vs those who didn't, for each gender separately?
- How does commute distance impact bike purchases?
- What age group buys bikes the most, and how does this differ for customers who end up not making a purchase?

To make this dashboard **interactive**, I added **slicers**, which allow exploring the data further by level of education, occupation, marital status, number of cars owned, etc.

## Inspiration
I built this project by following (and further modifying) [this tutorial](https://youtu.be/opJgMj1IUrc) from [Alex The Analyst](https://www.youtube.com/channel/UC7cs8q-gJRlGwj4A8OmCmXg).