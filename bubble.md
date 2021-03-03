
#Bubble Sort

Given array = [15, 10, 5, 20, 30, 25]

* Iteration 1
    * step 1: starting from the left, compare the first 2 adjacent numbers (in this case [15 $ 10]) 
    * step 2: if **15 > 10**, swap position to have greater number towards the right-result: [10 $ 15]
    * step 3: else let them retain same position.
    * step 4: repeat same process for every other pair of adjacent number till iteration 1 is completed. 
              [**15**, **10**, 5, 20, 30, 25] => [10, **15**, **5**, 20, 30, 25] => [10, 5, **15**, **20**, 30, 25] =>  [10, 5, 15, **20**, **30**, 25] => [10, 5, 15, 20, **30**, **25**] => [10, 5, 15, 20, 25, 30] end of iteration1.

* Iteration 2 
    * step 5: starting with the last outcome of iteration 1, repeat step 1 to 4. See final outcome below.
              [**10**, **5**, 15, 20, 25, 30] => [5, 10, 15, 20, 25, 30]

		

