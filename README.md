# 🔍 Neural Search Indexing Optimization: Integrating Augmentation and PEFT for Efficient Retrieval

#### Copyright © 2025 Alessio Borgi, Eugenio Bugli, Damiano Imola

## 📌 Overview  
This repository provides an optimized implementation of **Differentiable Search Indexing (DSI)**, integrating **data augmentation techniques** and **parameter-efficient fine-tuning (PEFT) methods** to improve retrieval accuracy and computational efficiency. Our contributions include:  

✅ **Data Augmentation Techniques:**  
- **Num2Word Transformation:** Converts numerical values into their word equivalents.  
- **Stopword Removal:** Eliminates redundant tokens to improve semantic representation.  
- **POS-MLM Augmentation:** Combines part-of-speech tagging with masked language modeling to enhance context understanding.  

✅ **Parameter-Efficient Fine-Tuning (PEFT) Methods:**  
- **LoRA**: Low-Rank Adaptation for lightweight fine-tuning.  
- **QLoRA**: 4-bit quantization with LoRA for memory efficiency.  
- **AdaLoRA**: Adaptive LoRA that dynamically adjusts rank.  
- **ConvLoRA (LoCon)**: LoRA extended with depthwise convolution for local feature modeling.  

🚀 Our approach enables **faster fine-tuning, reduced memory consumption, and enhanced retrieval performance** for large-scale search indexing tasks.  

---

## 📦 Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/alessioborgi/DSI-Augmentation-FineTuning.git
cd DSI-Augmentation-FineTuning
```
### 2️⃣ Set Up Virtual Environment
```bash
python -m venv dsi_env
source dsi_env/bin/activate  # On Windows: dsi_env\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

