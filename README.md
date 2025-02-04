🚀 Evolutionary and Metaheuristic Approach for the Traveling Salesman Problem
A Comparative Study

📌 Author: Akimuddin Aslam Shaikh
📍 Institution: National College of Ireland, School of Computing


📌 Project Overview
The Traveling Salesman Problem (TSP) is a well-known combinatorial optimization problem that seeks the shortest possible route for a salesman to visit multiple cities and return to the starting point. This project explores metaheuristic and evolutionary algorithms to solve TSP efficiently, comparing their performance in terms of accuracy and execution time.

🔍 Key Highlights
✅ Comparison of three algorithms: Integer Programming, Genetic Algorithm, and Simulated Annealing
✅ Benchmarking on TSP datasets with 29, 40, and 80 cities from Bavaria
✅ Evaluated shortest path and computational efficiency
✅ Enhanced Genetic Algorithm and Simulated Annealing for improved results
✅ Integer Programming consistently found optimal solutions, while Genetic Algorithms and Simulated Annealing balanced efficiency and accuracy

📊 Algorithms Implemented & Performance Summary
Algorithm	Optimality	Execution Time	Scalability
Integer Programming	✅ Best (Optimal Solutions)	❌ Slowest	❌ Struggles with large datasets
Genetic Algorithm (GA)	⚖️ Balance between optimality & speed	✅ Faster than Integer Programming	✅ Scalable for larger datasets
Simulated Annealing (SA)	⚖️ Balances accuracy & efficiency	✅ Performs well for medium-sized problems	✅ Handles larger datasets efficiently
🔹 Key Finding: Integer Programming provides the most accurate results, but Genetic Algorithms and Simulated Annealing are better suited for large-scale real-world applications due to their speed and adaptability.
🔹 Improved Metaheuristic Approaches: Fine-tuned mutation rates, cooling schedules, and selection techniques to enhance GA and SA performance.

🛠️ Technologies & Tools Used
Python 
NumPy & Pandas (Data Handling)
Matplotlib & Seaborn (Visualization)
SciPy & OR-Tools (Optimization & Integer Programming)
DEAP Library (Genetic Algorithm Implementation)
📌 Results & Insights
✅ Integer Programming consistently achieved the best solutions but was computationally expensive for larger datasets.
✅ Genetic Algorithm performed efficiently and was scalable, making it suitable for practical TSP scenarios.
✅ Simulated Annealing achieved near-optimal results while significantly reducing computation time.
✅ Parameter tuning significantly impacted the efficiency and accuracy of GA and SA.

📌 Future Work
✔ Implement Hybrid Algorithms (e.g., combining Genetic Algorithm with Local Search techniques).
✔ Test on real-world datasets with dynamic constraints (e.g., traffic conditions, delivery time windows).
✔ Explore Reinforcement Learning approaches for TSP optimization.
