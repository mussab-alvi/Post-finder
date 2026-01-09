# Post Word Finder 🧠🔍

This is a beginner-friendly Python script that allows users to search for a word within a predefined post. It performs a **case-insensitive match** and prints whether the word is present or not.

## 💡 Features
- Accepts user input via `input()`
- Converts both input and post to lowercase for accurate matching
- Uses `in` keyword for substring detection
- Friendly output messages

## 🧪 Sample Output
Enter word you want to search: Ai
Ai is present in this post !!!
Have a nice day :)


---

## 📜 Code Overview
```python
post = "Artificial Intelligence (AI) is transforming cybersecurity" \
       "by making threat detection, prevention, and response faster and more accurate."

a = input("Enter word you want to search: ")

if a.lower() in post.lower():
    print(a, "is present in this post !!!")
else:
    print(a, "is not present in this post")

print("Have a nice day :)")
```


🚀 How to run

for cloning:
git clone https://github.com/mussab-alvi/Post-finder.git

📚 Learning Goals
Practice string methods like .lower()

Understand conditional logic (if-else)

Build confidence with input/output operations

🧠 Author
Mussab Alvi  
BSCS Student | Python & C++ Learner | Internship Explorer

Linkdin profile:
www.linkedin.com/in/muhammad-mussab-alvi-450028392
















