# Email Subject Line Generator

This repo contains a Jupyter Notebook that generates catchy **email subject lines** from brief descriptions using a pretrained **GPT‑2** model (Hugging Face `transformers`).

## How to Run
1. Create/activate a Python 3.10+ environment
2. Install dependencies:
   ```bash
   pip install transformers torch pandas matplotlib
   ```
3. Open `Email_Subject_Generator.ipynb` in Jupyter/VSCode/Colab
4. Run cells top to bottom
5. (Optional) Download Enron dataset from Kaggle and set `ENRON_CSV_PATH` in the notebook

## Files
- `Email_Subject_Generator.ipynb` – main notebook
- `outputs/` – generated CSV/JSON results

## Notes
- Start with the demo dataset to verify everything works.
- Then switch to Enron for more realistic inputs.
- Tune prompt templates & decoding parameters to improve results.

## Author
Visshva R
