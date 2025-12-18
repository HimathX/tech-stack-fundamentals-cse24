# Tech Stack Fundamentals Workshops

---

## Repository Structure

```
tech-stack-fundamentals-cse24/
├── README.md
├── WORKSHOP_OVERVIEW.md
├── SCHEDULE.md
├── Task 01/
│   ├── README.md
│   ├── task_instructions.pdf
│   └── submissions/
│       └── [Your_Name]/
│           └── index.html
├── Task 02/
│   ├── README.md
│   ├── task_instructions.pdf
│   └── submissions/
│       └── [Your_Name]/
│           └── index.html
└── Task 03/
    ├── README.md
    ├── task_instructions.pdf
    └── submissions/
        └── [Your_Name]/
            └── index.html
```

---

## How to Submit Your Work

### Step 1: Clone Repository

```bash
git clone https://github.com/SMILE-LABS/tech-stack-fundamentals-cse24.git
cd tech-stack-fundamentals-cse24
```

### Step 2: Create Your Submission Folder

**Naming Format:** `[First_Name]_[Last_Name]`

```bash
# Navigate to task submissions folder
cd "Task 01/submissions"

# Create your folder
mkdir Himath_Jayasinghe
cd Himath_Jayasinghe

# Create your HTML file
code index.html
```

**Examples:**
- `Himath_Jayasinghe/index.html`
- `Anusha_Perera/index.html`
- `Kamal_Silva/index.html`

### Step 3: Complete Your Task

Write your code in `index.html` according to the task instructions in the README.md of that task folder.

### Step 4: Commit and Push

```bash
# Return to repository root
cd ../../..

# Stage your changes
git add .

# Commit with clear message
git commit -m "Add Task 1: Himath Jayasinghe"

# Push to GitHub
git push
```

---

## Quick Reference

```bash
# Clone repository
git clone https://github.com/SMILE-LABS/tech-stack-fundamentals-cse24.git

# Create submission folder
cd "Task 01/submissions"
mkdir Your_Name
cd Your_Name

# Create index.html
code index.html

# Stage and commit
cd ../../..
git add .
git commit -m "Task 1: Your Name"
git push
```

---

## Troubleshooting

**Cannot push to repository?**
```bash
git remote set-url origin https://github.com/[your-username]/tech-stack-fundamentals-cse24.git
```

**Merge conflict?**
```bash
git pull origin main
git add .
git commit -m "Your message"
git push
```

---

Last Updated: 18th December 2025
