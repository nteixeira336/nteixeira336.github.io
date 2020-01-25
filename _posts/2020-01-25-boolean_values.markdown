---
layout: post
title:      "Boolean Values "
date:       2020-01-25 22:07:23 +0000
permalink:  boolean_values
---

Boolean is a data type which means true or false. They can help us relate other data types like intergers and strings in a true or false context. When Ruby was created, it was determined what values are true or "truthy" and what values are false or "falsey." This was quite confusing for me at first because outside of programming, we think there is only one kind of true and one kind of false. But I quickly learned a new way of thinking about true and false as I learned Ruby. 

**True or "truthy"**  
There is the literal true and then there is truthy. The literal true is when you actually see the word `true` written out. When a statement evaluates to true, we call that `truthy`. 

**False or "falsey**
The same can be said for false. Only the written word `false` is the literal false, and all expressions that evaluate to false are called `falsey`. Most things are truthy, only `false` and `nil` evaluate to false. Nil is quite different from 0 because 0 is a real value which means there are none of something. Nil is the absence of a something at all, so there can't be 0 of something that doesn't exist. This is why 0 is truthy and nil is false.

**Boolean Operators**
There are several operators we use to evaluate boolean expressions such as:

* `==` Equality comparison- This operator compares two values on either side, and if they are exactly equal the statement will return true, if they are not it will return false. We cannot use one `=` because that is how we assign variables. 

`1==1`   true 
`1==3`   false 
`read==bread` false 
`cat==cat ` true 
`dog==Dog`  false 

* `!=` Inequality operator- This operator is the opposite of the equality comparison. It compares each side and if they are NOT equal, we will have a return value of true. If they ARE equal, we will have a return value of false. 

 `1 != 1` false 
 `1 != 3` true 
` read != bread` true 

* `&&` And - For this operator to evaluate true, both values must evaluate to true. 

`true && true`  true 
`true && false` false 

You might be wondering what this looks like when used in code? We use booleans a lot in "if-then" situations. Here is an example: 

IF my homework is done AND the weather is nice THEN I will go to the beach. 

```
homework_is_done=true
weather_is_nice=true

homework_is_done && weather_is_nice ?  "go to the beach" : "study" 
```

This will return "go to the beach" because both sides of the `&&` are true in this case. We read this as "Homework is done and weather is nice? If true, go to the beach, if false, study." If either side is false, that would result in "study." 

* ` ||` Or- For "or" to evaluate to true, only one side has to be true. 

`false || true`   true 





