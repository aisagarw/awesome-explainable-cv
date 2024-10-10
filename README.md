# Awesome Explainable Computer Vision Papers 📚

A curated list of research papers focused on explainable methods in computer vision, ranging from saliency maps to concept-based explanations and beyond. The goal is to gather key papers that contribute to transparency and interpretability in machine learning models, particularly in the context of visual data.

### Table of Contents
1. [Surveys and Reviews](#surveys-and-reviews)
2. [Saliency Methods](#saliency-methods)
3. [Concept-Based Explanations](#concept-based-explanations)
4. [Contrastive Explanations](#contrastive-explanations)
5. [Datasets and Benchmarks](#datasets-and-benchmarks)
6. [Applications](#applications)
7. [Resources](#resources)

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

- **"Concept Embedding Models: Beyond the Accuracy-Explainability Trade-Off"**  
    **Authors**: _Mateo Espinosa Zarlenga, Pietro Barbiero, Gabriele Ciravegna, Giuseppe Marra et al._ <br>
    **Conference**: [NeurIPS 2022](https://openreview.net/pdf?id=HXCPA2GXf_)  <br>
    **Summary**: _propose novel concept-based architectures to overcome the accuracy/interpretability pitfalls of classic CBMs (mostly due to incomplete concepts or over-reliance on concepts), thus enabling their deployment in real-world settings where concept annotations are likely to be incomplete._

- **"Concept Activation Regions: A Generalized Framework For Concept-Based Explanations"**  
    **Authors**: _Jonathan Crabbé, Mihaela van der Schaar._ <br>
    **Conference**: [NeurIPS 2022](https://arxiv.org/pdf/2209.11222)  <br>
    **Summary**: _Discusses the assumptions behind existing methods like CAV which assume that the examples illustrating a concept are mapped in a fixed direction of the DNN’s latent space. Relaxes this assumption by allowing concept examples to be scattered across different clusters called concept activation region (CAR)._

- **"VICE: Variational Interpretable Concept Embeddings"**  
    **Authors**: _Lukas Muttenthaler, Charles Y. Zheng, Patrick McClure, Robert A. Vandermeulen, Martin N. Hebart, Francisco Pereira._ <br>
    **Conference**: [NeurIPS 2022](https://arxiv.org/abs/2205.00756)  <br>
    **Summary**: _Method to obtain non-negative representations of object concepts._

- **"Addressing Leakage in Concept Bottleneck Models"**  
    **Authors**: _Marton Havasi, Sonali Parbhoo, Finale Doshi-Velez._ <br>
    **Conference**: [NeurIPS 2022](https://finale.seas.harvard.edu/sites/scholar.harvard.edu/files/finale/files/10494_addressing_leakage_in_concept_.pdf)  <br>
    **Summary**: _Improvement over CBMs on fronts of them having an insufficient concept set and an inexpressive concept predictor._

 - **"Overlooked factors in concept-based explanations: Dataset choice, concept learnability, and human capability"**  
    **Authors**: _Vikram V. Ramaswamy, Sunnie S. Y. Kim, Ruth Fong, Olga Russakovsky._ <br>
    **Conference**: [CVPR 2023](https://arxiv.org/pdf/2207.09615)  <br>
    **Summary**: _Talks about the impact of the probe dataset on generated explanations by concept-based explanation methods, and also highlights that the concepts used in the probing datasets are harder to learn that the corresponding class itself. The authors conclude with some suggestions for improving the quality and usability of concept-based explanations._

 - **"CRAFT: Concept Recursive Activation FacTorization for Explainability"**  
    **Authors**: _Thomas Fel, Agustin Picard, Louis Bethune, Thibaut Boissin, David Vigouroux, Julien Colin, Rémi Cadène, Thomas Serre._ <br>
    **Conference**: [CVPR 2023](https://arxiv.org/pdf/2207.09615)  <br>
    **Summary**: _Method to identify both “what” and “where” by generating concept-based explanation._

- **"Spatial-temporal Concept based Explanation of 3D ConvNets"**  
    **Authors**: _Ying Ji, Yu Wang, Kensaku Mori, Jien Kato._ <br>
    **Conference**: [CVPR 2023](https://arxiv.org/pdf/2206.05275)  <br>
    **Summary**: _3D ACEs._

- **"Learning Bottleneck Concepts in Image Classification"**  
    **Authors**: _Bowen Wang,  Liangzhi Li, Yuta Nakashima, Hajime Nagahara._ <br>
    **Conference**: [CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_Bottleneck_Concepts_in_Image_Classification_CVPR_2023_paper.pdf)  <br>
    **Summary**: _This paper proposes Bottleneck Concept Learner (BotCL), which represents an image solely by the presence/absence of concepts learned through training over the target task without explicit supervision over the concepts. An image is represented solely by the existence of concepts and is classified using them._

- **"Language in a Bottle: Language Model Guided Concept Bottlenecks for Interpretable Image Classification"**  
    **Authors**: _Yue Yang, Artemis Panagopoulou, Shenghao Zhou, Daniel Jin, Chris Callison-Burch, Mark Yatskar._ <br>
    **Conference**: [CVPR 2023](https://arxiv.org/pdf/2211.11158)  <br>
    **Summary**: _Language Guided Bottlenecks (LaBo), leverages a language model to define a large space of possible bottlenecks. Given a problem domain, LaBo uses GPT-3 to produce factual sentences about categories to form candidate concepts. LLM generated sentential concepts can be aligned to images using CLIP, to form a bottleneck layer._

- **"Interpretable Neural-Symbolic Concept Reasoning"**  
    **Authors**: _Pietro Barbiero, Gabriele Ciravegna, Francesco Giannini, Mateo Espinosa Zarlenga et al._ <br>
    **Conference**: [ICML 2023](https://arxiv.org/pdf/2304.14068)  <br>
    **Summary**: _The paper highlights that sota concept-based models rely on high-dimensional concept embedding representations which lack a clear semantic meaning, thus questioning the interpretability of their decision process. They propose a Deep Concept Reasoner (DCR) where neural networks build syntactic rule structures using concept embeddings, but such representations are only used to compute a logic rule. The final prediction is then obtained by evaluating such rules on the concepts’ truth values and not on their embeddings, thus maintaining clear semantics and providing a totally interpretable decision._

- **"Causal Proxy Models for Concept-based Model Explanations"**  
    **Authors**: _Zhengxuan Wu, Karel D'Oosterlinck, Atticus Geiger, Amir Zur, Christopher Potts._ <br>
    **Conference**: [ICML 2023](https://openreview.net/pdf?id=1Hh1cIPJ7V)  <br>
    **Summary**: _The paper highlights that explainability methods in NLP systems encounter a form of the fundamental problem of causal inference. This means that for any given text input, we cannot observe the counterfactual versions of that input (i.e., alternate versions of the input that could lead to different outcomes). Without these counterfactuals, isolating the causal influence of specific parts of a model's representation on its outputs is difficult. The core proposal in this paper is the CPM, a model trained to mimic the black-box model. The CPM is designed to produce similar outputs as the original black-box model on actual input texts, while allowing for controlled interventions in its internal representations to simulate counterfactual scenarios._

- **"Concept-based Explanations for Out-of-Distribution Detectors"**  
    **Authors**: _Jihye Choi, Jayaram Raghuram, Ryan Feng, Jiefeng Chen, Somesh Jha, Atul Prakash._ <br>
    **Conference**: [ICML 2023](https://openreview.net/pdf?id=a33IYBCFey)  <br>
    **Summary**: _Propose an unsupervised framework for learning a set of concepts that satisfy the desired properties of high detection completeness and concept separability, and demonstrate its effectiveness in providing concept-based explanations for diverse off-the-shelf OOD detectors._

- **"Probabilistic Concept Bottleneck Models"**  
    **Authors**: _Eunji Kim, Dahuin Jung, Sangha Park, Siwon Kim, Sungroh Yoon._ <br>
    **Conference**: [ICML 2023](https://openreview.net/pdf?id=yOxy3T0d6e)  <br>
    **Summary**: _ProbCBM models uncertainty in concept prediction and provides explanations based on the concept and its corresponding uncertainty._

- **"Discover and Cure: Concept-aware Mitigation of Spurious Correlation"**  
    **Authors**: _Shirley Wu, Mert Yuksekgonul, Linjun Zhang, James Zou._ <br>
    **Conference**: [ICML 2023](https://openreview.net/pdf?id=QDxtrlPmfB)  <br>
    **Summary**: _Discovers unstable concepts across different environments as spurious attributes, and then intervenes on the training data using the discovered concepts to reduce spurious correlation._

- **"A Closer Look at the Intervention Procedure of Concept Bottleneck Models"**  
    **Authors**: _Sungbin Shin, Yohan Jo, Sungsoo Ahn, Namhoon Lee._ <br>
    **Conference**: [ICML 2023](https://openreview.net/pdf?id=YIWtM3GdZc)  <br>
    **Summary**: _Develops various ways of selecting intervening concepts to improve the intervention effectiveness and conduct an array of in-depth analyses as to how they evolve under different circumstances._

- **"Global Concept-Based Interpretability for Graph Neural Networks via Neuron Analysis"**  
    **Authors**: _Han Xuanyuan, Pietro Barbiero, Dobrik Georgiev, Lucie Charlotte Magister, Pietro Lió._ <br>
    **Conference**: [AAAI 2023](https://arxiv.org/abs/2208.10609)  <br>
    **Summary**: _highlights a finding that Graph Neural Network (GNN) neurons act as concept detectors, meaning that individual neurons in a GNN are capable of recognizing specific patterns or "concepts" within graph data. These concepts are tied to properties such as node degree (the number of edges connected to a node) and the neighborhood properties of the node (attributes of nodes directly connected to it._

- **"Interactive Concept Bottleneck Models"**  
    **Authors**: _Kushal Chauhan, Rishabh Tiwari, Jan Freyberg, Pradeep Shenoy, Krishnamurthy Dvijotham._ <br>
    **Conference**: [AAAI 2023](https://arxiv.org/abs/2212.07430)  <br>
    **Summary**: _Extends CBMs to interactive prediction settings where the model can query a human collaborator for the label to some concepts. We develop an interaction policy that, at prediction time, chooses which concepts to request a label for so as to maximally improve the final prediction._

- **"Sparse Linear Concept Discovery Models"**  
    **Authors**: _Konstantinos P. Panousis, Dino Ienco, Diego Marcos._ <br>
    **Conference**: [arXiv 2023](https://arxiv.org/abs/2308.10782)  <br>
    **Summary**: _Highlights that CBMs usually suffer from performance degradation and lower interpretability than intended due to the sheer amount of concepts contributing to each decision. The authors propose a simple yet highly intuitive interpretable framework based on Contrastive Language Image models and a single sparse linear layer meaning that only a few features (or concepts) are allowed to contribute to each decision, addressing the problem of too many concepts being involved._  

- **"Statistically Signifcant Concept-based Explanation of Image Classifers via Model Knockoffs"**  
    **Authors**: _Kaiwen Xu1, Kazuto Fukuchi1, Youhei Akimoto1, Jun Sakuma._ <br>
    **Conference**: [IJCAI 2023](https://www.ijcai.org/proceedings/2023/0058.pdf)  <br>
    **Summary**: _Propose a method to learn the image concept and then using the Knockoff samples to select the important concepts for prediction by controlling the False Discovery Rate (FDR) under a certain value._

- **"Text2Concept: Concept Activation Vectors Directly from Text"**  
    **Authors**: _Mazda Moayeri, Keivan Rezaei, Maziar Sanjabi, Soheil Feizi._ <br>
    **Conference**: [CVPRW 2023](https://www.ijcai.org/proceedings/2023/0058.pdf)  <br>
    **Summary**: _Text2Concept introduces a method to generate CAVs directly from text descriptions, instead of relying on curated examples. The method leverages the CLIP model (which connects text and image representations in a shared multi-modal feature space) to enable any off-the-shelf vision model (like ResNet, etc.) to use text-based concepts without extensive training. The key innovation is a linear mapping layer that aligns the feature space of the vision model with the feature space of CLIP. This mapping layer requires only minimal training on existing data to achieve this alignment._

- **"Label-Free Concept Bottleneck Models"**  
    **Authors**: _Tuomas Oikarinen, Subhro Das, Lam M. Nguyen, Tsui-Wei Weng._ <br>
    **Conference**: [ICLR 2023](https://openreview.net/pdf?id=FlCg47MNvBA)  <br>
    **Summary**: _Method to transform any neural network into an interpretable CBM without labeled concept data, while retaining a high accuracy._

- **"CLIP-Dissect: Automatic Description of Neuron Representations in Deep Vision Networks"**  
    **Authors**: _Tuomas Oikarinen, Tsui-Wei Weng._ <br>
    **Conference**: [ICLR 2023](https://openreview.net/pdf?id=iPWiwWHc1V)  <br>
    **Summary**: _Leverages multimodal vision/language models to label internal neurons with open-ended concepts without the need for any labeled data or human examples._

 - **"Concept-level Debugging of Part-Prototype Networks"**  
    **Authors**: _Andrea_Bontempelli, Stefano Teso, Katya Tentori, Fausto Giunchiglia, Andrea Passerini._ <br>
    **Conference**: [ICLR 2023](https://openreview.net/pdf?id=oiwXWPDTyNk)  <br>
    **Summary**: _Proposes a "debugger", which is a method for human experts to provide feedback on model predictions, specifically on what portion of the input is relevant, which is then further used to finetune the model._

 - **"Post-hoc Concept Bottleneck Models"**  
    **Authors**: _Mert Yuksekgonul, Maggie Wang, James Zou._ <br>
    **Conference**: [ICLR 2023](https://arxiv.org/pdf/2205.15480)  <br>
    **Summary**: _PCBMs can convert any pre-trained model into a concept bottleneck model in a data-efficient manner, and enhance the model with the desired interpretability benefits. In constrast to CBMs tackling local interventions, PCBMs propose interventions for changing global model behavior._

 - **"Explain Any Concept: Segment Anything Meets Concept-Based Explanation"**  
    **Authors**: _Ao Sun, Pingchuan Ma, Yuanyuan Yuan, Shuai Wang._ <br>
    **Conference**: [NeurIPS 2023](https://papers.nips.cc/paper_files/paper/2023/file/44cdeb5ab7da31d9b5cd88fd44e3da84-Paper-Conference.pdf)  <br>
    **Summary**: _Explores using SAM as a concept discovery method to augment conceptbased XAI. Concepts here are largely class-level._
   

- **"A Holistic Approach to Unifying Automatic Concept Extraction and Concept Importance Estimation"**  
    **Authors**: _Thomas Fel, Victor Boutin, Mazda Moayeri, Rémi Cadène, Louis Bethune, Léo andéol, Mathieu Chalvidal, Thomas Serre._ <br>
    **Conference**: [NeurIPS 2023](https://arxiv.org/abs/2306.07304)  <br>
    **Summary**: _The authors propose a unified perspective on post-hoc concept-based explanation methods. The main intuition underlying the work revolves around the fact that typical concept-based explanations can be considered as a two-stage process whereby, initially, a concept vocabulary is learned and, lastly, each concept's importance is evaluated.._  




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
