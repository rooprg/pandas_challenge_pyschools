# pandas-challenge
Module 4 Challenge
Below is the help I received with certain aspects of this assignment.

Citations:

(1)   Aggregating statistics grouped by category. (2024). Retrieved from https://pandas.pydata.org/docs/dev/getting_started/intro_tutorials/06_calculate_statistics.html/
(2)   Oyama, F. (2023, January 25). How to Use the Pandas DataFrame Groupby Method. Retrieved from https://www.theoceancleanup.com/updates/whales-likely-impacted-by-great-pacific-garbage-patch/
(3)   Xpert Learning Assistance. (2024, April 23). . [Response to user question]. Retrieved from [URL of the platform where the conversation took place].

        When encountering an unknown error type during my work on Module Challenge 4, namely "FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass 
        observed=False to retain current behavior or observed=True to adopt the future default and silence this warning...", Xpert Learning Assistant provided the following advice with led to a change in my code (since we 
        did not see a similar error during classes or exercises):
        
        "The warning message you are seeing is a FutureWarning indicating a change in behavior that will occur in a future version of pandas. To address this warning and ensure your code runs without issues in the future   
         versions of pandas, you can explicitly set observed=True in the groupby operation.

         You can modify your code as follows to address the warning:

         spending_math_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"], observed=True)["Average Math Score"].mean()

         By explicitly setting observed=True, you will adopt the future default behavior and silence the warning. This adjustment will ensure that your code continues to work as expected in future versions of pandas."
