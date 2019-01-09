Fire Module using Bspline
	This is module which is based on graphics which draw a fire shape object using bspline in opengl.
 
Prerequisites
	Install openGl 
	Install gcc compiler 
	
Installing
	1)openGl
	$ sudo apt-get install gcc -y
	$ sudo apt-cache search free-glut
	$ sudo apt-get install freeglut3-dev
	
	2)gcc compiler
	$ sudo apt-get install gcc
	
Configuration
	Os 	: Debian/Ubuntu
	Os type : 64 bit
	Ram	: 4 GB
	
How to run
	gcc bspline.c -o obj -lglut -lGLU -lGL -lm
	./obj
