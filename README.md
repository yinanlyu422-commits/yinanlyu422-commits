# Yinan Lü

**MSc Artificial Intelligence | Computer Vision | Multimodal Learning | PyTorch**

I focus on computer vision and multimodal learning, with hands-on experience in model reproduction, controlled experimentation, robustness evaluation, model optimisation, and result analysis.

My current work covers multimodal sentiment analysis, vehicle re-identification, weakly supervised video anomaly detection, fine-grained image classification, and parameter-efficient LLM fine-tuning.

---

## Featured Project

### RA-EMOE: Reliability-Aware Multimodal Emotion Recognition

Robustness evaluation and reliability-aware routing calibration for multimodal sentiment analysis on **CMU-MOSI**.

**Key work**
- Reproduced the EMOE multimodal sentiment analysis baseline in PyTorch
- Built controlled robustness experiments covering modality absence, language masking, and Gaussian feature corruption
- Analysed router behaviour under modality degradation
- Designed the RA-EMOE reliability-aware calibration module
- Evaluated EMOE and RA-EMOE under matched degradation conditions

**Selected results**
- EMOE reproduction: **ACC-2 85.21% | F1 85.24% | MAE 0.7354**
- Complete vision absence: **F1 +2.47 percentage points**
- Complete language absence: **F1 42.31% → ~50.63% (+8.32 pp)**

[View the RA-EMOE repository](https://github.com/yinanlyu422-commits/EMOE-Robustness-RAEMOE)

---

## Computer Vision Projects

### Vehicle Re-Identification

Built a PyTorch Vehicle Re-ID training and evaluation pipeline using **ResNet50**, **Cross-Entropy Loss**, and **Triplet Loss**.

- Compared ResNet50, MobileNetV3, and EfficientNet-B0
- Conducted controlled experiments on augmentation and training configurations
- Improved test **mAP from 56.9% to 65.3%**
- Improved **Rank-1 from 88.5% to 90.8%**

### Weakly Supervised Video Anomaly Detection

Worked on MIL-based weakly supervised video anomaly detection with temporal modelling and CLIP-based semantic features.

- Implemented MIL scorer, Top-K Pooling, ranking loss, and evaluation components
- Participated in Temporal Self-Attention experiments
- Analysed model behaviour using PR curves, confusion matrices, UMAP, and attention heatmaps

### Fine-Grained Image Classification

Built a 543-class image classification pipeline and compared **EfficientNet-B0**, **ResNet50**, and **ViT-Base**.

- Evaluated model performance under different augmentation strategies
- Conducted controlled learning-rate and batch-size experiments
- Analysed the negative effect of excessive geometric augmentation on fine-grained recognition

---

## Multimodal & LLM

### TinyLlama + LoRA

Worked on parameter-efficient fine-tuning of **TinyLlama-1.1B** across en-AU, en-IN, and en-UK sarcasm datasets.

- Hugging Face PEFT / LoRA
- ~12.62M trainable parameters (~1.2%)
- Multi-seed cross-variety evaluation
- Weighted Cross-Entropy and Early Stopping

---

## Technical Skills

**Programming & Frameworks**  
Python · PyTorch · OpenCV · scikit-learn · Hugging Face Transformers / PEFT

**Computer Vision**  
CNN · ResNet · EfficientNet · ViT · Vehicle Re-ID · Metric Learning · Video Anomaly Detection

**Multimodal & Transformer**  
Transformer · Self-Attention · CLIP · Multimodal Fusion · Dynamic Routing · LoRA / PEFT

**Experimentation & Development**  
Linux · Git/GitHub · Conda · Jupyter · NVIDIA GPU · Controlled Experiments · Ablation Studies · Multi-seed Evaluation

---

## Education

**MSc Artificial Intelligence**  
University of Surrey  
2025–2026 · Degree expected January 2027

**BSc (Hons) Information Technology**  
UWE Bristol

---

## Contact

**Email:** lyn303517651@163.com  
**GitHub:** [yinanlyu422-commits](https://github.com/yinanlyu422-commits)
