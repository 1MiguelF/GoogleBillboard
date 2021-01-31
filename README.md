Google Billboard
==================
In July of 2004 a mysterious billboard appeared in Silicon Valley. All it said was  

     {first ten digit prime found in consecutive digits of e}.com  (this website is no longer available :( )

At the same time, an identical banner appeared in the Harvard Square subway station in Boston. No indication was given about the significance of the signs, but people who correctly discovered the ten digit prime and visited the website were given a subsequent puzzle. If they completed that problem correctly they received a congratulatory message encouraging them to apply for a job at Google Labs!  This promotion is no longer active.

Suggested steps to complete the assignment
------------------------------------------
1. Go to [https://codingbat.com/prob/p221207](https://codingbat.com/prob/p221207), log in, and do the isPrime problem
2. You may find the first ~50 slides of the [Unit_2_String_Objects_Methods](https://docs.google.com/presentation/d/1H9tzGeTWetjzUz1G450NGxbEO5xZl3BvacfkFWsvWRE/edit#slide=id.p1) slide presentation helpful
3. Now you are ready to start the project. Fork and clone down this repository
3. In `setup()` use the two argument version of `substring()` to pull out ten consecutive digits of e at a time. Convert them to `double`s with `Double.parseDouble()`. Here's an example:  
     `String digits = e.substring(2,12);`   
     `double dNum = Double.parseDouble(digits);`   
     `System.out.println(dNum);  //displays 7.182818284E9`  
Note that by default, Java displays doubles in exponential form. `7.182818284E9` is 7.182818284 x 10^9.
5. Finish the codingbat `isPrime()`  to test if a number is prime.
6. Add a loop to `setup()` that moves through the digits of e until it finds the first 10 digit prime.
7. Add commit and upload your finished program to your github account. 
9. OPTIONAL: If you have extra time you may want to see if you can solve the second puzzle. 
