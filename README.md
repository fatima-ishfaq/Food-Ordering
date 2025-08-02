# Food-Ordering
This is a simple beginner friendly  C++ code for Online Food Ordering.

Author: Fatima Ishfaq

**Project Description:**

Simple Food Order system is based on a concept of ordering food items and generating total food cost. There’s no login system in this mini project. Then the user can make an order by selecting from the main menu. This mini project contains limited features, but the essential one.
Talking about the features of the simple food order system, the user has to select any of the items from the main menu. Then he/she has to select its types and then enter food quantity. After this, the system displays the total bill of the customer. 

**Functional Requirements:**

Our project “Simple Food Order system” is the concept how we place any food order from our homes and other places. So the restaurant’s name is HER’s CAFE consists of three classes MENU, Food_Cafe and BILL which are inherited with each other in away that both MENU and Food_Cafe classes are inherited to BILL class in other words BILL class has two parents.
In first class MENU there are two functions Greetings( ) and menu( ) which shows greeting and  menu to the customer. 
Second class Food_Cafe is the class where the main working of our project takes place. It consist of choose( ) function which enable the user to chooses the dish he/she wants to buy then choose it flavor then select quantity and in the last according to the price of the dish and its quantity bill is generated.
Third class BILL is derived from both MENU and Food_Cafe so here multiple inheritance takes place. It consists of two functions anything_else( ) and checkout( ), where anything_else function enables the user to decide whether he/she wants to order anything else or not if yes, than the program starts from the menu and if no the control moves to the next function checkout were the final order message appears containing the customer and order information.
In the main( ) each function is called using the child class object. In this way this program executes.

**Incorporation of OOP in our project:**

Classes and objects, Access specifies (private, public and protected), encapsulation, Inheritance (Multiple) are used in our project.
