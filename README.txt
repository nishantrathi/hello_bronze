First Name - Nishant
Last Name - Rathi
Email Id - nishantrathi@csu.fullerton.edu

Description-
1) Changed the color of both lights to white
2) Calculate reflection vector from normal vector and eyedirection
	a) R = 2n(n.l)-l
	b) R = l-2n(n.l)
	Both the above reflection function gives different output in color but I used first equation (a)  
3) Cos(theta) is a dot product of eye direction vector and reflection vector
4) Calculeted color through given equation
5) Assigned calculated color to gl_FragColor
6) I tried to remove the ambient from the final color which increased the brightness of the object
7) I completed all the above calculations in Fragment shader