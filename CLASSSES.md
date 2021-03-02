User
====

Attributes
----------
-username : String

-email : String

-hashedPassword : String

-details : UserDetails

-goals : Goals[]

-customFoods : FoodItem[]


Methods
-------
+setAccountInfo(String, String, String)

+setAge(int)

+setHeight(int)

+setWeight(int)

+setGender(boolean)

+setLastDrinkTime(int)

+getAge() : int

+getHeight() : int

+getWeight() : int

+getGender() : boolean

+getLastDrinkTime() : int

+getDailyCals() : int


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
+calcBMI(User) : int

+calcDailyCals(User) : int

+calcCalorieDelta(User) : int

+isThirsty(User) : boolean

+onTrack(User, Goal) : boolean


Goal
====

Attributes
----------
-desiredWeight : int

-currrentWeigth : int

-goalType : int

-caloricLimit : int


Methods
-------


FoodItem
========

Attributes
----------
-totalCals : int

-carbsMultiplier : double

-protiensMultiplier : double

-fatsMultiplier : double


Methods
-------
+setFoodDetails(int, double, double, double)

+getCalories() : int


Exercise
========

Attributes
----------
-calsBurned : int

-exerciseName : String

Methods
-------

