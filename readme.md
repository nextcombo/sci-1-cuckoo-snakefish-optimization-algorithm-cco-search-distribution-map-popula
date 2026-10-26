# [SCI-1] Cuckoo Snakefish Optimization Algorithm (CCO) - Search Distribution Map, Population Diversity, and Exploration-Exploitation Analysis

Run on platforms: MATLAB R2023a and above, no additional toolboxes required, one-click operation.
References: Cuckoo catfish optimizer: a new meta-heuristic optimization algorithm, published in the top SCI journal Artificial Intelligence Review 2025 (ranked first in the Chinese Academy of Sciences' First-Class Zone, IF=13.9).
Documentation interpretation:
This algorithm paper was just published in July 2025, and there is currently zero analysis on improvements to the CCO algorithm! This article provides a complete CCO analysis program that can generate 10 high-quality analysis charts in one batch, covering search behavior, population dynamics, exploration-exploitation balance across all dimensions. The charts can be directly embedded into the method comparison section of SCI papers, significantly reducing the threshold for visualizing algorithm performance, making it very easy to support Chinese core journals, EI, and even SCI papers!
The core of the CCO (Cuckoo Catfish Optimization Algorithm) is a three-stage adaptive mechanism: parameter driving the algorithm from early compression-cooperation exploration, through Lévy flight transition, to late chaos predatory (Cauchy + Gaussian perturbation) + death parasitism rebirth. The actual effectiveness of this mechanism must be clearly presented with visualization.
Core Mechanisms:
① Compression space strategy: Early multiple individuals collaborate to gradually compress the escape space of the global optimum. Simulating random resistance in nature, meeting the standard normal distribution, describing the intensity of population collaboration.
② Surrounding search strategy: Logarithmic spiral and spherical encirclement alternately perform, controlling the rate of encirclement reduction by a shrinkage factor (highest efficiency), balancing broad exploration with fine local search.
③ Transition strategy: The population is divided into two groups, one moving towards (exploration) and another away from (development), while adding Lévy flight perturbations, achieving smooth transition between exploration and development.
④ Chaotic Prey-Catching Strategy: Late-stage individuals enter the cichlid nests, and based on the current aggregation degree compared to the initial aggregation degree, trigger different intensities of chaotic perturbations—Cauchy distribution simulates the cichlids' localized panic, while Gaussian distribution simulates large-scale stress escapes, helping the algorithm escape from local minima.
⑤ Death and Parasitic Strategies: Individuals that fail to capture are subject to a linearly decreasing probability of death, followed by a global random rebirth (probability restart mechanism) after death, preventing premature convergence of the population.
Experimental performance
Compared with 11 classic algorithms and 10 improved ones, CCO achieved the top rank in Friedman comprehensive ranking across all 23 classic test functions, CEC2014, CEC2017, CEC2022 benchmarks. It achieved an optimal solution rate across all test functions of 91.52%. Among them, CEC2017 (29 functions) achieved 100% optimal solutions compared to classic algorithms and 80% optimal solutions compared to improved ones, without other algorithms being able to achieve both in the two types of comparisons.
Why is it insufficient to have only convergence curves?
The experience with SCI (Scientific Citation Index) knows that reviewers only say "This does not demonstrate any difference in the search mechanism of the algorithm" when they see a convergence curve. What truly convinces reviewers is multi-dimensional qualitative analysis—where has the algorithm moved within the search space? When did population diversity decrease? Was the transition between exploration and development smooth or abrupt? Answering these questions cannot be done solely by benchmark numbers. This paper adds:
Follow the editor to receive irregularly high-quality innovative learning materials, articles, and code snippets, boosting your research endeavors!

## Images

![[SCI 1st] Cuckoo Snakefish Optimization (CCO) Algorithm, Search Distribution Map, Population Diversity, Exploration and Development Analysis](01.png)
![[SCI 1st] Cuckoo Snakefish Optimization (CCO) Algorithm, Search Distribution Map, Population Diversity, Exploration and Development Analysis](02.png)
![[SCI 1st] Cuckoo Snakefish Optimization (CCO) Algorithm, Search Distribution Map, Population Diversity, Exploration and Development Analysis](03.png)
![[SCI 1st] Cuckoo Snakefish Optimization (CCO) Algorithm, Search Distribution Map, Population Diversity, Exploration and Development Analysis](04.png)
![[SCI 1st] Cuckoo Snakefish Optimization (CCO) Algorithm, Search Distribution Map, Population Diversity, Exploration and Development Analysis](05.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
