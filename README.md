# **Bio-Inspired Systems**  
## **Optimization and Evolutionary Algorithms in Python**  
This repository offers Python implementations of various bio-inspired optimization and evolutionary algorithms, designed to solve complex computational challenges by mimicking natural processes. These techniques are widely applied across optimization, machine learning, and engineering fields.  

### **Included Algorithms:**  

---

## **Genetic Algorithm (GA)**  
### **Overview**  
Genetic Algorithms (GAs) iteratively refine a population of potential solutions through selection, crossover, and mutation. This implementation demonstrates a GA applied to maximizing a mathematical function.  

### **Key Features**  
- **Fitness Function:** Evaluates the quality of solutions (e.g., maximizing x²).  
- **Selection:** Probabilistic parent selection based on fitness scores.  
- **Crossover:** Combines genetic material from two parents to create offspring.  
- **Mutation:** Introduces variation by randomly modifying genes.  

### **Code Highlights**  
- **Fitness Function:** Defines the optimization objective (x² maximization).  
- **Population Evolution:** Generates and refines a population over generations.  
- **Progress Tracking:** Displays the best solution at each iteration.  

### **Applications**  
- Optimization of complex problems.  
- Feature selection in machine learning.  
- Pathfinding and resource management.  
- Strategic decision-making in games.  

---

## **Particle Swarm Optimization (PSO)**  
### **Overview**  
PSO simulates a swarm of particles navigating the solution space, adjusting their trajectories based on personal and global best positions. This implementation optimizes a quadratic function.  

### **Key Features**  
- **Fitness Evaluation:** Uses -x² to rank solutions.  
- **Particle Dynamics:** Tracks position, velocity, and personal best.  
- **Collaborative Search:** Particles communicate to converge on the optimal solution.  

### **Code Highlights**  
- **Particle Class:** Defines particle attributes (position, velocity, fitness).  
- **Velocity Update Rule:** Balances inertia, self-learning, and swarm influence.  
- **Boundary Handling:** Keeps particles within the solution space.  
- **Convergence Tracking:** Iteratively updates positions and fitness values.  

### **Applications**  
- Function optimization.  
- Feature selection in ML.  
- Engineering design.  
- Scheduling and pathfinding.  

---

## **Ant Colony Optimization (ACO)**  
### **Overview**  
ACO mimics how ants deposit pheromones to collaboratively discover optimal solutions. This implementation solves the Traveling Salesman Problem (TSP).  

### **Key Features**  
- **Distance Matrix:** Simulates city distances.  
- **Pheromone Trails:** Reinforces promising paths.  
- **Heuristic Guidance:** Prioritizes shorter routes.  
- **Pheromone Evaporation:** Prevents stagnation and promotes exploration.  

### **Code Highlights**  
- **Ant Class:** Defines ants constructing routes based on pheromone levels.  
- **Pheromone Update:** Balances exploration and exploitation.  
- **Iterative Optimization:** Improves solutions over multiple iterations.  
- **Feedback Mechanism:** Tracks the best distance found per iteration.  

### **Applications**  
- Route planning and logistics.  
- Network and resource optimization.  
- Scheduling and task allocation.  

---

## **Cuckoo Search Optimization (CSO)**  
### **Overview**  
CS models cuckoos’ reproductive strategies, leveraging Lévy flights and nest abandonment mechanisms to enhance solution search.  

### **Key Features**  
- **Objective Function:** Optimizes a customizable function (e.g., a quadratic sum).  
- **Lévy Flights:** Uses long-distance jumps for diverse exploration.  
- **Nest Abandonment:** Simulates host rejection of foreign eggs, promoting diversity.  
- **Iterative Refinement:** Tracks the best solution across generations.  

### **Code Highlights**  
- **Nests Management:** Represents solutions evolving over iterations.  
- **Lévy Flight Implementation:** Enables efficient global search.  
- **Replacement Strategy:** Prevents stagnation by introducing fresh solutions.  
- **Progress Monitoring:** Displays the best fitness score per iteration.  

### **Applications**  
- Continuous optimization.  
- Feature selection in ML.  
- Engineering design.  
- Resource allocation and scheduling.  

---

## **Grey Wolf Optimization (GWO)**  
### **Overview**  
GWO simulates wolf pack leadership dynamics to optimize solutions, balancing exploration and exploitation.  

### **Key Features**  
- **Hierarchical Leadership:** Alpha, beta, and delta wolves guide the search.  
- **Position Updates:** Wolves adjust positions based on leadership influence.  
- **Convergence Mechanism:** Progressively refines solutions.  

### **Code Highlights**  
- **Objective Function:** Optimizes a sum-of-squares function.  
- **Wolf Positioning:** Wolves update based on their social roles.  
- **Exploration vs. Exploitation:** Alpha, beta, and delta wolves balance search strategies.  
- **Iteration Feedback:** Displays the best fitness score and alpha wolf’s position.  

### **Applications**  
- Engineering design.  
- Feature selection and ML parameter tuning.  
- Structural optimization.  
- Resource management.  

---

## **Parallel Cellular Algorithm (PCA)**  
### **Overview**  
PCA uses a grid-based approach where each cell represents a potential solution, evolving based on local interactions.  

### **Key Features**  
- **Cellular Automata-Based Search:** Solutions update through neighborhood interactions.  
- **Parallel Computation:** Each cell processes updates simultaneously.  
- **Convergence Mechanism:** Cells refine solutions over iterations.  

### **Code Highlights**  
- **Grid Initialization:** Defines a population of cells.  
- **Fitness Evaluation:** Uses a sum-of-squares objective function.  
- **Neighborhood Interaction:** Cells adjust based on neighboring solutions.  
- **Iterative Optimization:** Continues refining solutions.  

### **Parameters**  
- **Grid Size:** Defines the number of cells.  
- **Solution Space Dimension:** Sets the dimensionality.  
- **Iterations:** Controls optimization duration.  

### **Applications**  
- Engineering design.  
- ML feature selection and tuning.  
- Data clustering.  
- Scheduling and resource allocation.  

### **Benefits**  
- **Scalability:** Ideal for large-scale problems.  
- **Parallel Efficiency:** Utilizes computational resources effectively.  
- **Exploration Capability:** Effectively searches the solution space.  

---

## **Gene Expression Programming (GEP)**  
### **Overview**  
GEP models genetic expression, encoding solutions as genes that evolve through selection, crossover, mutation, and gene expression.  

### **Key Features**  
- **Genetic Representation:** Solutions stored as gene sequences.  
- **Selection & Crossover:** Fittest solutions evolve via genetic operations.  
- **Mutation & Expression:** Introduces variation and translates genes into executable expressions.  

### **Code Highlights**  
- **Gene Encoding:** Represents mathematical expressions using operators and variables.  
- **Fitness Function:** Evaluates solutions against a defined cost function.  
- **Selection & Evolution:** Genes evolve through genetic operations.  
- **Iteration Tracking:** Displays fitness improvements over generations.  

### **Key Parameters**  
- **Population Size:** Defines the number of candidate solutions.  
- **Gene Length:** Sets the complexity of encoded solutions.  
- **Mutation & Crossover Rates:** Controls variation introduction.  
- **Generations:** Specifies evolution cycles.  

### **Applications**  
- Engineering design.  
- ML hyperparameter tuning.  
- Data mining & pattern recognition.  
- Resource scheduling.  

### **Benefits**  
- **Global Search:** Effectively explores the solution space.  
- **Adaptability:** Customizable for various optimization problems.  
- **Parallel Efficiency:** Supports parallel execution for large-scale problems.  
