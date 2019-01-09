<h3>Fire Module using Bspline<br></h3>
	This is module which is based on graphics which draw a fire shape object using bspline in opengl.
 
<h5>Prerequisites</h5>
	&nbsp;&nbsp;&nbsp;&nbsp;Install openGl <br>
	&nbsp;&nbsp;&nbsp;&nbsp;Install gcc compiler <br>
	
<h5>Installing</h5>
	1)openGl<br>
	&nbsp;&nbsp;&nbsp;&nbsp;$ sudo apt-get install gcc -y<br>
	&nbsp;&nbsp;&nbsp;&nbsp;$ sudo apt-cache search free-glut<br>		
	&nbsp;&nbsp;&nbsp;&nbsp;$ sudo apt-get install freeglut3-dev<br><br>
	2)gcc compiler<br>
	&nbsp;&nbsp;&nbsp;&nbsp;$ sudo apt-get install gcc<br>
	
<h5>Configuration</h5>
	&nbsp;&nbsp;&nbsp;&nbsp;Os 	: Debian/Ubuntu<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Os type : 64 bit<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Ram	: 4 GB<br>
	
<h5>How to run</h5>
	&nbsp;&nbsp;&nbsp;&nbsp;gcc bspline.c -o obj -lglut -lGLU -lGL -lm<br>
	&nbsp;&nbsp;&nbsp;&nbsp;./obj<br>

