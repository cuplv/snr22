# Symbolic and Numerical Methods for Reachability Analysis (SNR)


## SNR'22

Welcome to the home page of the 8th International Workshop on Symbolic-Numeric Methods for reachability Analysis (SNR). SNR'22 will collocate with [CONFEST'22](https://confest2022.mimuw.edu.pl) in Warsaw, Poland, on September, 12th 2022. 

Hybrid systems are complex dynamical systems that combine discrete and continuous components. Reachability questions, regarding whether a system can run into a certain subset of its state space, stand at the core of verification and synthesis problems for hybrid systems. Successful reachability analysis methods for hybrid systems require the unification of techniques from at least two research areas:
- _Symbolic methods_ that operate on exact and discrete representations of systems, in the form of various model checking and theorem proving algorithms.
- _Numerical methods_ that operate on various forms of numerical approximations and continuous transformations of the systems, as developed in the area of continuous dynamical systems and control theory. 

The existing, successful solutions for reachability analysis for hybrid dynamical systems cleverly integrate symbolic and numerical reasoning to tackle the scalability challenge. For instance, the reachable set computation methods explicitly construct flow-pipes that numerically overapproximate the reachable states over time, while efficient computation of such overapproximations requires symbolic representations such as support functions. Similarly, constraint solving methods symbolically encode reachability properties as logic formulas, while solving such formulas requires numerically-driven decision procedures. 
The key goal of the **Symbolic and Numerical Methods for Reachability Analysis** (SNR) workshop is to provide a platform to further explore synergies among these approaches by bringing together the experts in these two domains.

The SNR workshop aims to catalyze work on the interface of symbolic and numerical methods for the reachability analysis. The scope of the workshop includes, but is not restricted to, the following topics:
- Verification of hybrid systems
- Symbolic representation of regions in reachability analysis \item Techniques for Flow-pipe construction
- Abstraction techniques for hybrid systems and numerical programs
- Trajectory/Counterexample generation from symbolic paths
- Techniques for reliable integration
- Decision procedures supporting real numbers
- Formal logics to reason about hybrid systems
- Symbolic and Numerical Methods for Reinforcement Learning and Planning
- Domain specific approaches in Biology, Robotics, and Cyber-Physical Systems

This year, the organizers encourage submissions of papers exploring the intersection of SNR and Machine-Learning (ML).

## SNR and Machine Learning.
Machine Learning (ML) algorithms and data-driven components are at the core of modern engineering applications of hybrid dynamical systems providing support for perception and adaptation. Moreover, the recent successes of Deep Neural Networks (DNN) and Reinforcement Learning (RL) hint at powerful approaches to tackle scalability challenges in SNR. 
     
We invite research papers at the intersection of SNR and ML on the following non-exhaustive list of topics:      
- Reinforcement Learning (RL) for Real-Time and Hybrid Systems,
- Formal Logics for Continuous-State RL  (e.g., formal specifications in RL, shielding for RL),
- Decision Procedures for Continuous-State RL (e.g. SAT/SMT approaches to infer reward machines),
- Deep Neural networks for Symbolic and Numerical Reasoning for Reachability (e.g., neural certificates),
- Supervised Learning for SNR (e.g., using decision-trees in generating human-interpretable policies),
- Unsupervised Learning for SNR (e.g., mining formal specifications from behaviors), and
- Applications of SNR in safety-critical machine learning.     

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cuplv/snr22/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
