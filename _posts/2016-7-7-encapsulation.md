---
layout: post
title: ENCAPSULATION
published: true
---

Encapsulation is hiding of data. This is where the inner workings of a class are hidden from the rest of the program.
This is achieved by limiting _accessors_ and _mutators_.

##Accessors
This are methods used to ask an object about itself.This is done by using the _get methid_.

##Mutators
Public methods used to modify an object while hidding the data modification process.This is done by using the _se method_
##getters and setters methods.
Getter method gets values of a variable and allows acopy of the field to be returned_(accessors)_.
A setter method sets values of a variable _(mutator)_.It validates input.

####getter and setter method in action:
~~java

private class Students
{
private int Totalnumber;
private int Studentsgrade;

public int getStudentsgrade{
 return Studentsgrade;

}
public int getTotalnumber{
return Totalnumber;
}
public void int setTotalnumber{
Totalnumer = 40;

}
public void int setStudentsgrade{

}
}

~~~