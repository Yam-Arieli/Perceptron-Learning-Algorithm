# Problem from the course "Statistical Learning" of the Open University of Israel
### This is an implementation of the perceptron algorithm
>#### Generate a linearly separable data set of size N=20 as follows:
>Choose a random line in the plane (d=2) as your target function f, where one side of the line 
>maps to +1 and the other maps to -1. Choose the inputs of the data set as random points in 
>the plane and evaluate the target function on each input to get the corresponding output.
<ol>
  <li>Run the Perceptron Learning Algorithm on the data set above. 
    <ol>
      <li>Report the number of updates that the algorithm takes before converging.</li>
      <li>Plot the training set, the target function f, and the final hypothesis g in the 
same figure. </li>
      <li>Plot the training set, the target function f, and the final hypothesis g in the.
same figure.</li>
      <li>Randomly generate a test data of size 100 and calculate the fraction of points 
where f and g disagree on this data set.
same figure.</li>
    </ol>
  </li>
  <br>
  <li>Repeat (1) with another randomly generated data set of size N=20. Compare your 
results with (1).</li>
<br>
  <li>Repeat (1) with another randomly generated data set of size N=100. Compare your 
results with (1).</li>
<br>
  <li>Repeat (1) with another randomly generated data set of size N=1000. Compare your 
results with (1).</li>
<br>
  <li>Modify the algorithm such that it takes inputs of dimension d=10 instead of d=2.
<br>
Randomly generate a linearly separable data set of size N=1,000 and feed the data set 
to the algorithm.
<br>Repeat the algorithm on the same data set for 100 experiments 
where in the iterations of each experiment pick x(t) randomly instead of 
deterministically.
<br>Plot a histogram for the number of updates that the algorithm takes 
to converge.</li>
<br>
  <li>Summarize your conclusions with respect to accuracy and running time as a function 
of N and d.</li>
</ol>