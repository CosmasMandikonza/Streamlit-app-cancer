# Streamlit-app-cancer
# Breast Cancer Diagnosis App

The **Breast Cancer Diagnosis App** is a machine learning-powered tool built to aid medical professionals and students in the early detection and diagnosis of breast cancer. By using a sophisticated prediction model, the app analyzes specific measurements of a breast mass and provides insights on its likelihood of being benign or malignant.

 <!-- If you have any visuals, you can replace 'link-to-your-image' with the actual image link. -->

## 🩺 Key Features

- **Accurate Diagnosis Prediction**: Uses a machine learning algorithm trained on relevant medical data to predict the probability of a breast mass being benign or malignant.
- **Visual Insights**: View a radar chart representation of the input data for a clear and intuitive visual assessment.
- **Flexible Data Input**:
  - Manually input measurements for analysis, ideal for quick assessments.
  - Connect directly to a cytology lab for automated data retrieval (Note: machine integration is external to the app).

## ⚙️ How It Works

1. **Input the Data**: The user scales measurements associated with the breast mass, such as radius, texture, perimeter, and other specific attributes.
2. **Run Prediction**: The app processes these inputs through its trained model and predicts the diagnosis as either **Benign** or **Malignant**.
3. **View Results**: The predicted diagnosis and probability scores are displayed, providing a quick and data-driven assessment.

## 📊 Visual Representation

A radar chart offers a comprehensive view of the input data, highlighting how different measurements compare to typical benign or malignant cases. This visual aid enhances the app's usability, helping medical professionals make informed assessments.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Streamlit
- scikit-learn (for machine learning)
- Matplotlib (for visualization)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CosmasMandikonza/Streamlit-app-cancer.git
   cd Streamlit-app-cancer
