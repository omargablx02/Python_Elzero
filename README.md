# 🐍 Python Elzero — Course Notes & Assignments

![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)
![Lessons](https://img.shields.io/badge/Lessons-005%20%E2%86%92%20132-3498DB)
![Assignments](https://img.shields.io/badge/Assignments-01%20%E2%86%92%20132-98C379)
![Course](https://img.shields.io/badge/Course-Osama%20Elzero%20(Elzero%20Web%20School)-FF8C00)
![Status](https://img.shields.io/badge/Status-Completed%20(Course%201)-success)

> My personal **notes + practice code + assignment solutions** for **Osama Elzero's Python course** (Elzero Web School).
> Everything in this repo was typed, run and debugged by hand — then documented with comments in **English + Arabic**.

---

## 📌 What is this repo?

Two things, in one place:

| # | Asset | File / Folder | What it is |
|:-:|:--|:--|:--|
| 1 | **Full course notes** | `Course 1_last.py` | 5,300+ lines of explained code covering lessons **005 → 132** |
| 2 | **Assignment solutions** | `Assignments Python ElZero/` | 24 assignment files (lessons **01 → 132**) + practice modules & DB files |

The notes file is written in **"documentation-first" style**: every block of code is kept **commented out**, with a header for the lesson number and a short explanation above it. That way one file works as notes *and* as runnable code — you just uncomment the block you want to try.

---

## 🗂️ Repository structure

```
Python_Elzero/
├── Course 1_last.py                 # 📘 Full course notes — lessons 005 → 132 (5,303 lines)
├── Assignments Python ElZero/       # 📝 Assignment solutions
│   ├── 01 → 25-*.py                 #    one file per topic (see table below)
│   ├── 14-File_Handling/            #    File Handling practice + 40 generated txt files
│   ├── 17-python_modules/           #    Custom module practice (main.py ↔ my_mod.py)
│   ├── 24-SQLite/                   #    SQLite databases (index.db, Types.db)
│   ├── test/                        #    Scratch area (experiments + txt files)
│   ├── pylint.py                    #    Linting / code-quality practice
│   ├── settings.json                #    VS Code + "Better Comments" color config
│   └── *.png                        #    Pillow (PIL) image-manipulation practice
└── README.md
```

---

## 📘 1) The course notes — `Course 1_last.py`

| Metric | Value |
|:--|:--|
| Total lines | **5,303** |
| Comment / documentation lines | **4,095** (~77%) |
| Lines with **Arabic** explanations | **689** |
| Lesson headers | **005 → 132** |
| File size | ~201 KB |

**How it is organised:**

```python
# ? -------------------------------------- 045 ------------------------------------------------------
# --------------------------------------------------------------------
# -- Functions => Default Arguments ----------------------------------
# --------------------------------------------------------------------
# def say_hello(name = "Unknown"):
#     print(f"Hello {name}")
#
# say_hello()
# ! ملاحظة: القيمة الافتراضية بتتستخدم لما مبنبعتش الـ argument
```

* `# ? ---- NNN ----` → start of lesson **NNN**
* `# !` → important note / gotcha
* Everything else stays commented so the file never breaks when run.

---

## 📝 2) The assignments — `Assignments Python ElZero/`

| File | Topic | Lessons | LOC |
|:--|:--|:--:|--:|
| `01-Introduction And Variables.py` | Variables, data types, `print`, f-strings | 01 – 10 | 33 |
| `02-Strings And Methods.py` | Strings & string methods | 11 – 18 | 94 |
| `03-Numbers & Arithmetic Operators.py` | Numbers & arithmetic operators | 19 – 20 | 24 |
| `04-List_Methods.py` | Lists & list methods | 21 – 23 | 91 |
| `05-Tuples_Methods.py` | Tuples & tuple methods | 24 – 25 | 42 |
| `06-Set, Dictionary & Methods.py` | Sets, dictionaries & methods | 26 – 32 | 85 |
| `07-Operators & Type Conversion.py` | Operators & type casting | 33 – 37 | 43 |
| `08-User Input & Practice.py` | `input()` & practice | 38 – 40 | 25 |
| `09-Control Flow.py` | `if / elif / else` | 41 – 46 | 59 |
| `10-Loop While & Training.py` | `while` loops & training | 47 – 50 | 110 |
| `11- Loop For & Training.py` | `for` loops, nested loops, `break/continue` | 51 – 55 | 318 |
| `12-Function.py` | Functions, parameters, `return` | 56 – 59 | 79 |
| `13-Packing, Recursion, Lambda.py` | `*args`, `**kwargs`, recursion, lambda | 60 – 64 | 134 |
| `14-File_Handling/14-Files Handling.py` | File handling (read/write/append) | 65 – 68 | 132 |
| `15-Built In Functions.py` | Built-in functions (`len`, `range`, `sorted`, …) | 69 – 71 | 218 |
| `16-Map, Filter, Reduce.py` | `map`, `filter`, `reduce` | 72 – 75 | 93 |
| `17-Modules & Packages.py` | Modules & packages | 76 – 78 | 35 |
| `18-Date & Time.py` | `datetime` module | 79 – 80 | 23 |
| `19-Generators & Decorators.py` | Generators & decorators | 81 – 85 | 59 |
| `20-Collection Of Modules.py` | Collection of modules (`os`, `sys`, `random`, …) | 86 – 89 | 135 |
| `21-Error Handling & Debugging.py` | Exceptions, debugging & linting | 90 – 94 | 76 |
| `22-Regular Expression.py` | Regular expressions (`re`) | 95 – 102 | 50 |
| `23-Object Oriented Programming.py` | OOP: classes, inheritance, magic methods | 103 – 116 | 248 |
| `24-SQLite Database.py` | SQLite databases (`sqlite3`) | 117 – 127 | 104 |
| `25-Advanced Concepts.py` | `unittest`, random serials, advanced practice | 128 – 132 | 68 |

**Extra practice material**

* `14-File_Handling/` — 40 small `txt*.txt` files generated while practising read / write / append modes.
* `17-python_modules/` → `main.py` imports a custom `my_mod.py` (module creation practice).
* `24-SQLite/` → `index.db` and `Types.db` created during the SQLite lessons.
| `pylint.py` → code-quality / linting practice. · `test/` — scratch experiments.
| `*.png` → Pillow (PIL) image manipulation practice (`elzero-pillow.png`, `change_color*.png`).

---

## 🎨 3) Comment color coding — "Better Comments"

Every note uses **tagged comments** so the important parts pop out while reading. Tags and colors are defined in [`Assignments Python ElZero/settings.json`](Assignments%20Python%20ElZero/settings.json):

| Tag | Meaning | Color |
|:--|:--|:--|
| `!` | 🔴 Important note / warning / gotcha | `#FF2D00` |
| `?` | 🔵 Lesson header, question, section marker | `#3498DB` |
| `t~` | 🟠 Assignment / training header | `#FF8C00` |
| `*` | 🟢 Key idea / highlight | `#98C379` |
| `@@` | 🟢 Instruction step | `#09a30f` |
| `^^` | 🟡 Extra tip | `#d7a317` |
| `//` | ⚪ Disabled / old code (strikethrough) | `#474747` |

**Enable it in VS Code:**

1. Install the extension **Better Comments** (`aaron-bond.better-comments`).
2. Open *Settings (JSON)* and append the `better-comments.tags` block from `settings.json`.
3. Reload the window — the tags above will be colorized.

---

## ▶️ How to use / run

```bash
# 1) Clone
git clone https://github.com/omargablx02/Python_Elzero.git
cd Python_Elzero

# 2) Run an assignment file (Python 3.10+; developed on 3.13)
python "Assignments Python ElZero/01-Introduction And Variables.py"
```

> ⚠️ Most lines are **intentionally commented out** (they are notes). Uncomment the block you want to execute, run the file, then comment it back.

**Recommended setup**

* Python **3.13**
* VS Code + extensions: **Better Comments**, **Python**
* `pip install pylint` → for the linting practice in `21-Error Handling & Debugging.py` and `pylint.py`

---

## 🧠 Topics covered (checklist)

- [x] Variables, data types, type casting
- [x] Strings, lists, tuples, sets, dictionaries (+ their methods)
- [x] Operators, control flow (`if/elif/else`), `while` / `for` loops
- [x] Functions, packing (`*args` / `**kwargs`), recursion, lambda
- [x] File handling, built-in functions, `map` / `filter` / `reduce`
- [x] Modules & packages
- [x] Date & time, generators & decorators
- [x] Error handling & debugging (exceptions, `pylint`, `unittest`)
- [x] Regular expressions
- [x] Object-Oriented Programming (classes, inheritance, magic methods)
- [x] SQLite database
- [x] Advanced concepts & `unittest`

---

## 🤝 Credits & License

* Course by **Osama Elzero** — [Elzero Web School](https://elzero.org/) (Python course).
* This repo contains **my own notes, practice and solutions** written while following the course — shared as-is for anyone studying the same content.
* Free to use for learning. No warranty.

---

<details>
<summary><b>🇪🇬 نسخة عربية مختصرة (Arabic summary)</b></summary>

### الملف دا إيه؟
ريبو فيه **شرح كورس بايثون بتاع أسامة الزيرو (Elzero Web School)** بالكامل، مكتوب بإيدي ومتنفّذ ومترّتب، وفيه حلول الـ Assignments.

### المحتوى:
1. **`Course 1_last.py`** → ملف الشرح الكامل: **5,303 سطر**، فيهم **4,095 سطر كومنتات** و **689 سطر شرح بالعربي**، مغطّي الدروس من **005 لـ 132**.
   - كل درس بيبدأ بسطر: `# ? ---- رقم الدرس ----`
   - الكود كله **معلّق (comment)** عن قصد، عشان الملف يشتغل كـ Notes وكـ كود في نفس الوقت — تفكّ الكومنت عن الجزء اللي عايز تجرّبه وخلاص.
2. **`Assignments Python ElZero/`** → **24 ملف حلول** للـ assignments من **01 لـ 132** (كل ملف مغطّي مجموعة دروس)، ومعاهم:
   - `14-File_Handling/` → تدريب الـ Files + 40 ملف txt.
   - `17-python_modules/` → تدريب عمل Module خاص (`main.py` + `my_mod.py`).
   - `24-SQLite/` → قواعد بيانات SQLite.
   - `test/` → مساحة تجارب.

### الألوان (Better Comments):
فيه `settings.json` جاهز فيه إعدادات تلوين الكومنتات:
`!` أحمر (ملاحظة مهمة) · `?` أزرق (عنوان درس) · `t~` برتقالي (عنوان assignment) · `*` و `@@` أخضر · `^^` أصفر.
تركّب إضافة **Better Comments** في VS Code وتنسخ الإعدادات من `settings.json` وخلاص.

### التشغيل:
```bash
python "Assignments Python ElZero/01-Introduction And Variables.py"
```
> أغلب السطور معلّقة — فكّ الكومنت عن البلوك اللي عايز تشغّله.

</details>
