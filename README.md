# 🔐 Password Generator (Python)

## 📌 Description

This is a simple **Python Password Generator** that creates a random and secure password based on the number of **letters, numbers, and symbols** chosen by the user.

The program uses Python’s built-in **`random` module** to randomly select characters from predefined lists of:

* Uppercase and lowercase **letters**
* Numeric **digits**
* Special **symbols**

After taking user input, the script combines the randomly selected characters and displays a **generated password**.

---

## ⚙️ How It Works

1. The program greets the user with a welcome message.
2. It asks the user:

   * How many **letters** are needed
   * How many **numbers** are needed
   * How many **symbols** are needed
3. Using loops and `random.choice()`, the program:

   * Picks random characters from each category
   * Adds them to a password string
4. Finally, the generated password is printed on the screen.

---

## 🧠 Concepts Used

* Python **lists**
* **for loops**
* **user input** with `input()`
* **type conversion** using `int()`
* **random module** (`random.choice`)
* **string concatenation**

---

## ▶️ Example Output

```
Welcome to password generator!!
How many letters you want in your password: 5
How many nums you want in your password: 3
How many symbols you want in your password: 2

aZtQm482@#
THIS IS YOUR GENERATED PASSWORD.....
```

---

## 🚀 Future Improvements

* Shuffle the final password for better randomness
* Allow copying the password to clipboard
* Add password strength checker
* Create a simple **GUI version** using Tkinter or a web version using HTML/CSS/JS

---

## 🛠 Requirements

* Python 3.x
* No external libraries required (only built-in `random` module)

---

## 📂 Usage

Run the script in terminal:

```
python password_generator.py
```

Follow the prompts to generate your secure password.

---

⭐ If you like this project, consider giving it a **star** on GitHub!
