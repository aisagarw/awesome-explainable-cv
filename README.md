# Awesome Explainable Computer Vision Papers 📚

A curated list of research papers focused on explainable methods in computer vision, ranging from saliency maps to concept-based explanations and beyond. The goal is to gather key papers that contribute to transparency and interpretability in machine learning models, particularly in the context of visual data.

### Table of Contents
1. [Surveys and Reviews](#surveys-and-reviews)
2. [Saliency Methods](#saliency-methods)
3. [Concept-Based Explanations](#concept-based-explanations)
4. [Contrastive Explanations](#contrastive-explanations)
5. [Causal Explanations](#causal-explanations)
6. [Visual Question Answering (VQA)](#visual-question-answering)
7. [Datasets and Benchmarks](#datasets-and-benchmarks)
8. [Applications](#applications)
9. [Resources](#resources)

---

### Surveys and Reviews
- **"Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities, and Challenges toward Responsible AI"**  
  Authors: Arrieta et al.  
  Conference: IJCAI 2020  
  [Link](https://arxiv.org/abs/1910.10045)  
  _Summary:_

- **"Explainable AI for Interpretable and Transparent Machine Learning Models: A Review"**  
  Authors: Tjoa and Guan  
  Conference: Expert Systems with Applications 2020  
  [Link](https://www.sciencedirect.com/science/article/pii/S1566253520308285)  
  _Summary:_

---

### Saliency Methods
- **"Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization"**  
  Authors: Selvaraju et al.  
  Conference: ICCV 2017  
  [Link](https://arxiv.org/abs/1610.02391)  
  _Summary:_

- **"SmoothGrad: removing noise by adding noise"**  
  Authors: Smilkov et al.  
  Conference: ICLR 2017  
  [Link](https://arxiv.org/abs/1706.03825)  
  _Summary:_

---

### Concept-Based Explanations

@misc{,
   abstract = {Concept-based interpretability addresses the opacity of deep neural networks by constructing an explanation for a model's prediction using high-level units of information referred to as concepts. Research in this area, however, has been mainly focused on image and graph-structured data, leaving high-stakes tasks whose data is tabular out of reach of existing methods. In this paper, we address this gap by introducing the first definition of what a high-level concept may entail in tabular data. We use this definition to propose Tabular Concept Bottleneck Models (TabCBMs), a family of interpretable self-explaining neural architectures capable of learning high-level concept explanations for tabular tasks. As our method produces concept-based explanations both when partial concept supervision or no concept supervision is available at training time, it is adaptable to settings where concept annotations are missing. We evaluate our method in both synthetic and real-world tabular tasks and show that TabCBM outperforms or performs competitively compared to state-of-the-art methods, while providing a high level of interpretability as measured by its ability to discover known high-level concepts. Finally, we show that TabCBM can discover important high-level concepts in synthetic datasets inspired by critical tabular tasks (e.g., single-cell RNAseq) and allows for human-in-the-loop concept interventions in which an expert can identify and correct mispredicted concepts to boost the model's performance.},
   author = {Mateo Espinosa Zarlenga and Zohreh Shams and Michael Edward Nelson and Been Kim and Google Deepmind and Mateja Jamnik},
   title = {TabCBM: Concept-based Interpretable Neural Networks for Tabular Data},
}


- **"TCAV: TabCBM: Concept-based Interpretable Neural Networks for Tabular Data"**  
  Authors: Mateo Espinosa Zarlenga and Zohreh Shams and Michael Edward Nelson and Been Kim and Google Deepmind and Mateja Jamnik
  Conference: [TMLR 2024](https://openreview.net/pdf?id=TIsrnWpjQ0)
  _Summary:_ Propose Tabular Concept Bottleneck Models (TabCBMs), a family of interpretable self-explaining neural architectures capable of learning high-level concept explanations for tabular tasks

  
- **"TCAV: Concept-based explanations by testing with concept activation vectors"**  
  Authors: Kim et al.  
  Conference: ICML 2018  
  [Link](https://arxiv.org/abs/1711.11279)  
  _Summary:_

- **"Interpretable and Editable Concept Reasoning"**  
  Authors: Yeh et al.  
  Conference: NeurIPS 2019  
  [Link](https://arxiv.org/abs/1912.01098)  
  _Summary:_

---

### Contrastive Explanations
- **"Explaining Deep Neural Networks with a Conceptualized Contrastive Explanation"**  
  Authors: Dhurandhar et al.  
  Conference: AISTATS 2018  
  [Link](https://arxiv.org/abs/1802.07623)  
  _Summary:_

---

### Causal Explanations
- **"Causal Interpretability for Machine Learning – Problems, Methods, and Evaluation"**  
  Authors: Pawelczyk et al.  
  Conference: NeurIPS 2020  
  [Link](https://arxiv.org/abs/2012.14545)  
  _Summary:_

- **"On the Relationship Between Explanation and Prediction: A Causal View"**  
  Authors: Amir-Hossein Karimi, Krikamol Muandet, Simon Kornblith, Bernhard Schölkopf, Been Kim  
  Conference: NeurIPS 2022  
  [Link](http://arxiv.org/abs/2212.06925)  
  _Summary:_

---

### Visual Question Answering
- **"Self-Critical Reasoning for Robust Visual Question Answering"**  
  Authors: Wu et al.  
  Conference: NeurIPS 2019  
  [Link](https://arxiv.org/abs/1912.08600)  
  _Summary:_

---

### Datasets and Benchmarks
- **"CUB-200-2011 Birds Dataset"**  
  Description: A popular dataset for fine-grained image classification with concept annotations used for explainability research.  
  [Link](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)  
  _Summary:_

---

### Applications
- **"XAI in Medical Imaging"**  
  Authors: Lundervold and Lundervold  
  Conference: Frontiers in Neuroscience 2019  
  [Link](https://www.frontiersin.org/articles/10.3389/fnins.2019.00518/full)  
  _Summary:_

---

### Resources
- **Code Repositories**  
  - [Grad-CAM Implementation (Pytorch)](https://github.com/jacobgil/pytorch-grad-cam)
  - [TCAV Implementation (Tensorflow)](https://github.com/tensorflow/tcav)

- **Related Awesome Lists**
  - [Awesome Explainable AI (XAI)](https://github.com/wangyongjie-ntu/Awesome-XAI)

---

## Contributions
Feel free to contribute! If you have found any important paper that you think belongs here, create a pull request or open an issue.

---
