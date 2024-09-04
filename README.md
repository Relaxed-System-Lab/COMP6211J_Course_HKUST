<div style="text-align:center">
<a href="https://hkust.edu.hk/"><img src="https://hkust.edu.hk/sites/default/files/images/UST_L3.svg" height="45"></a>


# COMP6211J 2025 Fall

</div>

<h2 style="text-align: center;"> Advanced Large-Scale Machine Learning System for Foundation Models </h2>

**Lecturer**: [Binhang Yuan](https://binhangyuan.github.io/site/). 


## Overview

In recent years, foundation models have fundamentally revolutionized the state-of-the-art of artificial intelligence. Thus, the computation in the training or inference of the foundation model could be one of the most important workflows running on top of modern computer systems. This course unravels the secrets of the efficient deployment of such workflows from the system perspective. Specifically, we will: i) explain how a modern machine learning system (i.e., PyTorch) works; ii) understand the performance bottleneck of machine learning computation over modern hardware (e.g., Nvidia GPUs); iii) discuss four main parallel strategies in foundation model training (data-, pipeline-, tensor model-, optimizer- parallelism); and iv) real-world deployment of foundation model including domain-specific adaptations.


## Syllabus 

| Date | Topic |
|-----|------|
| W1 - 09/03, 09/05  | Introduction and Logistics [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%201%20-%20Introduction%20and%20Logistics.pdf) & Stochastic Gradient Descent |
| W2 - 09/10, 09/12  | Auto-Differentiation & Nvidia GPU Computation and Communication |
| W3 – 09/17, 09/19  | Transformer Architecture & Large-scale Pretrain Overview |
| W4 - 09/24, 09/26  | Data-, Pipeline- Parallelism & Tensor Model-, Optimizer- Parallelism |
| W5 - 10/03         | Generative Inference Overview |
| W6 - 10/08, 10/10  | Alogirhtm Optimizations for Inference & System Optimizations for Inference |
| W7 - 10/15, 10/17  | Retrivial Augument Generation & LLM Agent for Domain Specific Areas | 
| W8 - 10/22, 10/24  | Presentation Sessions |
| W9 – 10/29, 10/31  | Presentation-Sessions |
| W10 - 11/05, 11/07 | Presentation-Sessions |
| W11 - 11/12, 11/14 | Presentation-Sessions |
| W12 - 11/19, 11/21 | Presentation-Sessions |
| W13 - 11/26, 11/28 | Presentation Sessions |

## Grading

- Course Report (70%):
  - Literature review (50%):
    - Cover the relevant techniques exhaustively. (10%) 
    - Understand the relevant techniques correctly. (15%)
    - Organize the techniques using good categorization. (15%) 
    - The report is written in professional academic English. (10%)
    - Page limits: 4 pages in NeurIPS template (excluding reference). 
  - Research plan (20%):
    - The proposed research plan is executable. (10%)
    - The proposed research plan includes novelty and concrete design. (10%) 
    - Page limits: 4 pages in NeurIPS template (excluding reference).
- In-class Presentation (30%), including literature review only:  
  - Clearly organize the material and present the problem definition, related work, and methodology appropriately. (20%)
  - Can answer the questions from the lecturers and other students appropriately. (5%)
  - Submit short feedback for all the other presentation sessions. (5%) 
  - (Other student feedback determines 70% of the grades for this part.)

## Topics for Literature Review:

- [Topics](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/topics.md). 


