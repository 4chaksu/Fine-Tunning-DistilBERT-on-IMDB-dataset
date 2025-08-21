# Fine-Tunning-DistilBERT-on-IMDB-dataset
A compact, reproducible pipeline to **fully fine-tune** `distilbert-base-uncased` for **binary sentiment classification** on a **subset of IMDB** reviews.

> **Setup**: Full fine-tuning (all weights trainable).  
> **Data**: 4,000 movie reviews for training, 1,000 reviews for testing.  
> **Goal**: Fast, resource-friendly model with solid accuracy for production-style sentiment use cases.

---

## 🔧 Environment & Dependencies

- Python ≥ 3.9
- `transformers`, `datasets`, `torch`, `scikit-learn`, `pandas`, `numpy`
- (Optional) GPU (CUDA) for speed

```bash
pip install -U transformers datasets torch scikit-learn pandas numpy
