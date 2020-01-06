---
layout: post
title:      "Learning about Initialize"
date:       2020-01-06 01:36:51 +0000
permalink:  learning_about_initialize
---


Through learning through object lifestyles was dealing initalization, In Ruby a can produce new instances of itselfs with or without initialize but if we want each instance of our class to be created with different attributes we will define initialize. The Initialize method is a method that is called automatically whenever new is being used. Kind of like how a factory that produces new cars, car colors, cars parts and etc. For Example

```
class Car

  def initialize(color)
   @color = color
 end
 
  def color = (color)
    @color = color
  end
	
	 def color
	   @color
	end
	
	end
	
	We can call new like this
	
	Honda = Car.new("Red")
	Honda.Car
```
