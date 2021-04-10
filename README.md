# README For Task

1. After anylizing the data. We can see that there are few null values in the datasets. 'Brand' columns has most.

2. First of all i thought quite difficult approach that using all columns. So i changed date-time stamp into different columns.

3. But after sometime i got to know that i can take despription as input and category as output and this problem will become like kind of twitter sentiment analysis.

4. So Now, i have to find out which category i should chosse for my classifcation.

5. I visualize the datasets using seaborn. And check frequnecy of each category in 'product_category_tree' with maximum 4 level deep. So that i can check is there any too much difference in these frequency.

6. After evaluting the data. I came to know that i can take top 6 category of first level for my pridiction. Because after its frequency goes down like around 200+ something.

7. After that, cleaning the description column using 'preprocess_string' function.

8. For classification I used multinomial classification model because i have to classify into more than 2 category and the multinomial logistic regression was specifically designed for the nominal data.

9. Firstly I have used CNN for this but couldn't get much accuracy.

10. Then i think may Term frequency-inverse document frequency may help. so i have used that also. But it seems there is not such big diffenece. And I got accuracy 0.9914285714285714 on test datasets.