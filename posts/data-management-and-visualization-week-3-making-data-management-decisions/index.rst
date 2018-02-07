.. title: Data Management and Visualization - week 3: Making Data Management Decisions
.. slug: data-management-and-visualization-week-3-making-data-management-decisions
.. date: 2018-02-07 16:41:53 UTC+11:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text


Here is my conclusion. More details are in my `jupyter notebook <https://github.com/jeremy886/learn_datascience/blob/master/australia/week3_assignment.ipynb>`_.


Replacing missing values should make the data analysis more accurate and show a real picture.

Here are the missing data:

    negative income -1 in the “income_low” column
    unknown income -99 in the “income_low” column
    unknown income -99 in the “income_high” column
    unknown income 9999 in the “income_high” column All are changed to nump.nan

When using qcut to explore the distribution of population, it’s discovered that the majority of population is fewer or equal to 3, accounting for nearly 50%. The reason is that Victoria has a relatively smaller population so the population per post code per income bracket is small. That can have an impact on analysis based on post code.

I also created secondary variables and discover some meaningful facts:

    “income” is created by averaging the lower and higher ends of the income brackets.
    “total_income” is created by timing “income” and “number” together. We made an assumption that the average income is the average of the lower and higher ends.
    Using the secondary variables, we can quickly tell the average weekly income ratio is, Female : Male = 591.53 : 773.68

To further explore the influence of post code (location), I extract top and bottom 10 income post codes. Since it’s difficult to use the post code alone, I try to map the code to suburb names. In the process, I realise the mapping is not perfect but I try it anyway because it is far more easier to interpreter the data by name.

The analysis is not yet complete and I hope some data visualization techniques can help me discover more interesting areas I can use for further investigation next week.
