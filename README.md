# 🎯 NumHunt

**NumHunt** is a simple C-based number guessing game where the **computer tries to guess the number you're thinking of** using a binary-search approach.

Instead of the computer randomly guessing, you guide it by telling whether its guess is **Higher, Lower, or Correct**.

---

## 🕹️ How It Works

1. Enter the **lowest** and **highest** values of your range.
2. NumHunt calculates the middle value of the range.
3. Tell the computer:
   - `H` → Your number is **Higher**
   - `L` → Your number is **Lower**
   - `Y` → The guess is **Correct**
4. The range is narrowed after every response.
5. NumHunt keeps guessing until it finds your number.

### Example

```text
Welcome to NumHunt!

Enter the lowest value: 1
Enter the highest value: 100

Current Range: [1 - 100]
My guess: 50
Your response (H/L/Y): H

Current Range: [51 - 100]
My guess: 75
Your response (H/L/Y): L

Current Range: [51 - 74]
My guess: 62
Your response (H/L/Y): Y

Got it! Your number was 62.
```

---

## 🧠 Concept Used

The main logic behind NumHunt is **Binary Search**.

At every step, the program divides the possible range and eliminates half of the remaining numbers based on the user's response.

This makes the guessing process much more efficient than random guessing.

---

## 🛠️ Built With

- **C**
- `stdio.h`
- `ctype.h`
- Binary Search Logic

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/suprio-dev/NumHunt.git
```

Navigate into the project:

```bash
cd NumHunt
```

Compile:

```bash
gcc main.c -o numhunt
```

Run:

### Windows
```bash
numhunt
```

### Linux / macOS
```bash
./numhunt
```

---

## 📚 What I Practiced

While building NumHunt, I practiced:

- `while` loops
- Conditional statements
- User input with `scanf()`
- Character handling with `toupper()`
- Variables and arithmetic operations
- Binary search logic
- Input validation
- Building an interactive console program

---

## 👨‍💻 Contributors

**Jayant Kumar Rajgaria**

**Suprio Adhikary**

Learning, building, and getting better one project at a time. 🚀