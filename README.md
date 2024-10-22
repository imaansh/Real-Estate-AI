# Real-Estate-Price-Prediction-and-Conversational-Search-System

# This project has four parts: 
1) Price Prediction
2) Description Generation
3) Recommendation Generation
4) User Intent Identification
5) Conversational AI for general questions

## Price Prediction
1) Data Cleaning + Preprocessing (Outlier exclusion, log)
2) Training & Testing split creation
3) Training model
4) Getting R^2 of 0.3
5) Predicting price 

## Description Generation 
1) Chat Groq model: "mixtral-8x7b-32768"
2) Generates descriptions based of user query

## Recommendation Model
1) Create unstructured data from structured data
2) Vectorise using TDIF vectoriser
3) Using cosine similarity to generate top 3 recommendations

## User Intent Identification and Flow
1) Uses LLM to identify user intent from user query (recommendation, price prediction, description generation or general query)
2) Uses Langraph to identify user intent and call that particular function

## Langraph 
![image](https://github.com/user-attachments/assets/1a7ed49d-e41e-4402-9f01-715b8d18c8ca)

## Future Work 
1) Implement front end UI for this project





