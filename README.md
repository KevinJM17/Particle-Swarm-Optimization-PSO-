# Principle Swarm Optimization
Principle Swarm Optimization (PSO) is an artificial intelligence technique that can be used to find appropriate solution to complex maximization and minimization problems. 

In this repository I have performed PSO on the equation: y = -15 (Sin(2x)^2 - (x-2)^2 + 160), to get the optimal position of x to obtain the maximum of the function.

# PSO Process
Step 1: Initialize the population.

Step 2: Evaluate the fitness of each particle.

Step 3: Modify the velocity & position of all particles based on previous best (pbest) and global best (gbest).

Step 4: Terminate on some condition

Step 5: Go to step 2.

# Velocity Updation (Max velocity, Vmax = 20)
Vi(t + 1) = W.Vi(t) + C1.r1.(pbesti - xi(t)) + C2.r2.(gbest - xi(t))

W -> weight factor

C1, C2 -> acceleration constant

pbesti -> personal best position attained by each particle i so far

gbest -> global best position discovered so far by any particle

r1, r2 -> random number uniformly distributed between [0, 1]

# Position Updation
xi(t + 1) = xi(t) + vi(t + 1)
