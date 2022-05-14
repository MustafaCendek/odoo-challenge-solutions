# Test - 5  
[Back to home](../readme.md)  
## We look at the cookies, paying attention to the cookie picture that is the clue, and there we find the password.  
![Cookies](./img/test5-01.png)  
## In addition, when the files included in the header are examined, there is a script called challenge.js. When we examine the content by clicking Reveal in Source Panel, we encounter a minified code.  
![Reveal in Source Panel](./img/test5-02.png)   
![Minified script](./img/test5-03.png)  
## Browsers have very advanced and useful features. So we don't need to worry about minified code.  
## If you are a Google Chrome user, find the { } button at the bottom left.  
![Formatter button](./img/test5-04.png)  
## It's a formatter button and can make the code more readable.  
![Pretty code](./img/test5-05.png)  
## Now the code is much more readable. There is a function called getBiscuit here. This script returns the value of a field in the cookie. We can copy the password directly from the place in the first picture, but if we run the code getBiscuit("passwd") on the console, it will also give us the password.  
![GetBiscuit function](./img/test5-06.png)  
[Back to home](../readme.md)
