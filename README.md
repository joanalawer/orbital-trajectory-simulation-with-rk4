# ORBITAL TRAJECTORY SIMULATION USING FOURTH-ORDER RUNGE-KUTTA (RK4) METHOD

The Earth–satellite system is formulated as a two-body problem governed by Newton’s Law of Universal Gravitation. 
The resulting second-order equations of motion are transformed into a first-order state-space system and integrated numerically using RK4 method to advance the system in time.
Simulation is demonstrated using Python Numby and Matplotlib Librraries


## PARAMETERS USED
	Earth’s gravitational parameter μ given as: (3.986*〖10〗^14 m^3/s^2 )
	Earth’s radius RE: (6.371*〖10〗^6 m)
	Initial altitude set to: (400km=400000m)
	Initial position is taken to be  (r_0=R_E+400000)
	Initial velocity chosen to be v_0=(7670)m/s
	Time step is set to an interval of 10 seconds: ∆t=10s
	Total propagation time (Approximate time it takes to make an orbit): 5600s
