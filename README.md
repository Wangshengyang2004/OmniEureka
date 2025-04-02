# OmniEureka
Omni-EUREKA represents a revolutionary approach leveraging large language models (LLMs) and vision-language models (VLMs) to automatically optimize reinforcement learning (RL) code through iterative rewriting and simulation-based performance feedback. Starting from baseline RL tasks (e.g., hover tasks), Omni-EUREKA transforms the codebase iteratively to achieve advanced functionalities like trajectory tracking, agile maneuvers, and multi-agent cooperation. We hope Omni-EUREKA can provide a new perspective on the ability of LLMs to optimize RL code.

## Updates
1. Looking for collaboration. If you're interested in this idea, please contact me through my email: shengyang.wang2004@gmail.com
2. ...

## Upgrade compare to NVIDIA's EUREKA
1. NVIDIA's EUREKA is a great work. It provides a good baseline for the research of RL. However, it requires a lot of manual work and reward experts to design the reward function as a baseline for comparison. The termination conditions would also require human design. Moreover, EUREKA's interesting idea of Human-in-the-Loop (RLHF) is good but not perfect.
2. Thus we want to upgrade EUREKA to a new level. First, the LLM agents will be able to design the whole code, not only the reward function. This will introduce great flexibility and diversity. Second, Omni-EUREKA will be able to start from a baseline code (e.g., hover task for crazyflie as shown in the IsaacLab repo) and then iteratively improve the code. Third, we will engage a VLM to understand the training results (the video during evaluation) and provide feedback like the RLHF method.
3. ...

## Three Innovative Points

1. **Iterative Code Transformation via LLMs**
   - **Core Concept:** Employ detailed natural language prompts to enable LLM-driven code modifications, dynamically adjusting RL tasks by altering reward functions, state definitions, and control algorithms based on performance feedback.
   - **Innovation Value:** This process substantially accelerates RL development, reducing manual coding effort while allowing automated exploration of advanced control strategies and diverse task functionalities.
2. **Feedback-Driven Simulation Loop**
   - **Core Concept:** Execute automatically transformed RL code within simulation environments (IsaacLab), capturing key performance metrics to guide subsequent iterations of LLM-driven code refinements.
   - **Innovation Value:** Rapid convergence and higher-quality RL policies result from real-time, data-driven feedback loops, significantly outperforming traditional manual trial-and-error methods.
3. **Automated Discovery of Innovative Control Strategies**
   - **Core Concept:** Enable LLM-generated code modifications to identify and adopt unconventional yet effective strategies through iterative cycles informed by simulation performance analytics.
   - **Innovation Value:** LLM-driven innovation results in unique, high-performing control solutions, potentially surpassing human-engineered policies, enhancing both efficiency and adaptability.


## Citation
If you find this work useful, please consider citing:

```bibtex
@misc{omnieureka2024,
  author = {Shengyang Wang},
  title = {Omni-EUREKA: Automated Reinforcement Learning Code Optimization via Large Language Models and Vision-Language Models},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/Wangsgyang2004/OmniEureka}}
}
```

Or in plain text:
Shengyang Wang. (2025). Omni-EUREKA: Automated Reinforcement Learning Code Optimization via Large Language Models [Computer software]. GitHub. https://github.com/Wangsgyang2004/OmniEureka


