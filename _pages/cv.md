---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


## Technical Focus Areas

I am an AI/ML Engineer and Researcher with over five years of combined experience in industrial software engineering and applied machine learning research. My work bridges AI research and practical software engineering, with a focus on developing, evaluating, and integrating machine learning solutions into real-world applications.

I have four years of professional experience at Basler AG, where I developed computer vision software, image processing algorithms, and industrial vision systems using C++, Python, OpenCV, and modern software engineering practices. My experience includes performance optimization, automated testing, CI/CD, and cloud-based development workflows.

My research background spans deep learning, computer vision, medical image analysis, self-supervised learning, and transfer learning. Through research collaborations with academic institutions, I work on adapting foundation models to specialized domains, including medical image segmentation and classification, using techniques such as fine-tuning, LoRA, and parameter-efficient learning (PEFT).

Beyond computer vision, I am interested in large language models (LLMs), retrieval-augmented generation (RAG), agentic AI, and machine learning systems, exploring how modern AI methods can be translated into reliable and useful applications.

My broader interests lie at the intersection of machine learning research, AI engineering, and scalable software systems, with an emphasis on connecting scientific advances to practical applications.

## Education


**Otto-von-Guericke University (OVGU) Magdeburg** | GPA: 1.9 (German scale, 1.0 is best)  —  Magdeburg, Germany
Master of Science, Medical Systems Engineering.   —  Graduation Date: 03/2021
Relevant Courses: Methods of Magnetic Resonance Imaging (MRI),
Visualization,
Computer-Assisted Surgery, Human-Computer Interfaces, Digital Information Processing, Computed Tomography (CT) Lab
Thesis: Quantification of the Improvement due to Transfer Learning in Segmentation of Neuromelanin-enriched Brain Structures | Advisor: Max Dünnwald

**Azad University, Science And Research Branch** | GPA: 16.45/20 (Iranian grading)  —  Tehran, Iran
Bachelor of Science, Biomedical Engineering (bioelectric)  —  Graduation Date: 11/2015
Relevant Courses: Image Processing, Algorithmic Computation
Thesis: Intravascular Ultrasound (IVUS) image generation by using Field II simulation method | Advisor: Prof. Seyed Kamaledin Setarehdan

## Publications


**T. Bahador**, M. Dünnwald, M. J. Betts, E. Düzel, S. Oeltze-Jafra, “Investigating the Benefit of Transfer Learning from the Locus Coeruleus for Substantia Nigra Pars Compacta Segmentation,” Submitted to IEEE International Symposium on Biomedical Imaging (ISBI 2027), under review ([Manuscript](https://taybh.github.io/assets/papers/ISBI_Paper_preprint.pdf)).

## Research Experience


**Research Collaborator  | Biomedical AI Research Lab (BAIR), UCLA ([GitHub](https://github.com/Taybh/corneal-diseases-classification))**  —  Remote | 06/2026 – Present
- Developing and benchmarking deep learning approaches for corneal disease classification using AS-OCT pachymetry maps.
- Developed an annotation tool, established labeling criteria in consultation with an ophthalmologist to address the lack of labeled data, and manually labeled AS-OCT images.
- Trained and evaluated a ConvNeXt classifier, achieving 94% classification accuracy, exploring approaches to scale annotation and classification across thousands of unlabeled AS-OCT images.

**Research Collaborator | OVGU and Human Technopole ([GitHub](https://github.com/Taybh/vessel-segmentation))**  —  Remote | 04/2026 – Present
- Investigating foundation models (SAM, MedSAM, and MedicoSAM) for medical vessel segmentation, using parameter-efficient fine-tuning methods (LoRA and adapters) for domain adaptation in low-data medical imaging settings.
- Developing reproducible GPU-accelerated PyTorch pipelines, evaluating segmentation performance across training configurations and loss functions, with a focus on transferability and domain robustness. **Supervisor:** [Dr. Soumick Chatterjee](https://www.linkedin.com/in/soumick/)

**Research Assistant | Medicine and Digitalization Group, Department of Neurology, University Hospital & German Center for Neurodegenerative Diseases (DZNE)** —  Magdeburg, Germany | 11/2020 – 03/2021
- Developed and designed experimental baselines for transfer learning in the segmentation of the locus coeruleus (LC) in MRI images, and contributed to segmentation workflows by annotating LC and substantia nigra pars compacta(SNpc) using radiology protocols and ITK-SNAP, supporting DZNE collaboration.

**Research Assistant | Max Planck Institute for Dynamics of Complex Technical Systems** — Magdeburg, Germany | 05/2020 – 08/2020
- Implemented cutting-edge convolutional neural networks (CNNs) and deep learning algorithms in super-resolution, enabling improvements of visual fidelity and detail reconstruction in non-medical data.

**Research Assistant | Medicine and Digitalization Group, Department of Neurology, University Hospital** — Magdeburg, Germany | 05/2019 – 01/2020
- Implemented state-of-the-art deep learning models in super-resolution and data imputation, in order to enhance the resolution of MRI scans, enabling more precise visualization and analysis.
- Mentored new students in the group in Linux workflows and Python programming.

## Industry Experience


**Software Engineer | Basler AG**  —  Ahrensburg, Germany | 05/2021 – 03/2025
- Developed image processing and embedded C++ computer vision modules, known as "vTools", and delivered web-based machine vision solutions, using Docker-based development, both on-premises and cloud training pipelines, CI/CD integration, and unit testing for production-grade deployment.

**Intern | Basler AG - R&D Department**  —  Ahrensburg, Germany | 12/2020 – 03/2021
- Designed and developed self-supervised and semi-supervised learning pipelines for industrial image classification, using Unsupervised Data Augmentation (UDA), considering constraints on an FPGA, to reduce labeling requirements.
- Improved test accuracy by up to 5% over the baseline self-supervised approach, achieving 85% accuracy with only 2,000 labeled images, compared with 90% using 50,000 labeled images in fully supervised learning.

**R&D Marketing Expert | Pooyandegan Rah Saadat**  —  Tehran, Iran | 12/2014 – 11/2015
- Worked with medical doctors and R&D teams during various surgeries to evaluate clinical requirements for new medical device modules and integrate feedback into development.

## Fellowships & Selected Programs


**Silicon Valley Fellowship [[Certificate](https://taybh.github.io/assets/certificates/SILICON_VALLEY_FELLOWSHIP_certificate.png)]**  —  San Francisco, United States | 10/2025
- Selected for a competitive international fellowship (4% acceptance rate), gaining exposure to Silicon Valley’s innovation and entrepreneurship ecosystem through engagement with founders, investors, and researchers.

## Projects


**Multilingual LLM Guardrail Benchmark, AI Safety & Alignment Evaluation | Personal Project ([GitHub](https://github.com/Taybh/multilingual-llm-guardrail-benchmark))**
- Built a Python benchmark to evaluate LLM safety guardrails across English, German, and Persian, comparing multiple approaches against harmful requests, prompt injection, and jailbreak attempts.

**RAG Policy Assistant | Personal Project (LLM Systems) ([GitHub](https://github.com/Taybh/rag-policy-assistant))**
- Built a retrieval-augmented generation system for enterprise policy question answering using Dense Passage Retrieval (DPR), FAISS vector search, and GPT-2 generation, and designed semantic retrieval pipelines for document grounding and low-latency question answering over internal knowledge bases.

**Multi-Agent NLP Chatbot | Personal Project (Agentic AI) ([GitHub](https://github.com/Taybh/multi-agent-nlp-chatbot))**
- Built a modular multi-agent chatbot with retrieval-based NLP, query routing, shared memory, and API integration, and implemented PDF-based question answering using TF-IDF retrieval and cosine similarity, with context-aware memory for multi-turn interactions.

**Quantification of the Improvement due to Transfer Learning in Segmentation of Neuromelanin-enriched Brain Structures (master thesis - ([script](https://taybh.github.io/assets/projects/master_thesis.pdf))) | OVGU **  —  Magdeburg, Germany | 06/2020 – 10/2020
- Developed and evaluated 3D U-Net models for segmentation of the locus coeruleus and substantia nigra pars compacta in neuromelanin-sensitive MRI.
- Compared inter-region transfer learning strategies against training from scratch across varying numbers of labeled subjects.
- Found that transfer learning did not significantly outperform scratch-trained baselines, even with as few as five labeled subjects.

**Smart walking aid for people with vision problem ([link](https://onurgulkokan6.wixsite.com/canebox)) | OVGU**  —  Magdeburg, Germany | 04/2018 – 07/2018
- Developed in a four‑member multidisciplinary team, CaneBox won both the Best Team Award and the Best Design award at Otto von Guericke University Magdeburg 2018. Currently rebuilding using embedded deep learning methods.

**IVUS Image Generation by using Field II simulation method(Bachelor thesis)**  —  Tehran, Iran

**Azad University**  —  10/2014 – 11/2015
- Generated intravascular ultrasound phantoms based on Finite Element and Field II methods

## Skills & Interests

**Programming:** Python, PyTorch, TensorFlow, Pandas, NumPy, scikit-learn, C++, Qt/QML, MATLAB, SQL, HTML, CSS
**ML & Vision:** CNNs, LLM, RAG, Transformers, Foundation Models, Prompt Engineering, Segmentation, Transfer Learning, Self-Supervised Learning, Fine-Tuning.
**Tools:** Docker, Git, Linux, OpenCV, Jupyter Notebook, Unittest, CUDA, Halcon, ITK-SNAP
**Cloud & DevOps:** cloud-based training workflows, AWS, Azure, CI/CD, Terraform
**Management & Documentation:** Atlassian (Confluence, Jira), Agile Methodologies (Agile Scrum, Kanban), LaTeX, Hugo
**Language:** English (Business fluency-C1), German (B2), Persian (Native), Arabic (A2)
**Interests:** Playing violin, Group dancing, Fitness / Weightlifting

## Honors & awards


**Best design award**, OVGU ("Smart Walking Aid" project)[[Certificate](https://taybh.github.io/assets/certificates/BEST_DESIGN_AWARD.png)] —  Magdeburg, Germany | 07/2018

**Best team award**, OVGU ("Smart Walking Aid" project)[[Certificate](https://taybh.github.io/assets/certificates/Best_team_award.png)] —  Magdeburg, Germany | 07/2018

## Licenses & Certificates

- [Future of AI](https://bluedot.org/certification?id=recDBN1qpXIV1QSvE), [AGI Strategy](https://bluedot.org/certification?id=recexsB59KtFEzjbw), [Technical AI Safety](https://bluedot.org/certification?id=recpP1x2fc2x4CsgT) - BlueDot Impact
- Entrepreneurship - Wharton Online
- German B2 - telc GmbH - The European Language Certificates

## Teaching, Mentorship & Outreach


**Speaker | INNOVATE Decentral, Hamburg**	 —  Germany | 04/2025 – Present
Delivered talks on innovation, entrepreneurship, and career development in technology for students and early-career engineers.

**Technology Content Creator** Created multilingual (EN/DE/FA) educational content on technology across multiple digital platforms  —  04/2025 – Present

**Physics Tutor & Teaching Assistant**  —  Tehran, Iran | 07/2011 – 06/2012 Tutored high school students in physics, graded exams, and contributed detailed examples and solutions to a physics textbook.


<!--  
Teaching
====== 

<div style="display: flex; justify-content: space-between;">
  <span>High School Physics Tutor & Teaching Assistant</span>
  <span>Jul 2011 - Jun 2012</span>
</div>

<p>
• Tutored high school students in physics, reinforcing core concepts and helping improve academic performance.
<br>• Supported my former teacher post-graduation by reviewing and grading student exam papers.
<br>• Contributed to the development of his book in physics, by writing detailed example solutions and supporting content.
</p>
-->