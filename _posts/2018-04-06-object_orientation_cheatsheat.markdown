---
layout: post
title:      "Object Orientation Cheatsheat"
date:       2018-04-06 15:28:24 +0000
permalink:  object_orientation_cheatsheat
---



Key Concepts
- Class: keyword class, followed by class name, ended with an end;
class Animal
     pet
end
- define: creating an object from the class using "new" keyboard; animal1 = Animal.new, animal2 = Animal.new
- initialize: takes list of parameters, useful when you're initializing a class variable;
 class Animal
      def initialize(s, a)
			     @size, @age = s, a
			end
end
- instance variable: class attributes, become properties of objects once objects are created using the class. share no value with other objects. accessed using @ operator
class Animal
   def initialize(s, a)
	    #assign isntance variables
	    @size, @age = s, a
   end
end
- accessor and setter method (getter method)
def petSize
   @size
end
def petAge
   @age
end

(setter method)
def petSize=(value)
@size = value
end

def petAge=(value)
@age = value
end

- instance method: can access instance variables
- class method and variable: class variable = variable shared between all instances of a class using @@. must be initialized within the class definition
- class method is defined using "def self.methodname(), which ends with end delimiter and be called using "classname.methodname
- to_s method: return a string representation of an object

string format of an object
@width, @height = w, h ------> (w:#@width,h:#@height)

- class inheritance: can make the new clsass inherit members of an existing class
- methods overriding: change behavior of an already defined method in a parent class
- clsas constant: define constant inside a class by assigning a direct numeric or string value to a variable, not using @ or @@. Cannot be changed unless you can access it directly inside a class, otherwise use classname::constant
- class information: self must reference something

Best Practices
 - The best practice is practice. The goal is to keep practicing until you can start coding in your sleep (more or less!) Try every type of problem, every which way. The more you're exposed to, the less you get stuck. 
