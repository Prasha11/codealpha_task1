# Student Grade Tracker — Java Console App

## Project Structure

```
StudentGradeTracker/
└── src/
    ├── Main.java           → Entry point, menu loop
    ├── Student.java        → Student model (id, name, subject, score, grade)
    ├── GradeManager.java   → ArrayList logic (add, remove, stats)
    └── ReportPrinter.java  → All console output and report formatting
```

## How to Compile & Run

### Step 1 — Compile
Open terminal in the `src/` folder and run:
```
javac *.java
```

### Step 2 — Run
```
java Main
```

## Features
- Add students with name, subject, and score
- View all students in a formatted table
- Summary report: average, highest, lowest score
- Grade distribution bar chart (A/B/C/D/F)
- Remove a student by ID
- Input validation throughout

## Grade Scale
| Grade | Score Range |
|-------|-------------|
| A     | 90 – 100    |
| B     | 80 – 89     |
| C     | 70 – 79     |
| D     | 60 – 69     |
| F     | 0  – 59     |
