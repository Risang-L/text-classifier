# Text Classifier: AI vs SLW (Second Language Writers)
This project was built as a personal learning project to explore linguistic data science, and syntactic complexity modeling.

[Live App](https://text-classifier-cgjwcf54nng8fax4cuszie.streamlit.app/)

---

## Features

- Load real-world `.txt` samples by index
- Visualize Syntactic Complexity Indices (e.g., MLS, CN_C, VP_T)
- Generate classification results with confidence scores
- Explore SHAP waterfall plots to interpret predictions

---

## About the syntactic Complexity Indices

The classifier uses L2SCA Indices by [TAASSC](https://www.linguisticanalysistools.org/taassc.html/)

Predictions are supported by SHAP contribution plots, showing how each feature influences the outcome toward AI or SLW.

---

## Data Overview

The dataset consists of 300 text samples divided into three categories:
- **1–100**: Human-written texts by second language writers (SLW)
- **101–200**: AI-generated texts using general prompts
- **201–300**: AI-generated texts created by prompting large language models (LLMs) to mimic SLW writing style

---

## Data Usage Notice

- The `.txt` files in [`txt_samples/`](./txt_samples) are included **only for demonstration and learning purposes**.  
  They are not licensed for reuse, redistribution, or commercial use.  
  See [`txt_samples/LICENSE.txt`](./txt_samples/LICENSE.txt) for full terms.

- The dataset file `X_binary.csv` is private and is **not licensed** for reuse, redistribution, or modification.  
  It is shared solely for demonstration purposes and should not be used for any other purpose.

---

## License

This project's code is licensed under the [MIT License](./LICENSE).
