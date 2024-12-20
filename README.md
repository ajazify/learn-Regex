Alright, Ajas! Let’s make this 30 minutes productive. Here's an idea: **"Learn the basics of Regular Expressions (Regex)"**. Regex is a super useful skill for validating inputs, searching, and manipulating text, which is often essential for app development, especially in Flutter.

---

### Why Regex?

-   Validate email, phone numbers, PAN, Aadhaar, etc.
-   Extract or replace specific data in strings.
-   Speed up debugging and testing by writing concise pattern-matching logic.

---
### What We'll Cover in 30 Minutes:

1.  **Basics of Regex Syntax** (10 minutes)
2.  **Practical Use Cases** (10 minutes)
3.  **Interactive Practice** (10 minutes)

---

Alright, Ajas! Let’s make this 30 minutes productive. Here's an idea: **"Learn the basics of Regular Expressions (Regex)"**. Regex is a super useful skill for validating inputs, searching, and manipulating text, which is often essential for app development, especially in Flutter.

----------

### Why Regex?

-   Validate email, phone numbers, PAN, Aadhaar, etc.
-   Extract or replace specific data in strings.
-   Speed up debugging and testing by writing concise pattern-matching logic.

----------


### 1. **Basics of Regex Syntax**

#### Key Patterns:

| Pattern |Description  | Example |
|--|--| --|
| . | Any single character | `a.c` → `abc` |
| * | Zero or more of preceding | `ab*c` → `abc` |
| + | One or more of preceding | `ab+c` → `abbc` |
| ? | Optional character | `colou?r` → `color`/`colour` |
| \d | Any digit (0–9) | `\d{3}` → `123` |
| \w | Any word character | `\w+` → `hello1` |
| [abc] | Any of a, b, or c | `b[aeiou]g` → `bag` |
| ^ | Start of string | `^abc` |
| $ | End of string | `xyz$` |


### 2. **Practical Use Cases**

#### Example 1: Validate Email

``` 
^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$`
```
---
#### Example 2: Validate Indian Phone Number

```
^[6-9]\d{9}$
```
---
#### Example 3: Extract Hashtags from Text

```
#(\w+)
```

---

### 3. **Interactive Practice**

#### Online Tools:

1.  **[Regex101](https://regex101.com/):** Visualize how your regex works.
2.  **[Regexr](https://regexr.com/):** Test and debug your patterns.

---
### Mini-Challenge for You:

Write a regex to:

1.  Validate a 6-digit OTP.
2.  Match dates in the format `dd-mm-yyyy`.

Let me know how it goes! 😊
