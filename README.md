# 🧠 ClarityAI – AI Decision-Making Agent

ClarityAI is an intelligent AI-powered agent that helps users make better decisions by analyzing options, evaluating risks, and predicting possible outcomes.

It acts like a personal decision assistant that combines logical reasoning with contextual understanding to provide clear, structured recommendations.

---

## 🚀 Features

* ✍️ **Problem Input System**
  Users can describe any real-life decision or dilemma.

* ⚖️ **Option Analysis**
  Compares multiple choices with detailed pros and cons.

* ⚠️ **Risk Evaluation**
  Identifies potential downsides and uncertainties.

* 🔮 **Future Prediction**
  Simulates possible outcomes for each option (short-term insights).

* 📊 **Decision Scoring**
  Assigns a score to each option based on impact and feasibility.

* 🧾 **Final Recommendation**
  Provides a clear, reasoned suggestion tailored to the user's input.

---

## 🏗️ Project Structure

```
clarity-ai/
│
├── backend/
│   ├── app.py              # Flask server & AI logic
│   ├── requirements.txt   # Python dependencies
│
├── frontend/
│   ├── index.html         # Main UI
│   ├── style.css          # Styling
│   ├── script.js          # API integration
│
└── README.md              # Project documentation
```

---

## ⚙️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Python (Flask)
* **AI Engine:** OpenAI API
* **CORS Handling:** Flask-CORS

---

## 🧠 How It Works

1. User enters a problem and possible options
2. Frontend sends data to backend via API
3. Backend constructs a prompt and sends it to OpenAI
4. AI analyzes the decision
5. Response is returned and displayed to the user

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/clarity-ai.git
cd clarity-ai
```

---

### 2️⃣ Setup Backend

```bash
cd backend
pip install -r requirements.txt
```

---

### 3️⃣ Add API Key

Open `app.py` and replace:

```python
client = OpenAI(api_key="YOUR_API_KEY")
```

with your actual OpenAI API key.

---

### 4️⃣ Run the Backend

```bash
python app.py
```

Server will start at:

```
http://127.0.0.1:5000
```

---

### 5️⃣ Run Frontend

* Open `frontend/index.html` in your browser

---

## 📌 Example Use Case

**Input:**

```
Problem: Should I choose a job or pursue higher studies?
Options: Job, Higher Studies
```

**Output:**

* Pros & Cons of each option
* Risks involved
* Future predictions
* Scores
* Final recommendation

---

## 🔮 Future Improvements

* 🎨 Advanced UI (React-based dashboard)
* 📊 Visual graphs for decision scores
* 🧠 User memory & personalization
* 🗂️ Decision history storage (Supabase)
* 🎤 Voice-based input
* 📱 Mobile app version

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork the repository and submit pull requests.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 💡 Inspiration

This project was built to help people overcome indecision by combining AI intelligence with structured reasoning.

---

## 👩‍💻 Author

**Tanmaya**
Aspiring Developer | AI Enthusiast | Problem Solver 🚀

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
