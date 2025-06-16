# SDHybridConf
Efficient Intrusion Detection on Edge-IoT with Shallow-Deep Hybrid Fusion Neural Networks

Abstract
This paper presents a novel adaptive Shallow-Deep Hybrid Intrusion Detection System (IDS) tailored for resource-constrained Edge-IoT environments. Unlike prior works that focus solely on accuracy, we introduce the Model Robustness Score (MRS)—a composite evaluation metric that is the first of its kind to holistically measure both detection performance and resource efficiency (CPU, memory, and inference latency), enabling deployment-aware model selection. Our proposed architecture fuses shallow and deep neural models through decision-level strategies, including maximum, subtraction, and weighted averaging, to balance computational cost and accuracy. Experimental results on the UNSW-NB15 dataset demonstrate that our hybrid models—particularly Concat20 and Maximum20 outperform recent hybrid IDS benchmarks, achieving up to 98.2\% accuracy, 0.98 F1-score, and sub-second inference time, while reducing CPU usage by over 30\% compared to standalone deep models. Sensitivity analysis confirms the adaptability of MRS across deployment scenarios such as smart traffic systems, disaster response networks, and V2X communication. This work establishes a scalable, efficient, and deployment-ready IDS framework for real-time Edge-IoT security.

Niranjan W. Meegammana Cyber Security Research Lab Shilpa Sayura Foundation Kandy, Sri Lanka

Harinda Fernando Dept. of Computer Systems Engineering Sri Lanka Institute of Information Technology Malabe, Sri Lanka
