# 🔄 python-loops
*A collection of Python loop examples, tricks, and optimizations—from basic `for`/`while` loops to advanced iteration techniques.*

---

## � Quick Start
1. **Clone the repo**:
   ```bash
   git clone https://github.com/RadiantCoreLabs/python-loops.git
Explore examples:

/basics – Simple for, while, and nested loops.

/optimization – Faster alternatives (e.g., list comprehensions, map()).

/projects – Practical use cases (e.g., data processing, game loops).

📚 Examples
Basic Loops
python
# Classic for-loop
for i in range(5):
    print(f"Iteration {i}")

# While loop with condition
count = 0
while count < 3:
    print("Hello!")
    count += 1
Optimized Loops
python
# List comprehension (faster than append())
squares = [x**2 for x in range(10)]

# Using enumerate() for index + value
for idx, value in enumerate(["a", "b", "c"]):
    print(f"Index {idx}: {value}")
🏎️ Performance Tips
Avoid for i in range(len(list)) → Use for item in list or enumerate().

Prefer map()/filter() for large datasets (lazy evaluation).

Replace nested loops with itertools.product() when possible.

🤝 How to Contribute
Fork the repo.

Add your loop example (with comments!) in the relevant folder.

Submit a PR.

Looking for:

Real-world use cases (e.g., loops in ML/data analysis).

Creative loop hacks.

📜 License
MIT © [Sina Parsa]

