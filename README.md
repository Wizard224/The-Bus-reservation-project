                                                      # The-Bus-reservation-project
Write a program in c++ for the bus reservation project .
The bus reservatin project in c++ is basicly dependent upon one of the features object oriented programming that is inheritance .

                                                            ABOUT INHERITANCE 
       
The capability of a class to derive properties and characteristics from another class is called Inheritance. 
Inheritance is one of the most important feature of Object Oriented Programming.
Derived Class:
The class that inherits properties from another class is called Sub class or Derived Class.
Base Class:
The class whose properties are inherited by sub class is called Base Class or Super class.

                                                            ABOUT PROGRAMMING
    Header file used -
                      #include <conio.h>
                      #include <stdio.h>
                      #include <iostream>
                      #include <string.h>
                      #include <stdlib.h>
 
 Here the program starts basically from main () function where the user need to opt for one option diplayed in the menu.
 1.install
 2.reservation
 3.show
 4.bus available
 5.exit
 enter your choice -
 
 THIS ARE THE OPTION AVAILABLE IN THE MENU 
 
 Now at  the end of the porgram you will find a switch casee-
 cout<<"\n\t\t\tEnter your choice:-> ";
  cin>>w;
  switch(w)
  {
    case 1:  bus[p].install();
      break;
    case 2:  bus[p].allotment();
      break;
    case 3:  bus[0].show();
      break;
    case 4:  bus[0].avail();
      break;
    case 5:  exit(0);
    
    Here the function will be called according to the option taken by the user .
    
                                                            USE OF INHERITENCE IN THE PROGRAM 
  We have previously discussed about the  base and derived class 
  
  Here in the given program class a is used as a base class 
   
   on the other hand 
  void install();
  void allotment();
  void empty();
  void show();
  void avail();
  void position(int i);
  this are the derived class .
