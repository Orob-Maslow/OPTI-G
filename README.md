# OPTI-G
This is an optimization program for G-code, and this is done by reorder the cuts, to minimize the distance between them.
Use it entirely at your own risk! It can still contain bugs!

## The program:
![GUI](https://raw.githubusercontent.com/runeSal/OPTI-G/master/Images/GUI%20v.0.4.1.PNG)

This optimizer is intended for use with 'pcbgcode' which has etch and drill files, but there is no different between how the software handle Etch and Drill files, and other G-code files can also be optimized by this program.

## The optimization:
The optimization support where the cut enter and stop at different places, and cuts there enter and exit the same place. Do NOT support G-code, where the order of the cuts between tool change are important, and need to be performed in sequence.
If you are interested in the algorithm used to optimize the G-code more information can be found at this
[link](http://hackaday.io/project/4955-g-code-optimizing).

![](https://raw.githubusercontent.com/runeSal/OPTI-G/master/Images/random%20cities%20before%20after%20OPTI-G.PNG)

## Installation:
1. Download the project and unpack it. 
2. Now there are two options
	* Move the 'Program' folder to location you want, and run the program from here. Make sure you have .NET 4.5 to run the program.
	* Or run the setup.exe file in the 'Installation files' folder.

## Images
![Before after OPTI-G](https://raw.githubusercontent.com/runeSal/OPTI-G/master/Images/pcb%20before%20after%20OPTI-G.png)
