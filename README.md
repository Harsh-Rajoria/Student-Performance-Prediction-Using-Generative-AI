# Student-Performance-Prediction-Using-Generative-AI
🧩 Module 1: Student Performance Prediction (G3)

🔥 What we did: • Collected UCI Student Performance Dataset (students’ data). • Selected important features like: • studytime • failures • absences • parent education, etc. • Trained a RandomForestRegressor model to predict final grade (G3).

🧠 Why we did it: • Prediction helps to identify struggling students early. • Random Forest was chosen because: • Easy to train. • Works well on small datasets like student profiles. • Handles mixed features (numerical + categorical).

⸻

🧩 Module 2: Synthetic Student Data Generation

🔥 What we did: • Used SDV (Synthetic Data Vault) or Gemini AI to generate fake but realistic student profiles. • Created extra student data (more training/testing).

🧠 Why we did it: • Real datasets are limited ➔ difficult to test large apps. • Synthetic data helps in: • Expanding training data. • Privacy ➔ No real student names/marks used. • Better model generalization.

⸻

🧩 Module 3: Academic Assistant Chatbot

🔥 What we did: • Built a chatbot using Gemini (Google AI) and fallback OpenAI GPT-3.5. • Students could ask: • “How to improve English?” • “Give a study plan” • “Motivate me to study”

🧠 Why we did it: • Students need more than prediction ➔ they need guidance. • Generative AI feels like a human academic mentor: • Motivates students. • Makes study plans. • Answers academic questions.

⸻

🧩 Module 4: Academic Assistant Full Web App (Streamlit)

🔥 What we did: • Built a Streamlit app where: • Students upload their profile (CSV). • AI predicts G3. • AI generates personalized study plan. • Weekly checklist created. • Hindi translation for non-English speakers. • Free chat box for any academic question.

🧠 Why we did it: • Apps are needed for students/teachers who don’t know coding. • Streamlit was used because: • Easy to build web apps in Python. • Instant deployment (on Colab using ngrok).

⸻

🧩 Module 5: Performance Logging and Progress Tracker

🔥 What we did: • After getting a study plan, students can log their weekly work: • Tasks completed each week. • Reflections: What went well / What went wrong. • Goals for next week. • Saved this into a CSV (performance_log.csv). • Built graphs: • Task completion pie charts. • Reflection summaries. • Monthly progress tracking.

🧠 Why we did it: • Tracking builds consistency ➔ small weekly improvements = huge final improvement. • Students can visualize their progress (not just see marks).

⸻

🧩 Module 6: Leaderboards and Monthly Progress

🔥 What we did: • Created a Leaderboard: • Show top students based on predicted G3. • Show consistency streaks (how many continuous weeks student logged work). • Generated Monthly Progress Reports: • G3 trend month-by-month. • Downloadable PDF reports.

🧠 Why we did it: • Healthy competition motivates students. • Monthly view helps students and teachers plan interventions. • PDF download allows students to print and submit reports.

⸻
