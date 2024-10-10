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
| W1 - 09/03, 09/05  | Introduction and Logistics [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%201%20-%20Introduction%20and%20Logistics.pdf) & Stochastic Gradient Descent [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%202%20-%20Stochastic%20Gradient%20Descent.pdf)|
| W2 - 09/10, 09/12  | Auto-Differentiation [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%203%20-%20Automatic%20Differentiation.pdf) & Nvidia GPU Computation and Communication [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%204%20-%20Nvidia%20GPU%20Computation%20and%20Communication.pdf)|
| W3 – 09/17, 09/19  | LLM Pretraining [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%205%20-%20LLM%20Pretraining.pdf) & Data-, Pipeline- Parallelism [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%206%20-%20Data%20and%20Pipeline%20Parallel%20Training.pdf) |
| W4 - 09/24, 09/26  | Tensor Model-, Optimizer- Parallelism [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%207%20-%20Tensor%20Model%20and%20Optimizer%20Parallel%20Training.pdf) & LLM Tuning and Utilization [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%208%20-%20LLM%20Tuning%20and%20Utilization.pdf) |
| W5 - 10/03         | Generative Inference Overview [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%209%20-%20Generative%20Inference%20Overview.pdf) |
| W6 - 10/08, 10/10  | Alogirhtm Optimizations for Inference [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%2010%20-%20Generative%20Inference%20Algorithm%20Optimization.pdf) & System Optimizations for Inference [[Slides]](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/Lecture%209%20-%20Generative%20Inference%20Overview.pdf) |
| W7 - 10/15, 10/17  | RAG and Domain Specific LLM Agent & Review | 
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

- [Topics and Reference](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/topics.md), [Topic Assignment](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/topic_assignment.md), [Presentation Schedule](https://github.com/Relaxed-System-Lab/COMP6211J_Course_HKUST/blob/main/presentation_schedule.md). 


