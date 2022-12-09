# Amazon_Vine_Analysis
Amazon product review analysis
Please note that I was able to extract customers_table onto PgAdmin but the rest of the data were taking too long to extract. So I just donwloaded the ipynb without running the extractions of the remaining tables. Please do understand my inconvenince. Thank you
##Overview
Determine if there is any bias toward favorable reviews from Vine members in the Amazon Ebook review dataset.
##Results
There are total of 32 vine reviews and 12520673 non-vine reviews
Among the 5 star reviews, there are 0 vine reviews and 20918 non-vine reviews
From the analysis, there is 0% vine reviews from all the 5 star reviews. On the other hand, 100% of the 5-star reviews are non-vine reviews.
##Summary
Based on these, there is significant difference in 5 star review whether they are vine or non-vine reviews. An addiitonal analysis could be plot the boxplot as well as scatter-plot to understand if other reviews (less than 5 star) has also some indication of vine review effect as the alternative hypothesis. 

![Image1.png](https://github.com/chris820629/Amazon_Vine_Analysis/blob/main/Image1.png)
![Image2.png](https://github.com/chris820629/Amazon_Vine_Analysis/blob/main/Image2.png)
![Image3.png](https://github.com/chris820629/Amazon_Vine_Analysis/blob/main/Image3.png)
![Image4.png](https://github.com/chris820629/Amazon_Vine_Analysis/blob/main/Image4.png)
![Image5.png](https://github.com/chris820629/Amazon_Vine_Analysis/blob/main/Image5.png)