# Python Tutorial for Beginners — Let’s Code!

## What is Python?  
Python is a popular programming language used everywhere—from web development to AI, games, and automation. It’s easy to read and write, which makes it perfect for beginners.

---

## Step 1: Setting Up Python
> 🦘 Skip if have installed

1. Download Python:  
   Go to https://python.org/downloads and download the latest version for your system (Windows, Mac, Linux).  
   When installing, make sure to check “Add Python to PATH” on Windows!

2. Check Installation:  
   Open your command line or terminal and type:
   ```bat
   python --version
   ```
   You should see the Python version number. If not, check your installation.

---

## Step 2: Writing Your First Python Program

Let’s start with the classic Hello, World!

Open any text editor (Notepad, VSCode, etc.) or the Python interactive shell (type python in terminal).

Type this:
```py
print("Hello, World!")
```

Save the file as hello.py if you’re using a text editor.

To run it, open terminal and type:
```bat
python hello.py
```

You’ll see:

`Hello, World!`

Congrats! You just ran your first Python program.

---

## Step 3: Python Basics

### Variables and Data Types

```py
name = "Your Name"    # String (text)  
age = 25           # Integer (whole number)  
height = 1.75      # Float (decimal number)  
is_coder = True    # Boolean (True or False)
```

### Print Variables
```py
print("Name:", name)  
print("Age:", age)
```

### Basic Math
```py
sum = 5 + 3  
product = 4 * 7  
print("Sum:", sum)  
print("Product:", product)
```
---

## Step 4: Getting Input from the User
```py
user_name = input("What’s your name? ")  
print("Nice to meet you, " + user_name + "!")
```
---

## Step 5: Conditional Statements (If, Else)
```py
age = int(input("How old are you? "))

if age >= 18:  
    print("You’re an adult!")  
else:  
    print("You’re a minor.")
```
---

## Step 6: Loops

### For Loop
```py
for i in range(5):  
    print("Number", i)
```
### While Loop
```
count = 0  
while count < 5:  
    print("Counting:", count)  
    count += 1
```
---

## Step 7: Functions

Functions help organize your code into reusable blocks.
```py
def greet(name):  
    print("Hello, " + name + "!")

greet("Your name")  
greet("Whatever")
```
---

## Step 8: Simple Project Idea — Guess the Number Game!
```py
import random

secret_number = random.randint(1, 10)  
guess = None

while guess != secret_number:  
    guess = int(input("Guess a number between 1 and 10: "))  
    if guess < secret_number:  
        print("Too low, try again.")  
    elif guess > secret_number:  
        print("Too high, try again.")  
    else:  
        print("You got it! The number was", secret_number)
```
---

## Bonus Tips to Keep Learning

- Practice daily with small projects or challenges.  
- Use Replit.com to code in your browser without setup.  
- Check out Automate the Boring Stuff https://automatetheboringstuff.com for fun real-world Python projects.  
- Ask questions and explore Python docs: https://docs.python.org/3

---

Happy coding! 🚀
