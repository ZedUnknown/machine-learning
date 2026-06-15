# Repository Datasets

To keep this repository lightweight and optimize Git performance, raw data files are hosted remotely on Hugging Face. Below is the dataset map, source links, and the expected directory layouts for local setup.

---

## 📂 Remote Data Repository
All files are maintained in the following dedicated data repository:
* **Hugging Face Hub:** [`ZedUnknown/machine-learning`](https://huggingface.co/datasets/ZedUnknown/machine-learning)

---

## 🗺️ Datasets

| Dataset File | Total Samples | Note | Download Link |
| :--- | :--- | :--- | :--- |
| **`names-v1.txt`** | ~32,000 | Lowercase | [**names-v1.txt**](https://huggingface.co/datasets/ZedUnknown/machine-learning/blob/main/names-v1.txt) |
| **`names-v2.txt`** | ~212,000 | Capitalized | [**names-v2.txt**](https://huggingface.co/datasets/ZedUnknown/machine-learning/blob/main/names-v2.txt) |

---

### Expected Layout

This repository contains placeholder text files pointing to the correct sources. To run the notebooks seamlessly, download the full datasets from the links above and overwrite the corresponding placeholder files inside the local `datasets/` directories.

```text
machine-learning/
└── xxxxx.xxx.xx/
    ├── datasets/
    │   └── dataset-name.ext  <-- Overwrite this placeholder file with the downloaded dataset file
    └── xxxxx.ipynb
```