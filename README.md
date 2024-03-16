## Monte Carlo Simulation for Estimating PI
This Python script uses a Monte Carlo simulation to estimate the value of PI. The program generates a specified number of random points within a square and determines how many fall inside a circle inscribed in the square. By calculating the ratio of points inside the circle to the total points, an approximation of PI is obtained. The script visualizes the random points using a scatter plot in Matplotlib, where the color of each point is determined by its position in the circle. The title of the plot displays the number of points used in the simulation and the estimated value of PI with four decimal places.

## Mathematical detail
The area of a circle with radius $r$ is given by the formula $A = \pi  r^2$. For a circle inscribed in a square with side length $2r$, the area of the square is $(2r)^2 = 4r^2$. The ratio of the area of the circle to the area of the square is:
$$
\frac{π  r^2}{4r^2} = \frac{π}{4}
$$
This relationship is utilized in the Monte Carlo simulation to estimate the value of PI.

![Plot Image](/output.png)


