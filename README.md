<h1 style="text-align:center"><b>Coding Challenge - Consumer Prices Division, Data Science team</b></h1>

<p>The Consumer Prices Division (CPD) is undergoing a transition to utilize new data sources to enable better calculation of the Consumer Price Index (CPI). This involves interpreting unstructured text data sources, such as a product description provided by a retailer, to identifying where products fit in the CPI taxonomy. The Data Science team at CPD are responsible for developing supervised and unsupervised methods to do this, and is looking for qualified candidates to support this work.</p>


<h2><b>Question 1</h2></b>

<p>Go to the UCI page and download the data (click Download: Data Folder and download online_retail_II.xlsx). Use the file to answer the following questions using the 2009-2010 data:</p>
<b>Item sold most in whole database based on the amount of records they appear in whole dataset</b><br>

<b>Item sold most in whole database based on the amount of the quantity.</b><br>

<h2><b>Part B</h2></b>
<p>For 2009-2010, plot the number of total items sold per week in each of the top 5 selling countries (top as in sold the most total items over the 2009-2010 data period), excluding the United Kingdom. Show this as a single line plot with a line for each country.</p>

<p>Separately, plot the number of orders per week for the 5 countries (excluding United Kingdom) with the highest number of orders in the 2009-2010 data period.</p>
<h2><b>Part C</h2></b>
<p> If (price == unit price)</p>

<p>For 2009-2010, show a table (dataframe) of the average invoice value (over all of 2009-2010 data) by country, shown in ascending invoice value. Exclude any rows that have returns (quantities that are negative) from the averages shown.</p>

<p>Make the same table again but include only orders where the total number of items (eg: total quantity for the order) was 10 items or fewer.</p>

<b><h2>Part D</b></h2>
<p>What is the most common pair of items to appear in the same order? Ignore the quantity of each item when doing this analysis (so an order of [10xItem A, 5xItem B], would be the same as an order of [1xItem A, 1xItem B]).</p>

<h2><b>Part E</b></h2>
<p>Using a clustering algorithm of your choise, determine if there are distinct clusters of products based on their descriptions. For this question:<p>

<ul>
<li>focus on data in the country of Germany only;</li>
<li>conduct an analysis of the products to see how many clusters (if any) exist in products purchased in Germany;</li>
<li>visualize the resultant clusters (or lack their of);</li>
</ul>
<p>comment on the applicability of the clustering in general on the data, and the determined groups based on the average price distribution of each group;</p>

<b><p>NOTE: This question is not meant to be an exhaustive analysis of the data, but instead meant to test your ability of unsupervised Machine Learning methods. We recommend that you not spend more than ~2 hours on it.</b></p>

<h2><b>Question 2</b></h2>

<p>Given a list of integer intervals defined by (start, end), where start is inclusive and end is exclusive, write a function that returns the sum of the integers in the union of all the intervals. For example, given:</p>

<p>intervals = [
    (1, 5),
    (3, 7),
    (10, 12),
]</p>

<p>We can see that the union of all intervals would be [1, 7) + [10, 12), which results in a return value of 42 (1+2+3+4+5+6+10+11).</p>
