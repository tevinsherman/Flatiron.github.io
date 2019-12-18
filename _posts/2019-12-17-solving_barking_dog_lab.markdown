---
layout: post
title:      "Solving Barking Dog Lab"
date:       2019-12-18 00:45:53 +0000
permalink:  solving_barking_dog_lab
---


In this lab is the introducing of working with class and build instance methods with setters and getters. We are going to need to create a Dog class with a name and a bark. Look at this as like building a "build-a-bear workshop" but instead build-a-doggy workshop. 

So we create:

``class Dog
  def name
    @name
  end

  def name=(dog_name)
    @name = dog_name
  end

  def bark
    puts "woof!"
  end
> end``

This here we can call on the instance of Dog for example

Macho = Dog.new

Macho.name = "Macho"

Macho.name
"Macho"

Macho.bark
"woof!"

