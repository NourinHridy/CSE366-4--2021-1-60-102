Task Assignment Optimization using Genetic Algorithm

**1. Introduction:**
Efficient task optimization allocation can enhance overall productivity. Using Genetic Algorithm, this task optimization of robots tried to ensure resource utilization.

**2. Implementation Details:**

 **Data Generation:** Data for task duration, task priorities and robot efficiency are generated randomly where number of tasks and robots are 10 and 5 respectively. 

 **Genetic Algorithm** : Genetic Algorithm included: 

 **Fitness Evaluation:** Using the formula of Total Production Time, the fitness of each solution is calculated based on the total time taken to complete tasks and the workload distribution among robots.
 
 **Selection:** In the selection, tournament solutions are implied where the every specimen of the population are selected. Based on their fitness level, parents for next generation are taken.
 
 **Crossover:** Two parents are selected and crossed over to produce two children as in new solutions by combining parts of their assignments.
 
 **Mutation:** Random mutations are applied to the offspring with a certain probability to introduce diversity.
 
 **Visualization:** After finding the best solution, the task assignments, durations, and priorities on a grid are shown using matplotlib.

**3. Challenges Faced:** The challenges that were faced:

 **Algorithm Complexity:** Designing an efficient fitness function and balancing exploration in the GA were challenging.

 **Parameter Tuning:** Adjusting parameters such as population size, tournament size, and mutation rate to achieve convergence.
 
 **Visualization:** Ensuring clear and informative visualization of the task assignments while maintaining readability.

**4. Results Analysis:**
The GA optimized tasks within the robots efficiently and minimized the total time. As the task durations and task priorities were different, the algorithm ensured to split the time and to balance the workload.

The visualization provides a clear insight as how the distribution of tasks among the robots are diverged.

![Screenshot 2024-04-04 132107](https://github.com/NourinHridy/CSE366-4--2021-1-60-102/assets/116054361/5220e31c-871d-40fb-9f30-a26c33859834)


**5. Conclusion:**
In conclusion, the genetic algorithm-based approach effectively addresses the task assignment optimization problem by providing efficient and balanced assignments of tasks to robots. By leveraging the power of evolutionary computation, the approach offers a robust and scalable solution with potential applications across various domains.
