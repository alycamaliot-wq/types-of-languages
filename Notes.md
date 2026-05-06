
As the computer knows only 0 n 1, it will be really difficult to write all of the apps n programs which is why we have programming
langs which helps us to translate our code into binary ( binary is the lang of comps 0 n 1 )
 
there are 3 types of languages:
proceddural, functional, object oriented


PROCEDURAL type of lang

its really spacific type of lang that requires really detailed info n steps to copmlate the task

Example 

closing the door function

first u need to know whether the door is closed or nor
if its not ( false ) then u need these following step

if u sit in a chair or sth u need to stay up
take the cordination of the door 
come to the door ( moving to left or right )
once ur close enought to grab the bar of the door 
ur hand will be up n u grab the bar of the door 
n based on the door u will whether push it out or in to close it 

n by doing these steps u will come back to ur original position ( first position before staying up ) 


functional type of lang 

its the type of lang that use functions much that contains a banch of code n line of code that makes one task which will give the 
possibility to use it anywhere at any time as much as possible n if the error happens only changing one function can correct all of
the code n etc that that funcion is being used 

rule n note: functions only calculates given tasks n it cant change anything outside of its place or box  

Example

car

car can be used to move on from a place to b regardless of the direction n place are being different, car can be used ( its like
a function u have one banch of codes that work as a group so u dont have to write the same thing over n over again ) n if the car is 
broken or working slow u can add changes or fix the broken part of the car


Object Oriented type of lang 

its code + data = it means creating the task using given data it shows problem solving stuffs n etc, 

Example 

lets say get a data of people: ali he is a student n from Atlantic 
what type of data is it? string ? boolen? integer? 
its cusmized data type

ali = string 
student = boolen: true 
worker = boolem: false 
Atlantic = String 

so we use these data to create a task for this person, like 

if the person is a student, allow him/her to work only 20 hours per week
if the person aint a student, allow him/her to work as long as they want 

if (this.isStudent == true) {
    allow "20 hours per week";
} else {
    allow "unlimited hours";
}

so basicly it means working w a banch of data ( names, paragraph, number, n etc )
n by using this data, u can make a task n give it to the spacefic type or data so when data comes rightly, it will do the task u said
to do



STATIC vs DYNAMIC languages

	// = = = = = > STATIC < = = = = = // 

 - works at compile time

 - Erros will be shown at the compile time 

 - Declate datatype before its been used

 - More controle

	// = = = = = > DYNAMIC language < = = = = = //

 - Performance type is being checked at runtime
 
 - Error might not be seen till program is run
 
 - No Need to declare datatype of variables

 - Saves time in writing code but might give error at run time 



	we have 2 types of memory: Stack n Heap 

 - a = 10 - - > Object  		
   | 
 ref variable 


 - so as our a is a ref variable it goes to the Stack memory n the object goes to Heap memory 

 - when the a does ( = ) it points to the object in Heap memory ( a point to the 10 w = while a is standing inside stack memory )
