# Stock-analysis

## Overview of Project

Steve is analyzing a multiple stock to find out which one is the best to invest. He is interested in the total daily volume and yearly return for each stock.

For us, to comprehend better what Steve is measuring, the daily volume is the total number of shares traded throughout the day. The yearly return is the percentage difference in price from the beginning of the year to the end of the year.

At first we focused in Daqo, the stock that Steve’s parents were interested in.

Then we do the complete analysis to the rest of the stocks, a total of twelve stocks, and data from 2017 and 2018, so we have the big panorama and Steve can choose a better option.

Finally, when we had all the information we are going to refactor our code to make it simple, easier and faster.


## Results

### Daqo results:

Using the next code, we get the return value for Daqo, it dropped over 63% in 2018, so it was not the best option for Steve.

![image](https://user-images.githubusercontent.com/90534703/135390916-7faf06ff-d4f6-427e-97b5-4c3f52a6b60e.png)


Then, for the analysis of the multiple stocks, we used part of the Daqo code, adding more code so we can analyze more information. And we got the results that Steve wants of the behavior of twelve stocks in 2017 and 2018.


![image](https://user-images.githubusercontent.com/90534703/135390962-51eb9d2e-c46f-409f-b862-e1acf92c96d7.png)
![image](https://user-images.githubusercontent.com/90534703/135390976-fdcda8a8-093c-429b-9afc-64ecaac6234b.png)


As we can see in the results, 2017 was a year in which almost every stock had a positive return value, compared with 2018 that only ENPH and RUN, were the only two stocks that kept having a positive return value. You should keep an eye on ENPH and RUN. 

![image](https://user-images.githubusercontent.com/90534703/135390997-0046be21-fee9-436a-bd3f-0996628b4219.png)

![image](https://user-images.githubusercontent.com/90534703/135391019-03799991-b327-4e24-bd3e-7fe76ca6c24b.png)

![image](https://user-images.githubusercontent.com/90534703/135391032-9e261603-2347-45a0-bbfc-bbb8123f576d.png)


Now, for the refactor code, we proceed to “clean” or edit the code, so it can give us the information in a faster time. What we did is that our code only loop through our data one time

Here you can see the code that we edit, so the loop only goes one time throught all the data, instead of the code that we used before.
![image](https://user-images.githubusercontent.com/90534703/135391058-0847ac5c-a70f-4a2e-8f2f-63652cce6838.png)



### The results about the time were the next ones.
##### Original Code.
![image](https://user-images.githubusercontent.com/90534703/135391104-4ce46c3c-f927-4450-99ea-7a1098426237.png)

![image](https://user-images.githubusercontent.com/90534703/135391121-f1ec28bd-e321-4757-b2bf-c48fc9ec72f5.png)

##### Refactor Code.
![image](https://user-images.githubusercontent.com/90534703/135391160-3ef8458c-dc4f-4d71-9058-edb3be484197.png)

![image](https://user-images.githubusercontent.com/90534703/135391172-a74a80e6-65f6-491f-9a14-1afe1934647e.png)

As we can see refactoring the code gave us a faster way to get the results, there was a significant reduction on the time on which our code run for each year.

## Summary

### - What are the advantages or disadvantages of refactoring code?

As I mentioned before refactoring the code have the advantage of reduce the time of code running, as we can appreciate on previous images.

Now, with the refactoring our code is more efficient, as we improved the logic of our code, making the loop only run one time.

A disadvantage could be that when we refactor our code we wouldn’t get the result that we want, and that the code gets damaged.

### - How do these pros and cons apply to refactoring the original VBA script?

The pro that we can apply in our exercise is that the macro run time was reduced.

It went from 1.11 seconds to 0.36 seconds for 2017, and from 1.14 seconds to 0.30 seconds for 2018.

And the cons, was that in certain point my refactoring was not working properly, but at the end it worked.






