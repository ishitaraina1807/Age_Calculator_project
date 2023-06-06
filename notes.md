HTML : 
the structure 

CSS: 
the design 
(toggle for dark mode can be apllied - later)
color changes on error 

JS: 
--> if no value is put - throws error with error message. 
-> year should be between 1900 - 2023
-> for months (1,3,5,7,8,10,12) : 1<days<31
-> for months (4,6,9,11) : 1<days<30
-> for month (2) : 1<days<28 
-> for year%4 == 0 : month (2) : 1<days<29
-->if these are not satisfied then error is thrown with different error message. 

--> Calculating age:
let's say : 18 07 2002 
something that uses current date (05 - 06 - 2023)
it's like if the birthday is done this year: current year - birth year 
                                           : 