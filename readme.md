# Class 14 
### View [all class list](https://github.com/poloey/feni)

# always use console when working with js. Since All error will be shown in console.

# Basic jquery function 
* show(timer) 
~~~js
$('p').show(2000)
~~~
* is(selector)
~~~js
$('p').is(':visible') // is function return true or false
~~~
* toggle(timer)
~~~js
$('p').toggle(2000)
~~~
* slideUp(timer)
~~~js
$('p').slideUp(2000)
~~~
* slideDown(timer)
~~~js
$('p').slideDown(2000)
~~~
* slideToggle(timer)
~~~js
$('p').slideToggle(2000)
~~~
* fadeIn(timer)
~~~js
$('p').fadeIn(2000)
~~~
* fadeOut(timer)
~~~js
$('p').fadeOut(2000)
~~~
* fadeToggle(timer)
~~~js
$('p').fadeToogle(2000)
~~~

# JavaScript Array function 
first make a array for demonstrating array function 
~~~js
var friends = [
  'sumon',
  'sarwar',
  'kayes',
  'tasnia',
  'tofaeel'
]
~~~
* to add value to end of the array - push(value)
~~~js
friends.push('tanim');
~~~

* to remove value from end of the array - pop()
~~~js
friends.pop();
~~~

* to add value to begining of the array - unshift(value)
~~~js
friends.unshift('mosarof');
~~~

* to remove value from the begining of the array - shift()
~~~js
friends.shift();
~~~


* to add, remove value from the middle of the array - splice(index, number of item want to delete, new value)
~~~js
friends.splice(3)
friends.splice(3, 1)
friends.splice(3, 0, 'new friend')
friends.splice(3, 1, 'new friend')
friends.splice(3, 0, 'new friend 1', 'new friend 1', 'new friend 2', 'new friend 3')
~~~

## Homework (since you will have about 5 days off, so it will be easier for you do following.)
* You have to complete a todo application with crud functionality as your home work (You may get help from [https://github.com/poloey/purejstodo](https://github.com/poloey/purejstodo) )    
Here I have added two todo edition. One is basic and another is advanced. Crud functionality present in advanced todo
* Please go through [w3Schools](http://w3schools.com) html, css, js, jquery


