# Neural Machine Translation: English–Amharic

A neural machine translation (NMT) project for translating between English and Amharic, one of the most widely spoken languages in Ethiopia and a low-resource language in NLP. The project trains a deep learning translation model on a parallel English–Amharic corpus and evaluates the quality of its translations.

## Repository Contents

| File | Description |
|------|-------------|
| `NMT_English_Amharic_final.ipynb` | Notebook covering data preparation, model training, and translation evaluation |
| `Amharic-English Dataset.rar` | Parallel English–Amharic dataset used for training (compressed archive) |

## Project Workflow

1. **Data preparation:** extract the dataset and load the English–Amharic sentence pairs.
2. **Preprocessing:** clean and normalize the text, then tokenize both languages.
3. **Model training:** train a neural translation model on the parallel corpus.
4. **Evaluation:** assess translation quality on held-out sentences.
5. **Translation:** generate translations for new input sentences.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/TimBroAhm/Neural-Machine-Translation.git
cd Neural-Machine-Translation
```

2. Extract `Amharic-English Dataset.rar` (for example with 7-Zip or WinRAR) into the project folder.
3. Open `NMT_English_Amharic_final.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab. A GPU is recommended for training.
4. If you use Colab, upload the extracted dataset files first.
5. Run the cells in order. The required libraries are imported at the top of the notebook.

## Why Amharic?

Amharic uses the Ge'ez script and has rich morphology, and far fewer digital language resources than English. This makes it a challenging and valuable target for machine translation research.

## Future Work

- Experiment with Transformer-based and pretrained multilingual models
- Expand the parallel corpus with more diverse domains
- Evaluate with additional metrics such as BLEU and chrF
- Support translation in both directions

## Author

**Tim** ([@TimBroAhm](https://github.com/TimBroAhm))
