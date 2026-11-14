# Module 00: Python Programming Fundamentals

Welcome to Python Programming Fundamentals module! If you are completely new to programming or coming from a non-Python background, this module is your starting point. Python is the universal language of Artificial Intelligence and Data Science because of its readability and powerful ecosystem. 

This guide covers everything you need to know to write, understand, and execute Python code before moving into advanced machine learning and LLM architectures.

---

## 🎯 Module Objectives
By completing this module, you will master:
- Setting up your Python environment and writing your first scripts.
- Core data types, variables, and type casting.
- Conditional logic (`if`, `elif`, `else`) and loops (`for`, `while`).
- Structuring data using Lists, Tuples, and Dictionaries (essential for handling API payloads and JSON).
- Writing reusable blocks of code using Functions.
- Importing external packages and understanding modules.

---

## 1. Syntax Basics & Variables
A variable acts as a container for storing data values. Unlike statically typed languages (like C#), Python infers the data type automatically when you assign a value.

### Common Data Types:
* **String (`str`):** Text data enclosed in single or double quotes (e.g., `"Hello AI"`).
* **Integer (`int`):** Whole numbers (e.g., `42`).
* **Float (`float`):** Decimal numbers (e.g., `3.14`).
* **Boolean (`bool`):** Truth values (`True` or `False`).

```python
# Defining variables
model_name = "GPT-4o"          # String
context_window = 128000        # Integer
temperature = 0.7              # Float
is_production_ready = True     # Boolean

# Printing formatted strings (f-strings)
print(f"Model: {model_name} | Context Window: {context_window} tokens")
```

---

## 2. Control Flow: Making Decisions & Repeating Tasks

### A. Conditional Statements (`if`, `elif`, `else`)
Programs evaluate conditions to make runtime decisions.

```python
token_count = 45000

if token_count > 100000:
    print("Warning: Approaching context limit!")
elif token_count > 50000:
    print("Notice: Moderate context usage.")
else:
    print("Context usage is safe.")
```

### B. Loops (`for` and `while`)
Loops allow you to iterate over sequences or repeat execution.

```python
# Looping through a list of AI frameworks
frameworks = ["PyTorch", "TensorFlow", "Semantic Kernel", "LangChain"]

for framework in frameworks:
    print(f"Exploring framework: {framework}")
```

---

## 3. Data Structures: Lists & Dictionaries
In AI engineering, you constantly manipulate collections of data and JSON configurations. 

### A. Lists (`[]`): Ordered, mutable collections.
```python
supported_models = ["gpt-4o", "claude-3.5", "llama-3"]

supported_models.append("mistral-large")  # Add an item
print(supported_models[0])                # Access the first item: "gpt-4o"
print(f"Total models: {len(supported_models)}")
```

### B. Dictionaries (`{}`): Key-value pairs (ideal for JSON data structures).
```python
llm_config = {
    "provider": "Azure OpenAI",
    "model": "gpt-4o",
    "parameters": {
        "temperature": 0.2,
        "max_tokens": 1000
    },
    "streaming": True
}

# Accessing dictionary values
print(llm_config["provider"])
print(llm_config["parameters"]["temperature"])
```

---

## 4. Reusable Code with Functions
Functions bundle logic into reusable blocks, accepting inputs (arguments) and returning outputs.

```python
def calculate_cost(prompt_tokens: int, completion_tokens: int, cost_per_1k: float) -> float:
    """Calculates the estimated API cost based on token usage."""
    total_tokens = prompt_tokens + completion_tokens
    total_cost = (total_tokens / 1000) * cost_per_1k
    return total_cost

# Calling the function
estimated_cost = calculate_cost(1500, 500, 0.005)
print(f"Estimated API Cost: ${estimated_cost:.4f}")
```

---

## 5. Working with Modules and Libraries
Python's real power comes from its vast library ecosystem. You can bring external tools into your script using the `import` keyword.

```python
import math
import json

# Using a built-in module function
radius = 5
area = math.pi * math.pow(radius, 2)
print(f"Circle Area: {area:.2f}")

# Working with JSON data strings
data_string = '{"status": "success", "code": 200}'
parsed_data = json.loads(data_string)
print(parsed_data["status"])
```

---

## 🚀 Hands-On Exercises
1. **Model Selector Script:** Create a list of 4 AI models. Write a `for` loop that checks if a specific model name (e.g., `"gpt-4o"`) is in the list and prints a confirmation message.
2. **Configuration Parser:** Build a dictionary containing prompt metadata. Write a function that takes this dictionary as input and prints out a formatted summary of the configuration.
