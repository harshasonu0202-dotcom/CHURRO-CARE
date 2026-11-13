# CHURRO-CARE

## Evaluating Lightweight Image Preprocessing for Historical Text Recognition Using an Open-Weight Vision-Language Model

### Project Overview
CHURRO-CARE evaluates the effect of lightweight image preprocessing techniques on historical text recognition using the CHURRO-3B vision-language model.

The project compares three image conditions:
- Original Images
- Contrast Enhanced Images
- Denoised Images

### Model and Dataset
- **Model:** CHURRO-3B
- **Model Source:** [Stanford OVAL CHURRO-3B](https://huggingface.co/stanford-oval/churro-3B)
- **Dataset:** [CHURRO Dataset](https://huggingface.co/datasets/stanford-oval/churro-dataset)

### Evaluation Metrics
- Character Error Rate (CER)
- Word Error Rate (WER)
- Normalized Levenshtein Similarity (NLS)

### Methodology
1. Load historical document images from the CHURRO dataset.
2. Apply lightweight preprocessing techniques.
3. Perform text recognition using CHURRO-3B.
4. Compare predictions with reference text.
5. Evaluate using CER, WER, and NLS.
6. Analyze the performance of different preprocessing conditions.

### Results
Preliminary evaluation on matched samples indicates that contrast enhancement achieved a slightly lower average CER and higher NLS, while denoising achieved a slightly lower average WER than the original images.

The evaluation is limited by the small sample size and the incomplete denoised OCR result for Sample 5.

### Technologies Used
- Python
- Google Colab
- Hugging Face
- CHURRO-3B
- OpenCV
- Pandas
- Matplotlib

### Repository Contents
- `CHURRO_CARE_Implementation.ipynb` — Project implementation, evaluation, and analysis.

### Limitations
This is a preliminary research evaluation using a limited number of samples. Results should not be generalized without further experimentation.

### Future Work
- Evaluate more historical document samples.
- Complete missing OCR evaluations.
- Investigate additional preprocessing techniques.
- Perform broader comparative analysis.

### References
- Stanford OVAL CHURRO-3B: https://huggingface.co/stanford-oval/churro-3B
- CHURRO Dataset: https://huggingface.co/datasets/stanford-oval/churro-dataset

---

**Research Project: CHURRO-CARE**
