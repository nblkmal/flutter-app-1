# Flutter Training
## Day 1

1. Install flutter and package
2. Flutter Overview : Widget Tree - structure of widgets in apps
	- text widget
	- button widget
	- row widget
	- etc
3. Dart Basic Primer
	- use variable
	- OOP Structure
	- static type programming language, cannot change value type
	- there is 'dynamic' type, can change dynamically but not suggested
	- void function will not return anything, but can return value from function
	- List is the same as JS Array
	- not a good practice to mix data type in one List array
	- define type at List<String> so that only that type can be use
	- Class usage, contain object, instance of the Class
	- Class can have constructor to receive any parameter
	- use String? name; to define a null data
	- class SuperUser extends User to inherit the User class
4. Create a Flutter App
	- create virtual machine
	- create project
	- run project demo
	- use Material App form Google Material
5. Scaffold & AppBar widget
	- Scaffold (home)
		- AppBar
		- body
6. Add property, colors & fonts
	- backgroundColor
	- style
	- custom font > create new folder 'fonts'
	- add .ttf font file into 'fonts'
	- edit pubspec.yaml file to update fonts
7. Stateless widget & hot reload
	- stateless = cannot change over time
	- stateful = can change over time
	- import all widget tree into one stateless widget to use it over time
8. 