# SADA-IR: Learning Semantic-Adaptive and Degradation-Aware Priors for All-Weather Image Restoration

## 📌 Introduction
All-Weather Image Restoration (AWIR) aims to recover clear images from diverse adverse-weather degradations, yet remains challenging due to the strong coupling and high heterogeneity of rain, haze, and snow effects. Recent multimodal restoration methods attempt to leverage vision–language priors, but are limited by two fundamental issues: (i) Vision–language models (\textit{e.g.}, CLIP) exhibit a semantic domain gap to human perceptual degradation cues, rendering manually specified discrete text prompt insufficient for faithfully describing real-world degradations; (ii) Degradation representations inferred from a single degraded observation lack informative constraints, hindering fine-grained modeling of degradation patterns and severity. To overcome these limitations, we propose SADA-IR, a novel prompt-based learning framework that jointly exploits the semantic-adaptive textual prior and degradation-aware visual prior for robust AWIR. Specifically, we introduce Semantic-Adaptive Prompt Tuning (SAPT) to dynamically select and calibrate the most compatible semantic prototype in the text embedding space, reducing the bias induced by fixed prompts. Moreover, we develop a degradation-adaptive visual context learning strategy that mines degradation cues from degraded–clean image pairs, enabling fine-grained quantification of degradation characteristics and strength variations. Extensive experiments demonstrate that SADA-IR achieves superior performance over state-of-the-art methods in both quantitative and qualitative evaluations.

<img width="1165" height="736" alt="image" src="https://github.com/user-attachments/assets/ef368a51-5728-414c-a649-ca22fcc994e8" />


## 🌊 Requirement
* Python==3.9
* torch==2.3.1
* torchvision==0.18.1
* CUDA==11.8

## 🚀 Training
```bash
python train.py
```

## 🧪 Testing
```bash
python test.py
```

## 📖 Paper Info & Status
> **Title**: SADA-IR: Learning Semantic-Adaptive and Degradation-Aware Priors for All-Weather Image Restoration 
> **Authors**: Laibin Chang, Shaodong Wang, Xu Zhang, Yunke Wang, Kui Jiang, and Bo Du
> **Status**: Under Review  
> **Code**: The code will be released after the paper is accepted.

---
## 📝 Notes
* ❓ If you have any questions, please feel free to contact us at **[changlb666@whu.edu.cn](mailto:changlb666@whu.edu.cn)**.
* 🌐 I am open to collaboration and welcome inquiries from anyone interested in my research. Please visit **[https://laibinchang.github.io/](https://laibinchang.github.io/)** for our latest updates.
