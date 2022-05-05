# Computational_Physics_port.
Hello this is my final portfolio for my computatinal physics class. the class is a physics/coding based class and this repository holds all of my projects that i have done in the class.

# Project Order
  1. Drude Model
  2. Project1 aka Double Pendulum
  3. buoyant forces on an object
  4. Vibrating Hoops
  5. Ising Model.

# Drude Model
  this project was to create a simulation of a model with the main idea is having objects being calculated with colissions with another object then updating all of the objects in the system.
  
# Double Pendulum
the double pendulum code was based on using our Ode file which solves the Ordinary Differential Equations for us and to create a model with it. (Note that when running the code it will take some time to run do to alot of iterations
# buoyant forces
the code goes through fluid dynamics and the assumption for this is that an object is dropped into the water with only gravity affecting said object which causes the buoyant force, viscosity of the liquid, and drag to affect the object trying to force it up.
# vibrating hoops

# ising Model
the Ising Model is the code using the monte carlos simulation and the Metropolis Algorthim.

A small trick can be done to optimally calculate the dE in 2D. Lets assume that spin S[i, j] is flipped, then only the nearest neighbor spins will account for a change in energy. There are two ways to calculate dE:

 1.First way is the simplest- take the exponential of the change in energy. Remember calculating the exponential N^2 times for each Monte Carlo move can get expensive!
 2.Second way is the least expensive in terms of computation time. Here you use the fact that spin can take values 1 and -1, and hence, there are only two possibilities for an energy increasing move. They are
  d         d           u         u    
d d d =>  d u d  or   u u u =>  u d u   #change in energy is 8
  d         d           u         u   



  d         d           u         u    
d d u =>  d u u  or   u u d =>  u d d   #change in energy is 4
  d         d           u         u 
Here u and d, respectively, denote the up and down configuration of the spins, which correspond to value 1 and -1.
