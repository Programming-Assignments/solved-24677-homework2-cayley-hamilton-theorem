Download Link: https://assignmentchef.com/product/solved-24677-homework2-cayley-hamilton-theorem
<br>



<h1><strong>Exercise 1. </strong>Cayley-Hamilton Theorem</h1>

Given

Find <em>A</em><sup>10 </sup>and <em>e<sup>At </sup></em>uisng C-H.

<h1><strong>Exercise 2. </strong>Linear dynamics solution</h1>

Let <em>x</em><sub>1</sub>(<em>t</em>) be the water level in Tank 1 and <em>x</em><sub>2</sub>(<em>t</em>) be the water level in Tank 2 . Let <em>α </em>be the rate of outflow from Tank 1 and <em>β </em>be rate of outflow from Tank 2 . Let <em>u </em>be the supply of water to the system. The system can be modelled into the following differential equations:

Figure 1: Tank Problem

Given <em>α </em>= 0<em>.</em>1, <em>β </em>= 0<em>.</em>2, <em>u </em>= 1, <em>x</em><sub>1</sub>(0) = 2, <em>x</em><sub>2</sub>(0) = 1, find the water level in both tanks after 5s. Solve with C-H theorem. You may use calculator but do not directly use programming.

<strong>Exercise 3. </strong><em>Jordan form, decomposition </em><em>(20 points, 5 for each A) </em>Derive the Jordan-form of the following matrices manually.

<h1><strong>A</strong><strong>   A </strong><strong>A</strong><strong>      A</strong></h1>

(Write the Jordan form such that eigenvalues should be in ascending order of their absolute√

values. The absolute value of a complex number is defined as |<em>a </em>+ <em>bi</em>| =        <em>a</em><sup>2 </sup>+ <em>b</em><sup>2</sup>)

<h2><strong>Exercise 4. </strong>CT and DT Dynamics</h2>

Given the following system. Assume <em>x</em>(0) = 0 and u is a unit step input. Answer the following questions with both manual derivation and Python programming. Include all your derivation. Solutions without derivation will receive zero points. Submit the code to Gradescope.

<ol>

 <li>i) Find <em>y</em>(5) for CT system <strong>(5 points) </strong>ii) Find the discretized state space representation using sample time <em>T </em>= 1<em>s </em><strong>(5 points) </strong>iii) Find <em>y</em>(5) of Discrete Time system. <strong>(5 points) </strong>Also plot signals <em>y</em>(<em>t</em>) for both CT and DT systems in the same figure. <strong>(5 points)</strong></li>

</ol>

<h2><strong>Exercise 5. </strong>Diagonalization</h2>

In the Fibonacci sequence, a Fibonacci number is the sum of the two previous F’s, starting from 0, 1

Fibonacci numbers: 0<em>,</em>1<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>5<em>,</em>8<em>,</em>13<em>,….</em>

Fibonacci equation: <em>F<sub>k</sub></em><sub>+2 </sub>= <em>F<sub>k</sub></em><sub>+1 </sub>+ <em>F<sub>k</sub></em>

How could we find the 20th Fibonacci number, without starting at <em>F</em><sub>0 </sub>= 0 and <em>F</em><sub>1 </sub>= 1, and add the numbers one by one all the way out to <em>F</em><sub>20</sub>? Hint: construct a discrete linear time invariant system.

You are allowed to use programming in the final matrix multiplication, but do not use the for loop to directly computer Fibonacci sequence