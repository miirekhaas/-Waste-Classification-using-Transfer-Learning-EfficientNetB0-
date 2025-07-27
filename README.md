
# 📦 Waste Classification using Transfer Learning (EfficientNetB0)

This project uses **transfer learning with EfficientNetB0** to classify images of waste materials into categories such as cardboard, glass, metal, paper, plastic, and trash. It was built and tested on [Deepnote](https://deepnote.com), optimized for **speed**, **minimal resource use**, and **Coursera assignment requirements**.

---

## 🚀 Project Highlights

- ✅ **Pretrained EfficientNetB0** for fast and efficient image classification
- ✅ **Fine-tuned** model with limited data for speed optimization
- ✅ **Static code analysis passed** (PyLint score 10/10)
- ✅ **All Coursera peer-reviewed tasks (1–10)** completed
- ✅ Developed in **Jupyter Notebook** with TensorFlow/Keras
- ✅ Compatible with **Deepnote GPU/CPU environments**

---

## 🧠 Dataset

- 📁 Structure: Each folder contains images of that waste type:
```
Garbage classification/
  ├── cardboard/
  ├── glass/
  ├── metal/
  ├── paper/
  ├── plastic/
  └── trash/
```
- 📍 **Note:** This project is configured for a Deepnote path:
```
/datasets/_deepnote_work/20250727-130903/Garbage classification/Garbage classification
```
> If you are running locally or elsewhere, update the `base_dir` path in the notebook accordingly.

---

## 📊 Tasks Completed (Coursera Assignment)

| Task No. | Description                          | Screenshot                     |
|---------:|--------------------------------------|--------------------------------|
| 1        | Print TensorFlow version             | `tensorflow_version.png`      |
| 2        | Create `test_generator`              | `test_generator.png`          |
| 3        | Print length of `train_generator`    | `train_generator_len.png`     |
| 4        | Print model summary                  | `model_summary.png`           |
| 5        | Compile model                        | `model_compile.png`           |
| 6        | Accuracy curve (extract feat model)  | `plot_accuracy_curve.png`     |
| 7        | Loss curve (fine-tuned model)        | `plot_loss_curve.png`         |
| 8        | Accuracy curve (fine-tuned model)    | `plot_finetune_model.png`     |
| 9        | Plot test image (extract model)      | `extract_features_model.png`  |
| 10       | Plot test image (fine-tuned model)   | `finetuned_model.png`         |

---

## 📁 Folder Structure

```
Waste-Classification-Transfer-Learning/
├── README.md
├── dataset_info/
│   └── README_dataset.md
├── models/
│   ├── efficientnetb0_extract.h5
│   └── efficientnetb0_finetuned.h5
├── notebooks/
│   └── waste_classification.ipynb
└── screenshots/
    └── *.png (All task screenshots)
```

---

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow / Keras
- EfficientNetB0
- Matplotlib
- Deepnote
- Jupyter Notebook

---

## 📌 Setup Instructions

1. Upload dataset to Deepnote and note the path
2. Clone this repo and open `notebooks/waste_classification.ipynb`
3. Run all cells — optimized for CPU or GPU use
4. Modify dataset path if needed

## 📦 Dataset Setup

This project uses the Garbage Classification dataset.

➡️ Download it from [Kaggle](https://www.kaggle.com/datasets/asdasdasd)   



## 📈 Results

- Fast execution even with reduced training samples
- Achieved accurate classification with a light model
- Ideal for low-resource environments

---

## 📃 License

MIT License — feel free to fork and build on top of this project.
