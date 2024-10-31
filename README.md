java c
ECSE 543A NUMERICAL METHODS IN ELECTRICAL ENGINEERING 
Assignment 21)  Figure  1  shows  two  first-order  triangular  finite  elements  used  to  solve  the  Laplace equation for electrostatic potential.  Find a local S-matrix for each triangle and a global S-matrix for the mesh, which consists of just these two triangles.   The local (disjoint)
and global (conjoint) node-numberings are shown in Figure 1(a) and (b), respectively. Also, Figure 1(a) shows the (x, y)-coordinates of the element vertices in meters.

Figure 1
2)  Figure 2 shows the cross-section of an electrostatic problem with translational symmetry: a rectangular coaxial cable. The inner conductor is held at 110 volts and the outer conductor is grounded. (This is similar to the system considered in Question 3, Assignment 1.)
(a) Use the two-element mesh shown in Figure  1(b) as a “building block” to construct a finite element mesh for one-quarter of the cross-section of the coaxial cable. Specify the mesh,  including  boundary  conditions,  in  an  input  file  following  the  format  for  the SIMPLE2D program as explained in the course notes. (Hint: Your mesh should consist of 46 elements.)
(b) Use the SIMPLE2D program with the mesh from part (a) to compute the electrostatic potential solution. Determine the potential at (x,y) = (0.06, 0.04) from the data in the output file of the program.
(c) Compute the capacitance per unit length of the system using the solution obtained from
SIMPLE2D. 
Note:         The SIMPLE2D program and related utility programs are available from the
myCoursespage for this course or on the World-Wide-Web at:
http://www.cambridge.org/ca/academic/subjects/engineering/engineering- mathematics-and-programming/finite-elements-electrical-engineers-3rd-editi代 写ECSE 543A NUMERICAL METHODS IN ELECTRICAL ENGINEERING Assignment 2Matlab
代做程序编程语言on?format=PB?format=PB (Click on “Resources” tab.)   Please read the file README.1ST before using the software. 

Figure 2.
3)  Write a program implementing the conjugate gradient method (un-preconditioned). Solve the matrix equation corresponding to a finite difference node-spacing, h = 0.02m inx andy directions  for the  same one-quarter  cross-section  of the  system  shown  in  Figure  2  that considered in Question 2 above. Use a starting solution of zero. (Hint: The program you wrote for Question 3 of Assignment 1 maybe useful for generating the matrix equation.)
(a) Test  your  matrix  using  your  Choleski  decomposition  program  that  you  wrote  for Question 1 of Assignment 1 to ensure that it is positive definite. If it is not, suggest how you could modify the matrix equation in order to use the conjugate gradient method for this problem.
(b) Once  you  have  modified  the  problem,  if necessary,  so  that  the  matrix  is  positive definite, solve the matrix equation first using the Choleski decomposition program from Assignment 1, and then the conjugate gradient program written for this assignment.
(c) Plot a graph of the infinity norm and the 2-norm of the residual vector versus the number of iterations for the conjugate gradient program.
(d) What is the potential at (x,y) = (0.06, 0.04), using the Choleski decomposition and the conjugate gradient programs, and how do they compare with the value you computed in Question 2(b) above. How do they compare with the value at the same (x,y) location and for the same node spacing that you computed in Assignment 1 using SOR.
(e) Suggest how you could compute the capacitance per unit length of the system from the finite difference solution.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
