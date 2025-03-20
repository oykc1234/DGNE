Dynamic Graph Neural Evolution (DGNE)

Overview

Dynamic Graph Neural Evolution (DGNE) is an innovative optimization framework that integrates Graph Neural Networks (GNNs) with Evolutionary Algorithms (EAs). It builds upon the foundation of Graph Neural Evolution (GNE) and introduces dynamic filtering mechanisms and adaptive Gaussian sampling functions to adjust the population distribution during the optimization process. DGNE achieves a balance between global exploration and local exploitation, enhancing optimization efficiency.
By emphasizing high-frequency information in the early stages to maintain population diversity and low-frequency information in the later stages to promote convergence, DGNE effectively optimizes the search process. The framework is designed to handle complex, high-dimensional optimization tasks and is particularly well-suited for scenarios where stability and adaptability are crucial.

Key Features

Dynamic Population Distribution: DGNE adapts the population distribution throughout the optimization process using dynamic filtering and Gaussian sampling.
Global Exploration & Local Exploitation: It strikes a balance between global exploration (early stages) and local exploitation (later stages) to optimize search efficiency.
High and Low Frequency Information: The algorithm focuses on high-frequency information in the early stages to improve diversity and low-frequency information in the later stages to improve convergence.
Graph Neural Networks (GNNs): DGNE leverages GNNs to capture and model the complex relationships and dependencies within the population, enhancing its optimization capabilities.

Performance

Experiments were conducted on the CEC2017 benchmark suite across 30, 50, and 100 dimensions. DGNE was compared with advanced algorithms like LSHADE, LSHADE cnEpSin, MadDE, SaDE, EA4eig, and classic algorithms like DE and CMA-ES. The results showed that DGNE:

Achieved the best average ranking in 50 and 100 dimensions.
Ranked third in 30 dimensions.
Demonstrated superior overall performance across all dimensions, showcasing its stability and robustness in various optimization scenarios.
Although DGNE performs slightly less competitively in low-dimensional tasks, it shows strong competitiveness and significant advantages in high-dimensional optimization problems.

Applications

DGNE has great potential as an optimization method in artificial intelligence and optimization fields. It can be applied to a wide range of complex optimization tasks, particularly those requiring robust performance in high-dimensional spaces. The method offers a promising direction for further research and development, especially in areas where population dynamics and adaptive filtering mechanisms are essential.

Conclusion

DGNE is a state-of-the-art optimization framework that leverages the power of Graph Neural Networks and Evolutionary Algorithms to provide efficient and adaptive solutions to high-dimensional optimization problems. Its dynamic population distribution, emphasis on both global exploration and local exploitation, and stability across different scenarios make it a promising tool for further advancements in the field of optimization.

Authors and Contact

This code is for the paper "Dynamic Graph Neural Evolution: An Evolutionary Framework Integrating Graph Neural Networks with Adaptive Filtering" accepted by the 2025 IEEE Congress on Evolutionary Computation. The authors are Kaichen Ouyang, Shengwei Fu, Yi Chen, and Huiling Chen. For inquiries, contact oykc@mail.ustc.edu.cn.
