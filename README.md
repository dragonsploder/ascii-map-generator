ascii map generator

![picture](AMG-medium-example.png) 

When you start the program, you will see:
	Small(1), Medium(2) or Large(3)

Small will create a 19x58 map

Medium will create a 37x118 map

Large will create a 49x209 map


The variables on lines 39-56 are:

shapes: the average sizes of the islands used (shapes1 or shapes2)
l: number of islands added to the map (these can overlap)
c: number of times the cutter function will run (curves sharp edges)
a: length
b: width

Note if you make a smaller then 10 and b smaller then 30, you may create an infinite loop

