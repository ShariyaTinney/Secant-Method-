
📐 Secant Method in C++

📌 Overview
This project is a simple implementation of the **Secant Method** using C++.  
The Secant Method is a numerical technique for finding the roots of nonlinear equations.  
It is an iterative method that requires two initial approximations and converges to the root through repeated evaluations of the function.


The equation used in this implementation is:
f(x) = x³ - x - 11



🎯 Features
✅ Calculates root using the Secant Method
✅ Handles function evaluation and convergence check
✅ Iterative loop until desired precision is reached
✅ Output displays root and number of iterations



🛠 Requirements
C++ Compiler (e.g., g++, clang++)
Any C++ IDE (optional): Visual Studio Code, CLion, Code::Blocks, etc.



🚀 How to Run

1.Clone the repository or download the source code:
   bash
   git clone https://github.com/ShariyaTinney/secant-method-cpp.git
   cd secant-method-cpp

2.Compile the C++ code:
   bash
   g++ main.cpp -o secant

3.Run the program:
   bash
   ./secant




🧠 How It Works
Starts with two initial guesses `x1` and `x2`.
Applies the **Secant Method** formula:
x0 = (x1 * f(x2) - x2 * f(x1)) / (f(x2) - f(x1))
Repeats until the difference between iterations is less than a given tolerance `E`.



📁 File Structure
secant-method-cpp/
├── main.cpp     # Main C++ program implementing the Secant Method
├── README.md    # This documentation file




📤 Sample Output
Root of the given equation = 2.58057
No. of iterations = 6




🔧 Customization
You can change the following in the code:
✅ The function `f(x)` in the `f()` method
✅ Initial guesses (`x1`, `x2`)
✅ Error tolerance `E`



🤝 Contributions
Contributions are welcome!
Feel free to fork this repository, create a new branch, and submit a pull request with your improvements.



📧 Contact
For any questions or feedback, contact:
ShariyaTinney — \[[ShariyaTinney.gmail@example.com](mailto:ShariyaTinney.gmail@example.com)] 



✅ What You Should Update
Replace:
`ShariyaTinney` in the `git clone` link
`ShariyaTinney` and `ShariyaTinney.gmail@example.com` with your actual ShariyaTinney/email
Once done, add this `README.md` to your project directory and push it to GitHub.

