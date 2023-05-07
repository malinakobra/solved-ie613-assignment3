Download Link: https://assignmentchef.com/product/solved-ie613-assignment3
<br>
<strong>Question 1</strong>You will implement and compare different algorithms for sampling the arms of a stochastic multi-armed bandit. Each arm provides i.i.d. rewards from a Bernoulli distribution with mean given in the table below. The objective is to minimise the regret. The algorithms you will implement are epsilon-greedy exploration, UCB, KL-UCB, Thompson Sampling.

<table width="314">

 <tbody>

  <tr>

   <td width="48">Arm</td>

   <td width="53">Arm 1</td>

   <td width="53">Arm 2</td>

   <td width="53">Arm 3</td>

   <td width="53">Arm 4</td>

   <td width="53">Arm 5</td>

  </tr>

  <tr>

   <td width="48">Mean</td>

   <td width="53">0.4</td>

   <td width="53">0.3</td>

   <td width="53">0.5</td>

   <td width="53">0.2</td>

   <td width="53">0.1</td>

  </tr>

 </tbody>

</table>

Table 3.1: Table 1

For epsilon greedy, you can choose

<strong>Question 2  </strong>Pure exploration, Best Arm Selection: Consider a K-armed bandit where each arm is a Bernoulii random variable. We would like to identify the best arm with probability atleast 1−δ, i.e., Pr{Iˆ= I<sup>∗</sup>}≥ 1−δ, where Iˆ is the estimated best arm and I<sup>∗ </sup>is the best arm. Numerically compare the expected sample complexity and the mistake probability of the following algorithms for different values of K. Set (confidence parameter) δ = 0.1.

<ul>

 <li>KL-LUCB [1] with parameters</li>

 <li>lil’UCB [2] with parameters.</li>

</ul>

Vary K between 10 to 50 in step size of 10. For each K, generate 1000 bandit instances with mean reward for each arm drawn uniformly at random from [0,1]. Average the sample complexities over all the instances to obtain the average sample complexity and the mistake probability should be calculated as the fraction of times non best arm is returned after stop signals are received.

<strong>Submission Format and Evaluation: </strong>Your should submit a report along with your code. Please zip all your files and upload via Moodle. The zipped folder should named as YourRegistrationNo.zip e.g.‘154290002.zip’. The report should contain one figure with four plots corresponding to each algorithm in Q.1. Write a brief summary of your observations. We may also call you to a face-to-face session to explain your code.