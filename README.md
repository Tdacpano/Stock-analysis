# Stock-analysis
Learning VBA through stock data 

# Overview of Project
  The purpose of this project was to assist Steve in helping his parents figure out which stocks would be best for them to begin investing their money into. The original goal was to compare the total daily volume of the DQ stock from 2017 & 2018 to other 12 stocks within the data. However, this challenge was to refactor the original code in order to compare the total daily volume to any stock in the stock market, not just the 12 we are limited to. In addition, we wanted to clean the code up and make it more efficient. We are able to test this by using the pop-up messages showing elapsed run time for the refactored code versus the original code.

# Results
The analysis is well described with screenshots and code (4 pt).
  After refactoring the code we were able to compare the total daily volume for any stock with the push of a button. However, in order to check whether the refactored code is more efficent than the original we will test out the run time for both. This test time will be used to compare the speeds for both the 2017 data and the 2018 data. 
  This image shows the speed of original code using the 2017 data. As it appears the code ran in 0.664 seconds for the 2017 data. 

<img width="532" alt="VBA_Challenge_Before2017" src="https://user-images.githubusercontent.com/117120227/204113490-c67177e7-c430-411d-bc54-378160d3141f.png">
 
  Now when comparing test speeds to the refactored code, the image shows that the new code runs more efficient. This code only took 0.121 seconds to run, which is quicker by 0.543 seconds. This is good to see because it is important for a code to run as efficient as possible in order to help reduce the resource consumption and completion time. 
  
<img width="488" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/117120227/204113492-0cf2de80-95ea-415c-907f-446da984bf94.png">
 
 Now the test must be run on the 2018 data to see if the refactored code works just as well with that data. As the image shows the original code ran in 0.679 seconds. Just about the same amount of time it took for the 2017 data.
 
<img width="488" alt="VBA_Challenge_Before2018" src="https://user-images.githubusercontent.com/117120227/204113507-139fef84-0600-4663-aa7a-1d3514e2c669.png">
  
  When comparing it to the following image the new code shows it is more quick and efficient. The refactor code now able to process the data in 0.125 seconds, which is 0.554 seconds quicker.
  
<img width="532" alt="VBA_Challenge_2018 VBA" src="https://user-images.githubusercontent.com/117120227/204113509-adf7ee77-67f0-48a4-9331-2b8efa9ad174.png">

# Summary
  In conclusion, refactoring the code proved to be a more efficient and effective method of processing data. By refactoring the code it allows for a better understanding of what is actually occurring. It also allows for the code to appear more clean, allowing any individual to go through the code now or even in the future, and still have ability to comprehend what is transpiring. One of the only disadvantage of refactoring code is the process of going through the original code and adjusting it in order to include more data than previously. 
  These pros and cons of applying a refactored code to the original script is that now the code will do everything the original did PLUS more! It not only runs for the 12 stocks in our data but now every stock in the stock market by the click of a button. It additionally, runs more efficient and quicker than the original. A possible con of applying refactoring to the original VBA script is that it took a few trial and error efforts in order for the code to fully work. Other than that the refactoring makes the original better structured so it is easier to understand along with the fact it runs more efficiently. 
