# DistilBERT Fine-Tuning on IMDB

Fine-tuned **`distilbert-base-uncased`** on a **4,000-review training split** of IMDB and tested on **1,000 reviews**.

---

## ⚙️ Setup
- **Base model:** `distilbert-base-uncased` (66M params, 6 layers, 12 heads)  
- **Training:** Full fine-tuning (all parameters updated)  
- **Batch size:** 16  
- **Epochs:** 2  
- **Optimizer steps:** ~500  

---

## 📊 Results

### Before Fine-Tuning (Base Encoder Only + Random Head)
- Accuracy: ~50% (random guess baseline on balanced dataset)  
- Eval Loss: High / unstable  

### After Fine-Tuning (Full Model, 4k/1k split)
- Accuracy: **~86–90%**  
- Eval Loss: ~0.30  
- Precision / Recall / F1: Balanced, ~0.86–0.90  

> The model started around **20% accuracy (step 0)** and improved to **~88% accuracy after 2 epochs**.

---


