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

- **"Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)"**  
    **Authors**: _Been Kim, Martin Wattenberg, Justin Gilmer, Carrie Cai, James Wexler, Fernanda Viegas, Rory Sayres_ <br>
    **Conference**: [ICML 2018](https://arxiv.org/pdf/1711.11279) <br>
    **Summary**: _Uses directional derivatives to quantify the degree to which a user-defined concept is important to a classification result–for example, how sensitive a prediction of zebra is to the presence of stripes._

- **"Towards Automatic Concept-based Explanations"**  
    **Authors**: _Amirata Ghorbani, James Wexler, James Zou, Been Kim_ <br>
    **Conference**: [NeurIPS 2019](https://proceedings.neurips.cc/paper_files/paper/2019/file/77d2afcb31f6493e350fca61764efb9a-Paper.pdf)  <br>
    **Summary**: _Automatically discovers concepts by segmenting the image at various resolutions so as to obtain concepts at all hierarchies and clustering similar segments as examples of the same concept. Next use any method like TCAV to explain the relevance of these discovered concepts._

- **"Concept Bottleneck Models"**  
    **Authors**: _Pang Wei Koh, Thao Nguyen, Yew Siang Tang, Stephen Mussmann, Emma Pierson, Been Kim, Percy Liang_ <br>
    **Conference**: [PMLR 2020](https://proceedings.mlr.press/v119/koh20a/koh20a.pdf)  <br>
    **Summary**: _First predicts concepts that are provided at training time, and then uses these concepts to predict the label. By construction, one can intervene on these concept bottleneck models by editing their predicted concept values and propagating these changes to the final prediction. No automated way proposed, but provides insights into how test-time concept intervention by domain experts can potentially help correcting incorrect predictions._

- **"GlanceNets: Interpretabile, Leak-proof Concept-based Models"**  
    **Authors**: _Emanuele Marconato, Andrea Passerini, Stefano Teso_ <br>
    **Conference**: [CRL 2022](https://arxiv.org/pdf/2205.15612)  <br>
    **Summary**: _Questions the interpretability of the concepts defined in classic CBMs and a propose clear definition of interpretability in terms of
alignment between the model’s representation and an underlying data generation process._




- **"TabCBM: Concept-based Interpretable Neural Networks for Tabular Data"**  
    **Authors**: _Mateo Espinosa Zarlenga, Zohreh Shams, Michael Edward Nelson, Been Kim, Google Deepmind, Mateja Jamnik_ <br>
    **Conference**: [TMLR 2024](https://openreview.net/pdf?id=TIsrnWpjQ0)  <br>
    **Summary**: _Propose Tabular Concept Bottleneck Models (TabCBMs), a family of interpretable self-explaining neural architectures capable of learning high-level concept explanations for tabular tasks._
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
