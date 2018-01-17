#1 When this code is run in Node, e.g. node index.js, what are the two stages of execution for this file called, and which order do they happen in?

If I am not mistaken, Scott covered this in lecture and used the words compliation and execution. Where compilation runs through the code for readable syntax. Then executes the callbacks.


#2 Write an explanation, using as much space as you need, relating to how the first stage of execution for this file operates. 

first the variale foo is read and attatched a value 'bar'. No syntax error there so on to the next. 
A function 'bar' is being read as an anonymous function, an object method with a variable foo which equals 'baz'. This 'read first' process continues all the way down to line 13. From line 13 and on, if no critical errors have broken the code, the functions will then  begin to execute in orderly fashion.
