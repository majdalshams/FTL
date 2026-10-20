# My FTL Syria Programme Journey: AI for Climate

Welcome to my learning journal for the **Frontier Tech Leaders (FTL) Syria Programme – AI for Climate**!

This repository documents my progress, key takeaways, and projects throughout this 3.5-month intensive program running from September to December 2026. The program is a unique collaboration between the UNDP, the UNDP Istanbul International Center for Private Sector in Development (ICPSD), and Damascus University, supported by the German Federal Ministry for Economic Cooperation and Development (BMZ) through KfW.

The goal is to build a new generation of tech leaders by connecting technical skills in AI, Python, and data science to real-world challenges in climate, energy, and the environment.

---

## 👨‍💻 About Me

I'm Ahmad Deeb, a passionate learner on a mission to leverage technology for sustainable development.

- **GitHub:** [@AhmedGDeeb](https://github.com/AhmedGDeeb)
- **LinkedIn:** [Ahmad Deeb](https://www.linkedin.com/in/ahmad-deeb-13699b39a/)

---

## 🗓️ Programme Schedule & Progress

The program is structured into several key phases. I will update this section as we progress.

| Phase / Module | Status | Key Topics |
| :--- | :---: | :--- |
| **Python Bootcamp** | 🔄 **In Progress** | Python syntax, Data Types, Variables, Operators, Control Flow, Functions |
| **Python Hackathon** | ⏳ Not Started | Group-based problem solving and presentation |
| **Data Analysis & SDG** | ⏳ Not Started | Data manipulation, analysis techniques, peer coding |
| **Applied Machine Learning** | ⏳ Not Started | Regression, Classification, Clustering, Model Development |
| **Applied Dev & Deployment** | ⏳ Not Started | Git, GitHub, Command Line, Docker, APIs, Model Integration |
| **Specialized Sessions** | ⏳ Not Started | Cybersecurity, AI Security, AI for Climate, Smart Grids |
| **Capstone Project** | ⏳ Not Started | Literature review, Problem statement, Model development, Final Presentation |
| **Professional Certifications**| ⏳ Not Started | Power Systems, Wireless Networking, IoT, Climate Monitoring |

**Key Programme Timelines:**
- **Program Duration:** September - December 2026
- **Python Hackathon:** September 28 - October 2, 2026
- **Capstone Final Presentation:** December 22-23, 2026

---

## 📚 Session Notes & Key Learnings

This section is my personal knowledge base. I'll add key takeaways from each session here. All code and exercises will be in my main [Colab Notebook](https://colab.research.google.com/github/AhmedGDeeb/FTL/blob/main/tasks/FTL_Tasks_ahmad_deeb.ipynb).

---

### Day 1: Welcome & Python Intro (Sep 14, 2026)

**Key Takeaways:**

- **Welcome & Program Overview:** The session introduced the FTL Syria Programme, its mission to apply frontier technologies like AI to climate challenges, and its structure over the next three months.
- **Program Logistics:** We learned about the timeline, the 70% minimum attendance requirement, access to a Coursera license, and the importance of the final Capstone project.
- **Python Bootcamp Launch:** The Python bootcamp will consist of eight sessions over two weeks, designed to build a foundation for the more advanced machine learning modules.
- **Tools Introduction:** The primary tools for the program are **Google Colab** for coding and **GitHub** for version control and sharing projects.
- **Python Fundamentals:** We kicked off the technical part by learning the absolute basics of Python:
    - **Variables:** Names that refer to objects in memory.
    - **Data Types:** Introduction to `int`, `float`, `string`, `list`, `dict`, and `boolean`.
    - **Dynamic Typing:** Python automatically determines the type of a variable at runtime.
    - **Expressions and Operators:** Combining values and variables with arithmetic (`+`, `-`, `*`, `/`) and assignment (`=`) operators.

- **My Code & Exercises:** [Link to my Day 1 Notebook](https://colab.research.google.com/github/AhmedGDeeb/FTL/blob/main/tasks/FTL_Tasks_ahmad_deeb.ipynb)

---

### Day 2: Session 1 — Functions, Lambda & Control Flow (Sep 15, 2026)

**Key Takeaways:**

- **Review of Day 1:** We quickly recapped variables, data types, and basic operators.
- **Control Flow:** The main topic was controlling the flow of a program.
    - **Conditional Statements:** Using `if`, `elif`, and `else` to execute code based on certain conditions.
    - **Comparison Operators:** Using `==`, `!=`, `>`, `<`, `>=`, `<=` to compare values.
    - **Logical Operators:** Using `and`, `or`, and `not` to combine multiple conditions.
- **Functions — Basics:**
    - **Definition:** A function is a reusable block of code that performs a specific task.
    - **Syntax:** Defined using `def function_name(parameters):` followed by an indented block.
    - **Return Values:** Functions can return values using the `return` keyword; if no `return` is used, the function returns `None`.
    - **Parameters vs. Arguments:** Parameters are the placeholders in the function definition; arguments are the actual values passed when calling the function.
    - **Scope:** Variables defined inside a function are local to that function and cannot be accessed outside it.
- **Lambda Functions:**
    - **Definition:** A lambda function is a small, anonymous function defined with the `lambda` keyword.
    - **Syntax:** `lambda arguments: expression`
    - **When to Use:** Best for short, one-line operations where a full `def` function would be overkill.
    - **Example:** `square = lambda x: x ** 2`
    - **Common Use Cases:** Passing a function as an argument (e.g., to `map()`, `filter()`, `sorted()`), inline calculations.
- **Practice:** We wrote small functions and lambda expressions to solve simple problems (e.g., unit conversions, basic calculations).
- **My Code & Exercises:** [Link to my Day 2 Notebook](https://colab.research.google.com/github/AhmedGDeeb/FTL/blob/main/tasks/FTL_Tasks_ahmad_deeb.ipynb)

---

### Day 3: Session 2 — Strings & Files (Sep 16, 2026)

**Key Takeaways:**

- **Exercise Review & Peer Feedback:** We reviewed our previous exercise (the BMI calculator and treasure-hunt game). I presented my **function-oriented BMI calculator** (with unit conversions, health categories, and CLI interaction) and a **randomly generated treasure-and-trap grid game** (with boundary checks and user attempts). The facilitator asked me to share my solution with the group for peer review and comments. The key lesson: combine the best elements from different approaches.

- **Python Strings — Representation & Core Operations:**
    - **Definition:** A string is a **sequence of characters** enclosed in single, double, or triple quotes.
    - **No Separate Character Type:** In Python, there is no `char` type — a single character is just a string of length 1.
    - **Immutability:** Strings cannot be changed in place; operations create new strings. Demonstrated with `id()` — the memory address changes after concatenation.
    - **Indexing:** Each character has an index starting from `0` (zero-based); negative indices count from the end (`-1` = last character).
    - **Concatenation:** Combine strings with `+`.
    - **Repetition:** Repeat strings with `*`.
    - **Length:** Use `len()` to count characters.

- **String Indexing & Slicing:**
    - **Indexing:** Access individual characters with `string[index]`.
    - **Slicing:** Extract a range with `string[start:stop:step]`. The **stop index is exclusive** (not included). Defaults: start=`0`, stop=end, step=`1`.
    - **Negative Indexing:** Access from the end (`-1` = last character).
    - **Example:** `"Monty Python"[0:4]` returns `"Mont"`; `"frontier"[0:4]` returns `"fron"`.

- **String Methods & Object Inspection:**
    - **Common Methods:** `.upper()`, `.lower()`, `.replace()`, `.split()`, `.find()`, `.startswith()`, `.endswith()`, `.join()`.
    - **`dir()`:** Lists all available methods for an object — a great way to explore (e.g., `dir('Lamacun')`).
    - **`type()`:** Confirms the data type (e.g., `type(s)` returns `str`).
    - **Parsing Example:** Extracting the username from an email using `.find("@")` and slicing: `email[0:findex]` returns `"john.doe"`.

- **String Comparisons & Boolean Checks:**
    - **Equality:** `==` and `!=` compare strings (e.g., `'Helo' == 'Hello'` returns `False`).
    - **Prefix/Suffix:** `.startswith()` and `.endswith()` return `True`/`False`.
    - **Use Case:** Filtering or validating text data.

- **Loop-Based Vowel Counting:**
    - **Approach:** Normalize to lowercase, iterate through each character, increment a counter when a vowel is found.
    - **Two Implementations:** One with a `while` loop (`count_vowels_while`), one with a `for` loop (`count_vowels_for`) — same logic, different syntax.

- **Type Annotations (Optional but Good Practice):**
    - Python is **dynamically typed**, so annotations are not required.
    - **Why Use Them:** Document expected types, support error handling, improve readability.
    - **Example:** `def count_vowels(text: str) -> int:`

- **Palindrome Exercise:**
    - **Definition:** A word, phrase, or number that reads the same forward and backward (ignoring spaces, punctuation, and capitalization).
    - **Approach:** Clean the input with `''.join(c for c in input_string if c.isalnum()).lower()`, then use `left` and `right` indices to compare characters from opposite ends, moving inward.
    - **Two Versions:** One using a `while` loop (`is_palindrome_while`), one using a `for` loop (`is_palindrome_for`).
    - **Example:** `"A man, a plan, a canal, Panama"` is a palindrome.

- **Python File Concepts & Opening Files:**
    - **Why Files Matter:** Data comes from different sources — we need to read, write, and append. Console input uses primary memory (RAM); files use secondary memory.
    - **Built-in `open()` Function:** `open(filepath, mode)` returns a **file handle** (`_io.TextIOWrapper`) providing methods to interact with the file.
    - **File Modes:**
        - `"r"` — Read (default)
        - `"w"` — Write (creates file, **replaces** existing content)
        - `"a"` — Append (adds to the end, **preserves** existing content)
        - `"b"` — Binary mode (for images, executables)
    - **Colab Note:** Mount Google Drive with `from google.colab import drive; drive.mount('/content/drive')` to access files.

- **Reading Files:**
    - **`.read()`** — Reads the entire file as a single string.
    - **`.readline()`** — Reads one line (the first line).
    - **`.readlines()`** — Reads all lines into a list.
    - **Looping:** Use a `for` loop with `enumerate()` to read specific lines or process line-by-line with numbering.

- **Writing & Appending Files:**
    - **Write Mode (`"w"`):** Replaces existing content; creates a new empty file if it doesn't exist.
    - **Append Mode (`"a"`):** Adds new content at the end without erasing; creates a new file if it doesn't exist.
    - **Best Practice:** Use the `with` statement — it automatically closes the file when the block completes, so no explicit `.close()` is needed.

- **Listing Files in a Directory:**
    - Use `os.listdir(basepath)` to iterate over every item (files, directories).
    - Use `os.path.isfile(os.path.join(basepath, entry))` to check if a path points to a regular file.

- **Error Handling for File Operations:**
    - **Problem:** `FileNotFoundError` when the path or filename is incorrect.
    - **Solution:** Use `try`/`except` to catch errors and provide a helpful message.
    - **Example:**
      ```python
      try:
          fhand = open(filept, "r")
          content = fhand.read()
          print(content)
      except:
          print('File Not found check again: ', filept)
          quit()
      ```

- **My Code & Exercises:** [Link to my Day 3 Notebook](https://colab.research.google.com/github/AhmedGDeeb/FTL/blob/main/tasks/FTL_Tasks_ahmad_deeb.ipynb)

---

### Day 4: Session 3 — Data Structures (Sep 17, 2026)

**Key Takeaways:**

- **Data Structures Overview:**
    - A data structure is a way of storing and organizing data so it can be accessed and updated efficiently.
    - Classified into **Linear** (lists, tuples) and **Non-linear** (dictionaries).

- **Python Lists:**
    - **Definition:** Ordered collections that can contain mixed data types. They are similar to arrays in other languages but with more capabilities.
    - **Properties:**
        - **Ordered:** Maintain the order of data insertion (e.g., `ordered_list[0]` returns the first item).
        - **Changeable (Mutable):** Items can be modified after creation (e.g., `ordered_list[0] = 'mango'`).
        - **Heterogeneous:** Can contain data of different types (e.g., `['apple', 100, 3.14, True, ['sub-list', 'elements']]`).
        - **Allows Duplicates:** Duplicate data is permitted (e.g., `['apple', 'apple', 'banana', 'cherry', 'banana']`).

- **List Methods:**
    - **`.append(item)`** — Adds a single item to the end of the list. If the item is a list, it is added as a nested list.
    - **`.extend(iterable)`** — Adds multiple items from an iterable to the end, flattening them into the list.
    - **`.sort(reverse=True/False)`** — Sorts the list in place. `reverse=True` sorts in descending order.
    - **`len(list)`** — Returns the number of items in the list.

- **List Operations:**
    - **`+` (Concatenation):** Combines two lists into a new list (e.g., `[1, 3, 3] + [4, 4, 6]` = `[1, 3, 3, 4, 4, 6]`).
    - **`*` (Repetition):** Repeats a list a given number of times (e.g., `[1, 3, 3] * 3` = `[1, 3, 3, 1, 3, 3, 1, 3, 3]`).

- **List Slicing:**
    - Format: `list[start:end]` — starts at `start` and goes up to, but does **not** include, `end`.
    - **Negative Slicing:** `numbers[-3:]` returns the last three items.
    - **Example:** `numbers[2:4]` on `[0, 1, 2, 3, 4, 5]` returns `[2, 3]`.

- **Accessing List Elements:**
    - Items are identified by their position, starting with `0`.
    - **Negative Indexing:** `dogs[-1]` returns the last element; `dogs[-2]` returns the second-to-last.

- **Lists and Loops:**
    - **`for` Loop:** Iterates over each item in the list (e.g., `for dish in dishes: print('I love ' + dish + ' very much')`).
    - **`enumerate()`:** Tracks the index of each item during iteration (e.g., `for index, dish in enumerate(dishes): print('Dish Number: ' + str(index) + ' ' + dish)`).

- **Lists and Strings:**
    - **`.split()`** — Breaks a string into a list of words (e.g., `"Python for Everybody".split()` returns `['Python', 'for', 'Everybody']`).
    - **`.join()`** — Combines a list into a string (e.g., `' '.join(words)` returns `"Python for Everybody"`).

- **Dictionaries:**
    - **Definition:** Store data values in **key:value** pairs. General syntax: `{key_1: value_1, key_2: value_2}`.
    - **Characteristics:**
        - **Keys are unique** — no duplicates allowed.
        - **No index** — not ordered by position; the key is the default iterator used to retrieve values.
        - **Mutable (changeable)** — values can be modified (e.g., `fruits_dict['apple'] = 4`).
        - Accessing a non-existent key raises a **`KeyError`** (e.g., `fruits_dict[0]`).

- **Dictionary Methods:**
    - **`.keys()`** — Returns all keys (e.g., `dict_keys(['apple', 'oranges', 'mangos'])`).
    - **`.values()`** — Returns all values (e.g., `dict_values([4, 2, 3])`).
    - **`.items()`** — Returns all key:value pairs as tuples (e.g., `dict_items([('apple', 4), ('oranges', 2), ('mangos', 3)])`).

- **Common Dictionary Operations:**
    - **Adding new key-value pairs:** `african_countries['Nigeria'] = 'Abuja'`.
    - **Modifying values:** `african_countries['Cameroon'] = 'Yaounde'`.
    - **Removing key-value pairs:** `del african_countries['Cameroon']`.
    - **Modifying keys:** Two steps — create a new key with the old value, then delete the old key (e.g., `african_countries['Niger'] = african_countries['Nigeria']; del african_countries['Nigeria']`).

- **Dictionaries and Loops:**
    - **Loop through all key-value pairs:** `for country, capital in african_countries.items():`.
    - **Loop through all keys:** `for key in my_dict.keys():` (or simply `for key in my_dict:`).
    - **Loop through all values:** `for value in my_dict.values():`.

- **Tuples:**
    - **Definition:** Ordered, **immutable** collections — like lists that can never be changed after creation. Can contain mixed data types.
    - **Creating Tuples:** `sample_tuple = (1, 2, "Python", 3.5)`; convert from a list with `tuple(['Veery', 'Eastern Meadowlark', 10, 25, True])`; blank tuple with `tuple()`.
    - **Accessing Elements:** Same indexing as lists (e.g., `c_tup[2]` returns `'South Africa'`).
    - **Slicing:** Same syntax as lists (e.g., `c_tup[1:4]` returns `('Egypt', 'South Africa', 'Ghana')`).
    - **Converting between Lists and Tuples:** `tuple(sample_list)` and `list(converted_tuple)`.
    - **Tuples as Return Values:** Functions can return multiple values as a tuple (e.g., `def min_max(numbers): return (min(numbers), max(numbers))`).

- **Dictionaries and Tuples (Advanced):**
    - **Sorting by key:** `sorted(word_freq.items())`.
    - **Sorting by value:** `sorted(word_freq.items(), key=lambda item: item[1], reverse=True)` — uses a lambda to select the value for sorting.

- **Assignments:**
    - **List Assignment (Party):** Maintain a guest list using Python lists — add guests, remove guests, and check who's on the list.
    - **Advanced Party Guest Manager:** Build a guest management system using dictionaries and tuples:
        1. Initialize an empty `guests` dictionary where each guest has a name, age, and email.
        2. Add guests using tuples: `"Alice", 28, "alice@email.com"`, `"Bob", 35, "bob@email.com"`, `"Charlie", 30, "charlie@email.com"`. Use the name as the key and `(age, email)` as the value.
        3. Update the list: add `"David", 22, "david@email.com"` and remove `"Bob"`.
        4. Create `get_guest_info(guest_name)` — returns a formatted string if the guest is on the list, otherwise a "not on the guest list" message.
        5. Display the total number of guests.
        - **Extensions:** Allow user input for new guests, display guests in order of age, and handle duplicate guest names by prompting to update or skip.

- **My Code & Exercises:** [Link to my Day 4 Notebook](https://colab.research.google.com/github/AhmedGDeeb/FTL/blob/main/tasks/FTL_Tasks_ahmad_deeb.ipynb)

### Day 5: Session 4 — Working with Scientific Data in Python / Intro to OOP (Sep 21, 2026)

**Key Takeaways**
1. Course Plan & Capstone Projects
    - The week includes: continued Python material, a coding session, a ninth session, and a **Wednesday coding challenge**.
    - **Capstone projects**: Participants can choose their own topics. The instructor will provide optional problem suggestions and guidelines for documenting the problem and proposed solution.
    - Submission options:
    - **No GitHub**: Submit a Python notebook or script via email.
    - **With GitHub**: Upload work and send the link to the instructor.

2. Review of Lists, Loops, Dictionaries, Strings & Tuples
    - **Lists + Loops**: `for` loops iterate over each item in a list.
    - **`enumerate()`**: Exposes the index of each item during iteration.
    - **String ↔ List conversion**:
    - `.split()` — breaks a string into a list of words
    - `.join()` — combines a list into a string
    - **Dictionaries**: Key-value collections with unique keys; demonstrated reading, changing, adding, and removing entries.
    - **Looping through dictionaries**: Process keys, values, or complete key-value pairs.
    - **Tuples**: Ordered, immutable collections; demonstrated creation, conversion from lists, indexing, slicing, and use for preserving unchangeable values.

3. Guest-List Application Demonstration (Abdulrahman Abdulkader)
    - Presented a guest-list app that:
    - Separated data operations from command-line display and control logic
    - Handled empty lists and errors gracefully
    - Used a **dictionary to map menu choices to functions**
    - **Function references**: George Al Issa asked how the dictionary referenced functions. Abdulrahman explained that functions are objects whose references can be stored and later invoked through dictionary keys.

4. Transition to Object-Oriented Programming (OOP)
    - OOP helps organize larger programs and prevents code repetition.
    - **Core terminology**:
    - **Class**: A template/blueprint defining attributes and behavior
    - **Attribute**: A variable within a class
    - **Method**: A function within a class
    - **Object**: A particular instance of a class
    - **Constructor**: Runs when an object is created
    - **Inheritance**: Extending a class to make a new class
    - **Encapsulation & Abstraction**: Deferred to later sessions

5. Python Objects & Built-In Classes
    - In Python, **everything is an object**.
    - Examples:
    - `type("a")` → `str` class
    - `type(2.2)` → `float` class
    - `type(5)` → `int` class
    - Lists belong to the `list` class
    - Built-in objects (strings, integers, floats, lists) expose methods defined by their classes.

6. Creating a Custom Dog Class
    - Started with an **empty class** using `pass` as a placeholder (Python doesn't allow empty class bodies).
    - Created an **instance** and checked its type.
    - Progressed from an empty class to one with attributes and methods.

7. Instance Attributes & Methods
    - **`__init__`**: Constructor method to initialize attributes when a new instance is created.
    - **`self`**: Represents the individual object/instance.
    - **Instance attributes**: Belong to each individual object (e.g., a dog's name and age).
    - **Methods**: Define behavior (e.g., eating, sleeping, barking).
    - Example: A dog's `tired` state controlled whether it would sleep or play.

8. Class Attributes & Inheritance
    - **Class attributes**: Defined outside the constructor; shared by all instances of the class (e.g., `species = "canine"`).
    - Useful for storing constants and values common to all instances.
    - **Inheritance**: Introduced as a future topic — allows a new class to reuse attributes and behaviors from an existing class.
    - **Encapsulation and abstraction**: Deferred.

9. Practice Exercises & Submission Process
    - Instructor shared **class exercises** for participants to complete independently.
    - Exercises will be reviewed at the beginning of the next session.
    - **Submission options** (clarified for Amjad Shekhani):
    - Email a Python notebook or script
    - Submit a GitHub link
    - Instructor planned to share materials earlier before future sessions.


### Day 6: Session 5 — OOP Continued, Regex & Web Scraping (Sep 22, 2026)

**Key Takeaways**

1. Exercise Distribution & Deadline
    - Three exercises were emailed to students.
    - **Deadline extended to Friday, 25 September 2026.**
    - Submission options:
    - Jupyter/Colab notebook (.ipynb)
    - Python script (.py)
    - GitHub repository
    - Upload to Google Drive/OneDrive and share the link
    - If a function is created, show the calling stage in the submission.

2. Evaluation & Peer-Coding
    - This exercise is part of **continuous evaluation** but is **not shown on the certificate** — it just confirms you pass and continue.
    - The **hackathon** is the biggest evaluation.
    - **Peer-coding** will come later (after the hackathon, likely during the data analysis weeks).
    - Order: individual exercise → hackathon → peer-coding.

3. Exercise Clarifications (from Amjad's questions)
    - **"List of dictionaries"**: A list containing dictionaries — one dictionary per city with keys `name`, `temperature`, `humidity`, `rainfall`.
    - Data can be self-created (simple) or from an API/external dataset (optional, not graded higher).
    - Functions are **optional** unless explicitly mentioned in the exercise.
    - The missing temperature value is **intentional** — to practice `continue`, count valid observations, and handle incomplete data.
    - "Valid observations" = cities with a temperature value present.
    - Temperature classification can be done with an `if` statement inside or outside a function — open to you.

---

**OOP Concepts Continued**

4. Inheritance
    - A new class (child/subclass) inherits attributes and methods from an existing class (parent/base class).
    - Benefits: code reuse, extension of existing classes, hierarchy.
    - Example: `Dog` (parent) → `GoldenRetriever` (child) inherits name, age, tired state, and methods.
    - In Python, calling parent methods does **not** require `super` — child objects can call inherited methods directly.
    - (Contrast with Java, where `super.method()` is used.)

5. Encapsulation
    - Combining data (attributes) and methods inside a class, while **restricting direct access** to internal data.
    - Python convention: prefix with `_` or `__` for "private" attributes.
    - `__balance` (double underscore) is name-mangled — not directly accessible.
    - Access is controlled through **public methods** (e.g., `deposit()`, `check_balance()`).
    - **Example**: A bank balance — users must deposit through a method, not set the balance directly.
    - Similar to `private`/`public` in C++.

6. Abstraction
    - Hiding complex implementation details and exposing only what's necessary.
    - Uses the `abc` module (`ABC`, `abstractmethod`).
    - An **abstract base class** cannot be instantiated directly — a subclass must implement the abstract methods.
    - **Analogy**: Driving a car — you use the steering wheel, brake, and accelerator without knowing how the engine, fuel, or transmission work.

7. Polymorphism
    - Different classes can use the **same method name** but produce different behavior.
    - Example: `Animal` (parent) has `speak()`. `Dog.speak()` returns "wolf", `Cat.speak()` returns "meow".
    - Same method name, different outputs depending on the object's class.

---

**Regular Expressions (Regex)**

8. Introduction to Regex
    - A pattern (character or sequence) used to **match patterns in text**.
    - Python module: `re`.
    - Uses: data cleaning, formatting, extracting emails, phone numbers, URLs, etc.
    - Regex is case-sensitive by default (as far as the session clarified).

9. `re.search()`
    - Searches a string for a match and returns the **first match**.
    - Returns `None` if no match found.
    - Can be wrapped in an `if` statement to check if a pattern was found.
    - Can be applied row-by-row to CSV data using a loop.

10. `re.findall()`
    - Returns a **list of all matches** of the pattern in the string.
    - Useful for large datasets.
    - Example: Finding all words that start with "A" and end with "C".

11. Pattern Syntax Discussed

    | Symbol | Meaning |
    |---|---|
    | `^` | Start of line |
    | `$` | End of line |
    | `.` | Any character |
    | `\s` | Whitespace |
    | `\S` | Non-whitespace |
    | `*` | Zero or more repetitions of the preceding character |
    | `+` | One or more repetitions |
    | `?` | Zero or one repetition |
    | `[abc]` | Any of a, b, or c |
    | `[^abc]` | Not a, b, or c |
    | `[a-z]` | Range a to z |
    | `\d` | Any digit |
    | `\w` | Any alphanumeric character |
    | `\W` | Non-alphanumeric |

    - Patterns can be **combined**.
    - `*` means "zero or more of the character before it" — so `A*C` can match just "C".

---

**Web Scraping**
12. What is Web Scraping?
    - Extracting data from websites.
    - Fetch web page content and analyze/interpret it.

13. HTTP Methods (via `requests` library)
    | Method | Purpose |
    |---|---|
    | `GET` | Retrieve data from a server |
    | `POST` | Send/create new data on a server |
    | `PUT` | Update data on a server |
    | `DELETE` | Delete data from a server |

14. `requests` Library
    - Used to make HTTP requests.
    - Example: `requests.get(url)` retrieves web content.
    - Can use `dir()` to explore available methods.

15. Beautiful Soup
    - Library for pulling data out of HTML/XML.
    - Creates a parse tree to extract information.
    - Example: Extracting the page title.
    - Works alongside `requests`.

16. Data Formats & APIs
    - Web data usually comes as **JSON** or **XML**.
    - **API** = Application Programming Interface — allows applications to communicate and retrieve data over the internet.
    - APIs provide methods to collect data; detailed API instruction deferred to a later session.

17. Libraries Mentioned for Future Sessions
    - `pandas` — reading files, data frames
    - `os` — system operations
    - `requests` — HTTP requests
    - `BeautifulSoup` — HTML/XML parsing
    - `re` — regular expressions

---

**Hackathon Details**

18. Hackathon Overview
    - **Groups will be assigned** (not chosen by participants).
    - Group list and directions expected by **Friday 25th or Sunday 27th**.
    - Theme: **Climate-related problems** — solve with Python (other tools allowed).
    - All groups present at the end; top groups recognized.
    - Marking comes from the hackathon presentation.
    - Python is primary but not exclusive — HTML, other languages, APIs allowed if comfortable.
    - For the **final project** (biggest one), participants **can choose their own group** — but not for this hackathon.

19. Schedule
    - **Thursday, 24 Sep**: No session — time to work on exercises.
    - **Friday, 25 Sep**: Exercise submission deadline.
    - **Friday/Sunday**: Hackathon groups and directions sent.
    - **Next week**: Hackathon.
    - **Later**: Peer-coding during data analysis weeks.

### Day 7: Session 6 — Introduction to Databases, SQL & SQLite (Sep 23, 2026)

**Key Takeaways**

1.  **Final Introductory Python Session & Transition to Data Analysis**
    - This session concluded the introductory Python material.
    - Future sessions will still use Python but will focus on data-analysis techniques rather than programming fundamentals.
    - A short assignment is due by **Friday**.
    - **COSA licenses** will be distributed progressively from **Friday through Monday/Tuesday**. Participants will receive an email notification to log in or create an account.
    - Participants are encouraged to suggest additional courses that could be added.

2.  **Database Concepts & Data Models**
    - A **database** is a structured collection of data organized and stored systematically, typically in digital format. It is designed to store, retrieve, add, delete, and update data efficiently.
    - Benefits: efficiency, reliability, security, recovery, encryption, and backups.
    - A **data model** is the blueprint or design of a database. It defines how data is organized, stored, and how different pieces relate to each other (e.g., tables, columns, relationships, rules).
    - Databases solve the problem of storing, updating, and preserving data while avoiding duplication.

3.  **Relational Databases & SQL**
    - A **relational database** is a collection of one or more tables. Tables store data in rows (records) and columns (fields/attributes).
    - **SQL (Structured Query Language)** is the language used to communicate with a relational database. It allows you to create, store, retrieve, update, and delete information.
    - Basic SQL Operations:
        - `SELECT`: Retrieve data from one or more tables.
        - `INSERT`: Add new records.
        - `UPDATE`: Change the content of existing records.
        - `DELETE`: Remove records or tables.
    - Filtering data is done using the `WHERE` clause.
    - Results can be ordered using `ORDER BY` (ascending or descending).

4.  **SQLite & SQLite Browser**
    - **SQLite** is a lightweight, serverless, zero-configuration relational database. It is ideal for embedded devices and small applications, and is easily compatible with Python.
    - **SQLite Browser** is a visual, open-source GUI tool used to create, design, edit, and manage SQLite database files. It allows you to run SQL queries, view results, and export data.
    - Participants can download SQLite tools from the official website, selecting the appropriate version for their operating system and processor architecture (e.g., Windows 32-bit or 64-bit).

5.  **Practical SQL Demonstration**
    - **Creating a Table:**
        ```sql
        CREATE TABLE users (
            name VARCHAR(128),
            email VARCHAR(128)
        );
        ```
    - **Inserting Data:**
        ```sql
        INSERT INTO users (name, email) VALUES ('John', 'john@example.com');
        ```
    - **Retrieving Data:**
        ```sql
        SELECT email FROM users WHERE name = 'John';
        ```
    - **Updating Data:**
        ```sql
        UPDATE users SET email = 'new@example.com' WHERE name = 'John';
        ```
    - **Deleting Data:**
        ```sql
        DELETE FROM users WHERE name = 'John';
       ```
**More Hackathon Details**

6. **Hackathon Structure & Schedule**
    - **Groups will be assigned** (not chosen by participants).
    - Group list and directions expected by **Monday**.
    - Teams will receive members' contact details (name, email, WhatsApp) on Monday to coordinate.
    - **Theme:** Climate-related problems — solve with Python (other tools allowed).
    - **Schedule:**
        - **Monday:** Normal session — receive groups, introduce hackathon, define problem within provided scope.
        - **Tuesday:** Work independently (no session).
        - **Wednesday:** Session with another deliverable.
        - **Thursday:** Final presentations.
        - **Friday:** Available if additional time is needed.
    - All groups present at the end; top groups recognized.
    - Marking comes from the hackathon presentation.
    - For the **final project** (biggest one), participants **can choose their own group** — but not for this hackathon.

### Day 8: Session 7 – ... (Sep 28, 2026)

*(This section will be filled out after the session)*

- **Key Takeaways:**
    - ...

---


## 🎓 Capstone Project: [Project Title Placeholder]

This section is dedicated to my final Capstone project, a requirement for graduation. The project must connect AI and climate and follow a structured development process.

- **Project Idea:** _To be decided._
- **Literature Review:** _To be completed._
- **Problem Statement:** _To be defined._
- **Methodology & Models:** _To be developed._
- **Final Deliverable:** _A working prototype/analysis and a final presentation scheduled for December 22-23, 2026._

---

## 🙏 Acknowledgements

A huge thank you to the entire team and all the organizers for making this incredible learning opportunity possible.

- **[Cristóvăo Cacombe](https://www.linkedin.com/in/cristov%C3%A3o-cacombe-0b4514a3/)** (UNDP Course Guide) for his excellent instruction and guidance.
- The **UNDP**, the **SDG AI Lab**, and **Damascus University** for creating and delivering this comprehensive program.
- The **German Federal Ministry for Economic Cooperation and Development (BMZ)** and **KfW** for their generous support.
- My fellow participants for the collaboration and shared learning journey.

Special thanks to the **FTL Team** for their continuous support and coordination. This program is a life-changing opportunity, and I am committed to making the most of it.