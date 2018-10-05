ascii map generator

![picture](/AMG-medium-example.PNG) 

When you start the program, you will see:
	Small(1), Medium(2) or Large(3)

Small will create a 19x58 map

Medium will create a 37x118 map

Large will create a 49x209 map


The variables are:

	shapes: the average sizes of the islands used (shapes0 - 5)

	l: number of islands added to the map (these can overlap)

	c: number of times the cutter function will run (curves sharp edges)

	a: length

	b: width

	p: place "stuff" (T or F)

Note if you make (a) smaller then min-shapesY and (b) smaller then min-shapesX, you may create an infinite loop

