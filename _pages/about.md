---
permalink: /
title: "Rishi Shah"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm **Rishi Shah**, a **Master's student in Machine Learning** at **Carnegie Mellon University**. Currently, I'm working with [Prof. Aditi Raghunathan](https://www.cs.cmu.edu/~aditirag/) on enhancing reasoning abilities in Vision Language Models (VLMs), aiming to bridge gaps in multimodal agent performance. My recent work includes developing adversarial attacks and improving the robustness of multi-modal closed-weight agents, with a paper submitted to **ICLR'25**.

Before CMU, I was part of the **Generative AI team at Samsung Headquarters** in South Korea, where I developed fine-tuned LoRA models for Samsung's Stable Diffusion, tailoring image generation to user preferences. I also implemented a retrieval-augmented generation (RAG) application to provide conversational responses from e-manual PDFs.

I graduated from **IIT-Delhi** in 2023 with a B.Tech in **CSE** and a **CGPA of 9.564**. I achieved **AIR 75** in JEE Advanced 2019 and **AIR 157** in JEE Mains 2019. During my undergrad, I collaborated with [Prof. Sayan Ranu](https://www.cse.iitd.ac.in/~sayan/) and [Prof. Sourav Medya](https://souravmedya.github.io/) on my thesis, NEUROCUT, a novel GNN-based method for graph cut extraction. My other research includes multi-agent reinforcement learning with [Prof. Rajeev Shorey](https://www.rajeevshorey.com/) and crop price forecasting with [Prof. Aditeshwar Seth](https://www.cse.iitd.ac.in/~aseth/).

With a strong passion for **multimodals, computer vision, NLP, RL, and GNN**, I am driven to contribute to AI and ML research, focusing on developing intelligent, multimodal agents that enhance human efficiency and convenience.  

Please feel free to reach out—I’m always open to collaborations and discussions!

# Education

## Masters in Machine Learning
**Carnegie Mellon Univeristy** 
*August 2024 - Present*

## Bachelors in Computer Science
**IIT-Delhi**  
*July 2019 - May 2023*


# Work Experience

## Samsung Electronics, South Korea
**Research Engineer, Generative AI Team**  
*September 2023 - August 2024*
- Fine-tuned Samsung Gauss-i using LORA and Dreambooth for generating themed images for TV background.
- Generated text-to-image datasets using prompt engineering and SDXL, filtered using CLIPScore and OpenCV tools.
- Leveraging LLMs using Retrieval-Augmented Generation improving user experience on Bixby(AI bot).
- Developing and rigorous testing Samsung Research’s LLM, identified various hallucinations in the model.

**Research Associate, Visual Display, AI**  
*May 2022 - July 2022*
- Designed supervised Time Series and unsupervised Clustering model to predict television replacement.
- Incorporated Key Performance Indicators from sensors with RFM values to improve performance by 6%.

## KnowDis, Delhi
**Data Science Intern, Query Search and Recommendation Engine**  
*May 2021 - July 2021*
- Worked on a multi-classification problem, fine-tuned fastText model to generate word embeddings.
- Implemented a framework using faiss and annoy libraries to optimize nearest neighbor search for query embedding.
- Built a scalable architecture where batch of queries took 55 secs compared to baseline’s 140 mins.


<br>

# Publications and Preprints


### Dissecting Adversarial Robustness of Multimodal LM Agents  
**ICLR'25(Under Review), [Prof. Aditi Raghunathan](https://www.cs.cmu.edu/~aditirag/)**  
*[May-Oct 2024]*  
- Introduced the **ARE** framework to analyze adversarial robustness in **multimodal language model agents**.  
- Demonstrated imperceptible image perturbations (<5% pixels) could achieve targeted attacks with a **67% success rate**.  
- Quantified component impact, showing **evaluators** and **value functions** reduce ASR while vulnerabilities increase ASR.  
- [GitHub Repository](https://github.com/rishi1001/agent_attack)


## NEUROCUT : Neural Approach for Robust Graph Partitioning
**KDD’24, Prof. Sayan Ranu**  
*[Jul 2022 - Jun 2023]*
- Designed a novel GNN based inductive architecture to find near-optimal solutions of cut related NP-hard problems.
- Modelled an RL based auto-regressive framework using policy gradient methods to find the optimal partitions.
- Developed framework generalizes to any cut objective and specified number of partitions, outperforming all baselines.

## Packet Routing using Multi-Agent Reinforcement Learning
**COMSNETS’23, Prof. Rajeev Shorey**  
*[Jan-July 2022]*
- Trained DDQNs for routing IoT data transmitted by a UAV network by implementing Multi-Agent RL.
- Formulated a novel cross-agent reward function to achieve 48.7% throughput gain over baselines.

## Price Forecasting of Agricultural Commodities
**COMPASS’23, Prof. Aaditeshwar Seth**  
*[Mar-Nov 2021]*
- Built short-term price forecasting model for Cotton, Soybean prices using Temporal Convolutional Networks.
- Generated a spectrum of price predictions with associated confidence which outperformed baseline 74% of the time.

