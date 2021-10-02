# Date Converter: BS <=> AD
Simple date converter. Made for using in the project [Electricity-Demand-Prediction](https://github.com/Ishan5hrestha/Electricity-Demand-Prediction).
Has list of number of days in all the months from 2000 BS to 2090 BS  
# Working
You can see in adtobs() function:  
```
gate = [2073,1,1,4]
tarik = [2016,4,13,4]
```
Variable gate gives date in BS and tarik gives the same date in AD. The 4 at the end denotes Wednesday.  
The AD date substracted from **tarik** date to find out the difference in number of days.  
This number is added to **gate** date to get the required date.
# Output
The output looks like this:
```
adtobs(2016,4,13): 2073,1,1,4
adtobs(2021,10,2): 2078,06,16,7
```
