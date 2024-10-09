# Awesome Explainable Computer Vision Papers 📚

A curated list of research papers focused on explainable methods in computer vision, ranging from saliency maps to concept-based explanations and beyond. The goal is to gather key papers that contribute to transparency and interpretability in machine learning models, particularly in the context of visual data.

## Table of Contents
1. [Surveys and Reviews](#surveys-and-reviews)
2. [Saliency Methods](#saliency-methods)
3. [Attribution Methods](#attribution-methods)
4. [Concept-Based Explanations](#concept-based-explanations)
5. [Contrastive Explanations](#contrastive-explanations)
6. [Causal Explanations](#causal-explanations)
7. [Visual Question Answering (VQA)](#visual-question-answering)
8. [Datasets and Benchmarks](#datasets-and-benchmarks)
9. [Libraries & Tools](#libraries-and-tools)
10. [Applications](#applications)
11. [Tutorials & Courses](#tutorials-and-courses)
12. [Resources](#resources)

---

## Surveys and Reviews
- **"Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities, and Challenges toward Responsible AI"**  
  Authors: Arrieta et al.  
  Year: 2020  
  [Link](https://arxiv.org/abs/1910.10045)

- **"Explainable AI for Interpretable and Transparent Machine Learning Models: A Review"**  
  Authors: Tjoa and Guan  
  Year: 2020  
  [Link](https://www.sciencedirect.com/science/article/pii/S1566253520308285)

---

## Saliency Methods
- **"Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization"**  
  Authors: Selvaraju et al.  
  Year: 2017  
  [Link](https://arxiv.org/abs/1610.02391)

- **"SmoothGrad: Removing Noise by Adding Noise"**  
  Authors: Smilkov et al.  
  Year: 2017  
  [Link](https://arxiv.org/abs/1706.03825)

- **"Full-Gradient Representation for Neural Network Visualization"**  
  Authors: Srinivas, et al.  
  Year: 2019  
  [Link](https://arxiv.org/abs/1905.00780)

---

## Attribution Methods
- **"SHAP: A Unified Approach to Interpreting Model Predictions"**  
  Authors: Lundberg, Lee  
  Year: 2017  
  [Link](https://arxiv.org/abs/1705.07874)

- **"LIME: Local Interpretable Model-agnostic Explanations"**  
  Authors: Ribeiro et al.  
  Year: 2016  
  [Link](https://arxiv.org/abs/1602.04938)

---

## Concept-Based Explanations
- **"TCAV: Concept-based explanations by testing with concept activation vectors"**  
  Authors: Kim et al.  
  Year: 2018  
  [Link](https://arxiv.org/abs/1711.11279)

- **"ACE: Automatic Concept-based Explanations"**  
  Authors: Ghorbani et al.  
  Year: 2019  
  [Link](https://arxiv.org/abs/1902.03129)

---

## Contrastive Explanations
- **"Explaining Deep Neural Networks with a Conceptualized Contrastive Explanation"**  
  Authors: Dhurandhar et al.  
  Year: 2018  
  [Link](https://arxiv.org/abs/1802.07623)

---

## Causal Explanations
- **"Causal Interpretability for Machine Learning – Problems, Methods, and Evaluation"**  
  Authors: Pawelczyk et al.  
  Year: 2020  
  [Link](https://arxiv.org/abs/2012.14545)

- **"Interpretable and Counterfactual Explanations"**  
  Authors: Wachter et al.  
  Year: 2017  
  [Link](https://arxiv.org/abs/1703.03717)

---

## Visual Question Answering (VQA)
- **"Self-Critical Reasoning for Robust Visual Question Answering"**  
  Authors: Wu et al.  
  Year: 2019  
  [Link](https://arxiv.org/abs/1912.08600)

- **"CLEVR-XAI: A Benchmark Dataset for Explainable Visual Question Answering"**  
  Authors: Johnson et al.  
  Year: 2017  
  [Link](https://cs.stanford.edu/people/jcjohns/clevr/)

---

## Datasets and Benchmarks
- **"CUB-200-2011 Birds Dataset"**  
  Description: A popular dataset for fine-grained image classification with concept annotations used for explainability research.  
  [Link](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)

- **"PASCAL VOC Explanations"**  
  Description: A dataset that provides saliency maps and explanations for object classification tasks.  
  [Link](http://host.robots.ox.ac.uk/pascal/VOC/)

- **"XAI-Bench"**  
  Description: A dataset that provides explanations along with labeled images to benchmark various explainability methods.  
  [Link](https://github.com/ExplainableML/xai-bench)

---

## Libraries & Tools
- **[Grad-CAM++](https://github.com/adityac94/Grad-CAMplusplus)**: An improved version of Grad-CAM with sharper and more accurate visualizations.
- **[LIME](https://github.com/marcotcr/lime)**: A library for generating local, interpretable model-agnostic explanations.
- **[SHAP](https://github.com/slundberg/shap)**: A powerful library that computes SHAP values for interpreting machine learning models.
- **[Captum](https://github.com/pytorch/captum)**: PyTorch's model interpretability library.
- **[Alibi](https://github.com/SeldonIO/alibi)**: A Python library offering algorithms for machine learning model inspection and explanation.

---

## Applications
- **"XAI in Medical Imaging"**  
  Authors: Lundervold and Lundervold  
  Year: 2019  
  [Link](https://www.frontiersin.org/articles/10.3389/fnins.2019.00518/full)

- **"Explainable AI for Autonomous Driving"**  
  Authors: Kim et al.  
  Year: 2018  
  [Link](https://arxiv.org/abs/1812.01761)

---

## Tutorials & Courses
- **[Explainable AI for Computer Vision by IBM](https://www.ibm.com/blogs/research/2020/06/explainable-ai-computer-vision/)**: An introductory guide to understanding and applying XAI techniques in computer vision.
- **[Explainable AI Techniques by Google AI](https://ai.google/explainability/)**: A collection of tools and resources for explainability, including tutorials on Grad-CAM and TCAV.
- **[FastAI’s Interpretable Machine Learning course](https://course.fast.ai/)**: A comprehensive course that includes explainable AI techniques for deep learning models.

---

## Resources
- **Code Repositories**  
  - [Grad-CAM Implementation (PyTorch)](https://github.com/jacobgil/pytorch-grad-cam)
  - [TCAV Implementation (Tensorflow)](https://github.com/tensorflow/tcav)

- **Related Awesome Lists**  
  - [Awesome Explainable AI (XAI)](https://github.com/wangyongjie-ntu/Awesome-XAI)
  - [XAI Libraries & Tools](https://www.restack.io/blog/explainable-ai-libraries)

---

## Contributions
Feel free to contribute! If you have found any important paper that you think belongs here, create a pull request or open an issue.
