---
title: "The Labyrinth of Links: Navigating the Associative Maze of Multi-modal LLMs"
collection: publications
category: conferences
permalink: /publication/2024-paper-title-number-4
excerpt: 'In this paper, we introduce a benchmark to evaluate association, a core yet underexplored aspect of human intelligence. We construct adjective- and verb-based tasks using an annotation-free method and propose three association levels: single-step, synchronous, and asynchronous. Extensive zero-shot evaluations reveal that current MLLMs, including GPT-4V, perform significantly worse than humans. Our benchmark offers a new direction for advancing MLLM research.'
date: 2024
venue: 'ICLR, 2025'
paperurl: 'https://arxiv.org/pdf/2410.01417'
cite
---

Multi-modal Large Language Models (MLLMs) have exhibited impressive capability. However, recently many deficiencies of MLLMs have been found compared to human intelligence, e.g., hallucination. To drive the MLLMs study, the community dedicated efforts to building larger benchmarks with complex tasks. In this paper, we propose benchmarking an essential but usually overlooked intelligence: association, a human's basic capability to link observation and prior practice memory. To comprehensively investigate MLLM's performance on the association, we formulate the association task and devise a standard benchmark based on adjective and verb semantic concepts. Instead of costly data annotation and curation, we propose a convenient annotation-free construction method transforming the general dataset for our association tasks. Simultaneously, we devise a rigorous data refinement process to eliminate confusion in the raw dataset. Building on this database, we establish three levels of association tasks: single-step, synchronous, and asynchronous associations. Moreover, we conduct a comprehensive investigation into the MLLMs' zero-shot association capabilities, addressing multiple dimensions, including three distinct memory strategies, both open-source and closed-source MLLMs, cutting-edge Mixture-of-Experts (MoE) models, and the involvement of human experts. Our systematic investigation shows that current open-source MLLMs consistently exhibit poor capability in our association tasks, even the currently state-of-the-art GPT-4V(vision) also has a significant gap compared to humans. We believe our benchmark would pave the way for future MLLM studies. Our data and code are available at: [this https URL](https://mvig-rhos.com/llm_inception).
