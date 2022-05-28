# Big-M-Method
Big-M Method Implementation in Java

Suppose, we have: <br />
Maximize z = x1 + 5x2 <br />
subject to: <br />
  3x1 + 4x2 ≤ 6 <br />
  x1 + 3x2 ≥ 2 <br />
  x1, x2 ≥ 0 <br />
  
If you want to solve this problem then, simply run the simplex_method.java code and enter values in console as same as below: <br />

Choose Problem Type: <br />
		 1) Maximization Problem <br />
		 2) Minimization Problem <br />
Enter chosen type: 1 <br />
Enter No. of variables: 2 <br />
Enter No. of constraints: 2 <br />
Enter coefficients of Objective Function: <br />
Enter the value of x1: 1 <br />
Enter the value of x2: 5 <br />
Enter LHS coefficients of constraints(1) : <br />
Enter the value of x1: 3 <br />
Enter the value of x2: 4 <br />
Choose Inequality option: <br />
		 1) ≤ <br />
		 2) ≥ <br />
		 3) = <br />
Enter chosen option: 1 <br />
Enter RHS coefficient of constraints(1) : 6 <br />
Enter LHS coefficients of constraints(2) : <br />
Enter the value of x1: 1 <br />
Enter the value of x2: 3 <br />
Choose Inequality option: <br />
		 1) ≤ <br />
		 2) ≥ <br />
		 3) =  <br />
Enter chosen option: 2 <br />
Enter RHS coefficient of constraints(2) : 2 <br />


************ Iteration - 1 ************ <br />
Incoming Variable is: x2 <br />
Outgoing Variable is: a1 <br />

************ Iteration - 2 ************ <br />
Incoming Variable is: s2 <br />
Outgoing Variable is: s1 <br />


Final table: [[1.2499999, 0.0, 0.75, 1.0, -1.0], [0.75, 1.0, 0.25, 0.0, 0.0]] <br />

#Note: s1 is a slack variable, s2 is a surplus variable & a1 is an artificial variable. <br />

*************** Basic Feasible Solution: ********************* <br />
The value of x1 is: 0 <br />
The value of x2 is: 1.5 <br />
The value of s1 is: 0 <br />
The value of s2 is: 2.4999998 <br />
The value of a1 is: 0   <br />
The value of Z_max is: 7.5 <br />

Process finished with exit code 0 <br />
