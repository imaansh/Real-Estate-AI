# Real Estate Conversational AI

This repository contains a Real Estate AI system that incorporates various machine learning techniques and models to provide the following features:

## Key Features
1. **Price Prediction**
2. **Description Generation**
3. **Recommendation Generation**
4. **User Intent Identification**
5. **Conversational AI for General Queries**

---

## 1. Price Prediction
- **Data Cleaning & Preprocessing**: Handles outliers and applies logarithmic transformations for better model performance.
- **Training & Testing Split**: Splits data into training and test sets to evaluate the model.
- **Model Training**: Trains a predictive model on cleaned real estate data.
- **Performance**: Achieves an R² score of 0.3.
- **Prediction**: Generates price predictions based on user inputs like house size, number of bedrooms, etc.

---

## 2. Description Generation
- **Model**: Utilizes the `mixtral-8x7b-32768` model from Chat Groq.
- **Functionality**: Generates human-like property descriptions based on user-provided details (e.g., "3-bedroom house in New York").

---

## 3. Recommendation System
- **Data Transformation**: Converts structured property data into an unstructured format.
- **Vectorization**: Uses TF-IDF vectorization on property descriptions.
- **Similarity Search**: Calculates cosine similarity to generate the top 3 recommended properties that match the user’s query.

---

## 4. User Intent Identification and Flow
- **Intent Detection**: Uses an LLM to classify user queries into four categories:
  - Price Prediction
  - Description Generation
  - Property Recommendations
  - General Queries
- **Flow Routing**: Implements Langraph to dynamically call functions based on user intent, ensuring a smooth and responsive experience.

---

## 5. Conversational AI
- **Chatbot Interface**: A conversational AI system capable of understanding general questions and responding accordingly.

---

## Langraph Integration
- Integrated **Langraph** to dynamically manage the flow of conversation based on user intent. This ensures that each user query is correctly routed to the appropriate function (e.g., price prediction, recommendations).

![image](https://github.com/user-attachments/assets/1a7ed49d-e41e-4402-9f01-715b8d18c8ca)
---

## Future Work
- **Front-end Interface**: The next step will be to develop a user-friendly front-end interface for easier interaction with the system.
