# 🧠 Quiz Game

This is a simple command-line-based quiz game built with Python. The game presents a series of True/False questions to the user, tracks their score, and displays the final result at the end.

---

## ✅ Features

- A series of True/False questions.
- Tracks the user's score throughout the quiz.
- Displays the final score at the end of the game.

---

## 📁 Project Structure

```
quiz-game/
├── main.py              # Entry point of the application 
├── question_model.py    # Defines the Question class 
├── data.py              # Contains the question data 
├── quiz_brain.py        # Quiz logic (asking questions, tracking score)
```

---

## 📄 File Descriptions

- **`main.py`**: Initializes the quiz, loads data, and displays the final score.
- **`question_model.py`**: Contains the `Question` class with question text and answer.
- **`data.py`**: Stores the list of question dictionaries used in the quiz.
- **`quiz_brain.py`**: Implements the core quiz logic, including question flow and scoring.

---

## 🖥️ Example Output

```
Q.1: A slug's blood is green. (True/False): True
You got the right answer!
Your current score is: 1/1

Q.2: The loudest animal is the African Elephant. (True/False): False
You got the right answer!
Your current score is: 2/2

...

Your final score is 10/12
```

---

## ▶️ How to Run

1. Clone this repository to your local machine.
2. Make sure Python 3 is installed.
3. Run the quiz from the terminal:
   ```bash
   main.py
   ```
