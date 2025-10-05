# 🧮 Scientific Calculator (Python)  

A **feature-packed**, **dual-mode Scientific Calculator** built with **Python**, supporting both **Command Line Interface (CLI)** and **Graphical User Interface (GUI)** modes.  
It combines accuracy, performance, and clean design — making it a perfect example of object-oriented Python + GUI development.  


## 🚀 Features

### ⚙️ Command-Line Mode (`Calculator.py`)
A powerful **interactive terminal-based** calculator that supports all basic and advanced mathematical operations.

✅ **Key Features**
- ➕ Basic operations — addition, subtraction, multiplication, division  
- 📈 Scientific functions — power, exponent, logarithm, square root  
- 📐 Trigonometric & inverse trigonometric operations (degree-based)  
- 🧠 Built-in help command (`help`)  
- 🛡️ Handles invalid inputs and division by zero gracefully  

🧾 **Example Run**
```bash
$ python Calculator.py
Enter operator (type 'help' to list options): add
Enter first number: 12
Enter second number: 8
Result: 20.0
Do you want to continue? (yes/no): no
Exiting calculator. Goodbye!
```



🖥️ GUI Mode (Calculator_with_gui.py)

An elegant Tkinter-based Graphical Calculator with a neat layout, supporting real-time expression evaluation and scientific functions.

✅ Highlights

🔢 Fully functional number pad

🧮 Basic operators: +, -, ×, ÷, %

🔬 Scientific functions: sqrt, pow, sin, cos, tan, asin, acos, atan, exp, log

🔄 Sign toggle (+/-)

🧹 Clear (C) and Backspace (CE) buttons

🧰 Safe evaluation of expressions using ast (prevents arbitrary code execution)

🎨 Modern, user-friendly interface with large clickable buttons


🪄 GUI Preview

> (Add a screenshot here if you want — e.g., assets/gui_screenshot.png)

python Calculator_with_gui.py





📂 Project Structure

Scientific-Calculator/
│
├── Calculator.py                # CLI-based scientific calculator
├── Calculator_with_gui.py       # GUI-based Tkinter calculator
└── README.md                    # Project documentation




⚙️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/<your-username>/Scientific-Calculator.git
cd Scientific-Calculator

2️⃣ Run Command-Line Calculator

python Calculator.py

3️⃣ Run GUI Calculator

python Calculator_with_gui.py




🧠 How It Works

🔸 CLI Version:

Uses a class-based structure (ScientificCalculator) for clean organization.

Operator functions are mapped dynamically via a dictionary of callables.

Handles both single-input and dual-input operations with validation loops.


🔸 GUI Version:

Built using Tkinter.

Uses grid layout for responsive button placement.

Safe mathematical expression parsing via the custom SafeEval class using Python’s ast module.

Supports chained operations and dynamic exponent inputs via simpledialog.




🧩 Technologies Used

Python 3.x
• Tkinter (GUI)
• AST module (Safe evaluation)
• Math module



🏆 License

This project is open-source and available under the MIT License.



⭐ If you like this project, give it a star!
Your support motivates me to build more such practical projects ❤️
