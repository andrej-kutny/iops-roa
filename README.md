Assignment description

# Designing randomized optimization algorithms

Working with Randomized Optimization Algorithms (ROAs) involves accounting for their stochasticity.

Their random-oriented components affect their behavior and performance. As a result, developing a ROA requires educated design choices.

### Task

In this assignment, you must develop two algorithms, i.e., one **trajectory-based** and one **population-based**, to solve the ***job shop scheduling problem***. The problem, also known as the *job-shop problem*, involves scheduling a set of jobs on a set of machines, where each job consists of a sequence of operations that must be processed in a specific order (precedence constraints). The goal is typically to find the optimal sequence of jobs on each machine to minimize the ***makespan***, i.e., the total time required to complete all jobs.

You can read more about the problem [here](https://developers.google.com/optimization/scheduling/job_shop).

***Instances.*** Choose and work with as many of the [benchmark instances](./data/jobshop.txt) as you want.

The instances are formatted with one line per job, listing the machine number and processing time for each step. For example, the following line:

```
4 88 8 68 6 94
```

means that job 1 (first line) should be assigned to machine 4 first, which takes 88 minutes to process; then to machine 8, which takes 68 minutes; and finally to machine 6, which takes 94 minutes.

***Algorithms.*** Feel free to experiment with as many of the algorithms we saw in the lecture as you want. Keep in mind that you need <u>at least</u> one trajectory-based and one population-based included in the final submission.

A good practice is to modularize your algorithms so you can test several versions without rewriting the code.

### Submission

You must submit a **_Jupyter Notebook_**, in which (a) you include the **algorithms**, (b) some **analysis with visualizations**, and (c) **comparative results**.

Use headers to distinguish each section.

***Algorithms.*** Include adequate comments in the algorithms.

Any preparatory/preprocessing steps required before running your algorithm(s) should be included before the algorithms section.

***Visualizations.*** The visualizations should be accompanied by text where you reflect on the plots.

***Results.*** The comparative results should support your final choice of algorithms.

Each cell should have been executed when you submit the Notebook.
