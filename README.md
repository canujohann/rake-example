Rake example
============


This code is based on [this site](http://jasonseifer.com/2010/04/06/rake-tutorial)

## How to use it ?

* Clone this repository
* Launch task(s)


```
#Call the "make_coffee" task of the "morning" namespace with a ENV variable
rake COFFEE_CUPS=5 morning:make_coffee

#call the "ready_for_the_day" in the "namespace"
rake morning:ready_for_the_day
```