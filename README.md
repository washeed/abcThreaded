

### Threaded ABC Algorithm

**ABC Algorithm with Threading**

This Python implementation demonstrates the Artificial Bee Colony (ABC) algorithm using multi-threading. The ABC algorithm is a metaheuristic optimization technique inspired by the foraging behavior of honey bees.

#### Objective Function

The implemented objective function is the Rastrigin function:

\[ f(x) = A \cdot n + \sum_{i=1}^{n} \left(x_i^2 - A \cdot \cos(2\pi x_i)\right) \]

Here, \(n\) is the dimensionality of the search space, and \(A\) is a constant usually set to 10.

#### Parameters

- `SN`: Number of food sources.
- `MCN`: Maximum number of cycles.
- `limit`: Maximum number of exploitations for a solution.
- `dimensionality`: Dimensionality of the search space.

#### Dependencies

- NumPy

#### License

This project is licensed under the [MIT License](LICENSE).

### Non-Threaded ABC Algorithm

**ABC Algorithm without Threading**

This Python implementation demonstrates the Artificial Bee Colony (ABC) algorithm without using multi-threading.

#### Objective Function

The implemented objective function is the Rastrigin function:

\[ f(x) = A \cdot n + \sum_{i=1}^{n} \left(x_i^2 - A \cdot \cos(2\pi x_i)\right) \]

Here, \(n\) is the dimensionality of the search space, and \(A\) is a constant usually set to 10.

#### Parameters

- `SN`: Number of food sources.
- `MCN`: Maximum number of cycles.
- `limit`: Maximum number of exploitations for a solution.
- `dimensionality`: Dimensionality of the search space.

#### Dependencies

- NumPy
