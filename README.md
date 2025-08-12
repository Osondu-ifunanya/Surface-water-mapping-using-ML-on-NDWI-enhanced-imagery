
# Surface Water Mapping Using ML on NDWI-Enhanced Imagery (Synthetic Data)

## 📌 Project Overview

This project demonstrates how to use machine learning techniques to map surface water bodies from NDWI (Normalized Difference Water Index)-enhanced imagery. Synthetic data is generated to simulate real-world satellite image features, enabling model training without reliance on large datasets.

The workflow includes:

* Generating synthetic NDWI and related spectral features
* Applying supervised ML classification
* Visualizing predicted surface water distribution

---

## 🛠 Features

* **Synthetic NDWI Dataset Generation** for training and testing
* **Machine Learning Model** (Random Forest) for classification
* **Accuracy Evaluation** using confusion matrix and classification report
* **Visualization** of water vs non-water regions

---

## 📂 Project Structure

```plaintext
.
├── surface_water_mapping.py   # Main script
├── synthetic_data.xlsx        # Generated synthetic dataset
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies
```

---

## 🚀 Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/surface-water-mapping.git
cd surface-water-mapping
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the script:

```bash
python surface_water_mapping.py
```

This will:

1. Generate synthetic NDWI-based data
2. Train the ML model
3. Classify pixels as water/non-water
4. Output classification accuracy and maps

---

## 📊 Example Output

* Confusion matrix showing classification performance
* Plots of NDWI distribution
* Classified map of water bodies

---

## 📖 Methodology

1. **Synthetic Data Simulation**: Create NDWI and related bands to mimic real satellite imagery.
2. **Feature Selection**: Use NDWI values and additional spectral indicators for classification.
3. **Model Training**: Train Random Forest to distinguish between water and non-water pixels.
4. **Evaluation**: Assess accuracy using synthetic ground truth.

---

## 📌 Dependencies

* `numpy`
* `pandas`
* `scikit-learn`
* `matplotlib`

---

## 📜 License

This project is licensed under the MIT License.


