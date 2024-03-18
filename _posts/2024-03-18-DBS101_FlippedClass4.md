---
Title: DBS101 Flipped Class 4
categories: [DBS101, Flipped_Class4]
tags: [DBS101]
---

### Topic : Intermediate and Advanced SQL.

### Lesson learned from flipped class

As I learned more about SQL, I discovered some cool tricks for handling data in different ways. I found out about advanced functions that help calculate things like averages or counts, but in more advanced ways. Then, I came across window functions, which let me analyze specific groups of data without losing any details. Later on, I learned about ROLL UP and CUBE, which are like magic tricks for organizing data into summaries. Lastly, I explored Pivot, a handy tool that turns rows of data into columns, making it easier to spot patterns and trends. Each new thing I learned felt like unlocking a new tool in my data analysis toolbox, helping me see data in new and exciting ways. Here are my understanding on the topic:

#### Advance Aggregate Functions

Aggregate functions are special functions that operate on sets of values to summarize or calculate a single result. Instead of working with individual rows of data, aggregate functions process groups of rows and return a single value. Common aggregate functions include SUM(), AVG(), COUNT(), MIN(), and MAX(). These functions are used to perform operations like calculating totals, averages, counts and finding the minimum or maximum value within a dataset.

Now for further understanding I did some practicals based on a database I created which was about sale. Here I have used all functions at once to get the desired result.

![alt text](<../Screenshot from 2024-03-18 21-12-04.png>)

After implementing the functions the result I got is as follows;

![alt text](<../Screenshot from 2024-03-18 21-12-18.png>)

#### Window Aggregating

As I kept learning, I found out about window functions in SQL, which are quite different from regular aggregate functions. Window functions allow you to do calculations on a specific group of rows called a window. This gives you the power to perform calculations across rows while still keeping the details of each individual row. It's like having a window that lets you see just the rows you're interested in, while still being able to look at the whole dataset. Common types of window functions used are Rank, Dense_Rank and Row Number. These window functions give you more control and flexibility when analyzing your data, allowing you to perform complex calculations and gain deeper conclusions.

Here window functions is used to calculate the rank, dense rank, and row number for each row based on the quantity, ordering the rows in descending order of quantity.

![alt text](<../Screenshot from 2024-03-18 21-16-23.png>)

After using of window function the result look like this.

![alt text](<../Screenshot from 2024-03-18 21-16-33.png>)
#### ROLL UP and CUBE

Now I came across ROLL UP and CUBE operations in SQL, which were quite fascinating. These features allowed me to create different levels of subtotals and grand totals with ease, giving me hierarchical summaries of my data. With ROLL UP, I could generate subtotal rows for each level of grouping, helping me to see the data in different aggregated views. Meanwhile, CUBE took it a step further by creating all possible combinations of dimensions, giving me even more insight into the relationships within my dataset.

The SQL code performs ROLL UP and CUBE operations to generate hierarchical and multidimensional summaries of data, respectively, providing insights at different aggregation levels.

![alt text](<../Screenshot from 2024-03-18 21-17-03.png>)

![alt text](<../Screenshot from 2024-03-18 21-17-42.png>)

And their rescpective output:

![alt text](<../Screenshot from 2024-03-18 21-17-16.png>)

![alt text](<../Screenshot from 2024-03-18 21-17-51.png>)

#### Pivot

PIVOT enables us to see rows as columns in a query result. Pivot lets me transform data from rows into columns, making it easier to analyze and understand. This reshaping of data helps me to cross-tabulate and analyze data from different angles, uncovering valuable insights and trends.

Now here's an example of how the table will look like when PIVOT is used.

![alt text](<../Screenshot from 2024-03-18 21-20-29.png>)

#### Conclusion

In conclusion, exploring advanced SQL techniques has been a thrilling journey. I've learned a lot about manipulating data and gained valuable skills for analyzing complex datasets. Looking ahead, I'm excited to continue exploring SQL's vast potential for uncovering insights and solving real-world problems.

### What I did in flipped class


At first, we were instructed to read and study a topic provided by our tutor, along with accompanying notes uploaded on the VLE for flipped class instruction. Subsequently, during the class, assuming that we had read and studied the assigned topic, our tutor divided us into groups to discuss and share our thoughts.

Each group was given a couple of minutes for discussion, and when the time was over, our tutor randomly selected a presenter from each group to deliver a presentation on the discussed topic. Following this, our class concluded as usual, with effective learning occurring throughout the session.





