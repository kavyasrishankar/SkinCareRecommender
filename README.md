# AI SkinCare Recommendation & Nutrition Assistant

An AI-powered skincare recommendation system that analyzes a user's facial image to predict skin type and provides personalized skincare products, dietary recommendations, and dermatology insights through an interactive Gradio web interface.

---

## Project Overview

The AI SkinCare Recommendation & Nutrition Assistant is designed to assist users in understanding their skin type using image-based analysis. After predicting the skin type, the system recommends suitable skincare products, healthy foods, and dermatologist-inspired care suggestions.

The application integrates Computer Vision, Machine Learning, and an interactive Gradio interface to provide a simple and user-friendly skincare assistant.

---

## Features

- Upload facial image
- AI-based skin type prediction
- Confidence score visualization
- Personalized skincare product recommendations
- Nutrition recommendations for healthy skin
- AI dermatology insights
-  Interactive Gradio user interface

---

## User Interface

### Input

- Upload Facial Image

### Output

- Predicted Skin Type
- AI Confidence Score
- Recommended Skin Care Products
- Recommended Foods
- AI Dermatology Insight
- Personalized Skin Care Suggestions

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Pillow
- Matplotlib
- Gradio
- Google Colab

---

## Dataset

The model was trained using a facial skin type image dataset consisting of different skin categories.

Dataset Structure

```
SkincareDataset/
│
├── train/
├── test/
├── valid/
```

---

##  Working Pipeline

1. User uploads a facial image.
2. Image is preprocessed (resize, normalization).
3. The trained CNN model predicts the skin type.
4. Confidence score is generated.
5. Product recommendations are displayed.
6. Nutrition suggestions are generated.
7. AI dermatology insights are presented.

---

## Sample Prediction

**Predicted Skin Type**

```
Oily
```

**Confidence Score**

```
30.26%
```

**Recommended Products**

- Sebamed Clear Face Gel
- Simple Face Wash
- Aqualogica Sunscreen

**Recommended Foods**

- Orange
- Tomato
- Spinach
- Green Tea

**Dermatology Insights**

- Excess sebum production detected
- Moderate acne susceptibility

Recommendations

- Oil-free cleanser
- Lightweight moisturizer
- SPF protection

Expected Outcome

- Reduced oiliness
- Healthier skin appearance

---

## Machine Learning Workflow

```
Facial Image
      │
      ▼
Image Preprocessing
      │
      ▼
CNN Skin Type Classification
      │
      ▼
Skin Type Prediction
      │
      ▼
Recommendation Engine
      │
      ├── Products
      ├── Foods
      └── Dermatology Insights
```

---

## Future Improvements

- Acne severity detection
- Dark circle detection
- Wrinkle analysis
- Skin hydration estimation
- Multi-language support
- Mobile application deployment
- Cloud deployment using Hugging Face Spaces or Render

---

## Applications

- Personal skincare assistant
- Beauty and wellness platforms
- Dermatology clinics
- AI healthcare solutions
- Cosmetic recommendation systems

---

## Project Demonstration

Upload a facial image and receive:

Skin Type Prediction

Confidence Score

Personalized Product Recommendations

Nutrition Suggestions

AI Dermatology Insights

---

## Author

**Kavyasri S**

B.Tech – Artificial Intelligence and Data Science

Rajalakshmi Institute of Technology

GitHub: https://github.com/kavyasrishankar

LinkedIn: https://linkedin.com/in/kavyasrishankar
