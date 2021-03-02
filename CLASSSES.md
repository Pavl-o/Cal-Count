User
====

Attributes
----------
-username : String

-email : String

-hashedPassword : String

-goals : Goals[]

-details : UserDetails


Methods
-------
setAccountInfo(int username, int email, int password) : void

setAge(int num) : void

setHeight(int num) : void

setWeight(int num) : void

setGender(boolean bool) : void

setLastDrink(int num) : void

getAge() : int

getHeight() : int

getWeight() : int

getLastDrinkTime() : int

getGender(boolean bool) : boolean

get_dailyCals() : int

UserDetails
===========

Attributes
----------
-height : int

-weight : int 

-age : int

-gender : boolean

-lastDrinkTime : int

-dailyCalsConsumed : int


Methods
-------


Calculator
==========

Attributes
----------

Methods
-------
+calcBMI(User user) : int

+calcDailyCals(User user) : int

+calcCalorieDelta(User user) : int

+isThirsty(User user) : boolean

+onTrack(User user, Goal goal) : boolean


Goal
====

Attributes
----------
-desiredWeight
-currrentWeigth
-goalType
-caloricLimit


Methods
-------
-

FoodItem
========

Attributes
----------
-

