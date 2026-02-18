# 🍽️ Filipino Meal Planner Chatbot
> AI-powered chatbot for personalized Filipino meal planning using Neural Networks

**Live Demo:** [https://pullancu-dev.github.io/filipino-meal-planner-chatbot-nn/](https://pullancu-dev.github.io/filipino-meal-planner-chatbot-nn/)

---

## 🧠 Machine Learning Features

This project uses **5 Neural Networks** powered by Brain.js that actually learn from user behavior:

| Neural Network | Purpose |
|---|---|
| Calorie Detection NN | Detects calorie goals from natural language input |
| Food Recommendation NN | Recommends foods based on user preferences |
| Food Compatibility NN | Ensures foods in a meal work well together |
| Calorie Distribution NN | Distributes calories across Breakfast / Lunch / Dinner / Snack |
| Macro Optimization NN | Balances protein, carbs, and fat based on user goals |

### How the AI Learns
- User rates food items with 👍 or 👎
- After **3+ ratings**, the Food Recommendation NN **retrains automatically**
- Uses **time decay** — recent ratings have more influence than older ones
- Ratings are saved to Firebase so the AI **remembers you across sessions**

---

## ✨ Features

- 💬 Conversational chatbot interface — just type naturally
- 🍽️ 542 Filipino foods in the database
- 🎯 ±5% calorie accuracy
- 🔒 Google Login via Firebase Authentication
- ☁️ Cloud-synced taste profile (👍/👎 ratings saved to Firestore)
- 📱 Responsive — works on mobile and desktop
- 🔄 Personalized meal plans that improve over time

---

## 🗣️ How to Use

1. Open the chatbot
2. Sign in with Google (or skip to use anonymously)
3. Type your calorie goal and preferences:
   - *"2000 calories, high protein, no seafood"*
   - *"1500 calories, vegetarian"*
   - *"2500 calories, low carb, no pork"*
4. Rate the suggested foods with 👍 or 👎
5. Generate a new meal plan — the AI will have learned from your ratings!

---

## 🛠️ Technologies Used

- **Brain.js** — Neural Network library for JavaScript
- **Firebase Authentication** — Google Login
- **Firebase Firestore** — Cloud storage for user feedback/ratings
- **PapaParse** — CSV parsing for the food database
- **Vanilla JavaScript / HTML / CSS** — No frameworks needed

---

## 📁 Project Structure

```
filipino-meal-planner-chatbot-nn/
├── meal_planner_chatbot.html        # Main app (all-in-one)
└── chatbot_food_database_COMPLETE.csv  # 291 Filipino foods dataset
```

---

## 👨‍💻 Developers

Made with ❤️ by **JMP**
