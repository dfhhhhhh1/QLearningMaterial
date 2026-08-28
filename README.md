# Quantum Computing with Qiskit: Eight-Week Course

An eight-week introduction to quantum computing, built on IBM Quantum Learning material and
Qiskit. Participants finish the course with a working environment, a grounding in the underlying
mathematics, and hands-on experience programming real quantum hardware.

**Start with [Start_Here.ipynb](Start_Here.ipynb).** It covers the module schedule, the weekly
rhythm, the setup you need before Module 1, and how work is submitted.

## Module Map

| Module | Topic |
|--------|-------|
| [1](module1/Schedule.ipynb) | Quantum Fundamentals & Environment Setup |
| [2](module2/Schedule.ipynb) | Quantum Mathematics and Notations with Linear Algebra |
| [3](module3/Schedule.ipynb) | Multiple Systems, Entanglement, and Interference |
| [4](module4/Schedule.ipynb) | Qiskit Programming and Circuits |
| [5](module5/Schedule.ipynb) | Quantum Algorithm Exploration |
| [6](module6/Schedule.ipynb) | Quantum Error Correction and Fault-Tolerant Quantum |
| [7](module7/Schedule.ipynb) | Quantum in Practice and Scaling to Utility |
| [8](module8/Schedule.ipynb) | Current Research and Future Planning |
| [Bonus](optional_material/Schedule.ipynb) | Other machine types, future algorithms, qLDPC codes *(optional)* |

## IBM Badge Practice Exams

Several modules line up with IBM Quantum Learning badges. [`badge_exams/`](badge_exams/README.md)
holds an optional, ungraded practice exam for each one: same format as the weekly quizzes, but
longer and pooled across every week the badge covers. The badge itself is earned on IBM's site.

| Badge | Covered by |
|-------|------------|
| [Basics of Quantum Information](badge_exams/Basics_of_Quantum_Information_Practice_Exam.ipynb) | Weeks 2-4 |
| [Fundamentals of Quantum Algorithms](badge_exams/Fundamentals_of_Quantum_Algorithms_Practice_Exam.ipynb) | Week 5 |
| Foundations of Quantum Error Correction | Week 6 *(not released yet)* |
| [Quantum Business Foundations](badge_exams/Quantum_Business_Foundations_Practice_Exam.ipynb) | Weeks 1, 5, 8 |

## Repository Layout

Each `moduleN/` folder follows the same structure:

| Path | Contents |
|------|----------|
| `moduleN/Schedule.ipynb` | The module entry point. Read this first. |
| `moduleN/README.md` | Short orientation for the module. |
| `moduleN/labs/` | Walk-through notebooks. Run them; they are not graded. |
| `moduleN/practices/` | Ungraded hands-on notebooks, with keys in `answers/`. |
| `moduleN/exercises/` | Graded assignments. Commit and push these. |
| `moduleN/answers/` | Answer keys. |
| `moduleN/resources/` | Slide decks, PDFs, reference material. |
| `moduleN/images/` | Figures used by the module's notebooks. |

Plus one shared folder:

| Path | Contents |
|------|----------|
| `badge_exams/` | Optional practice exams for the IBM badges, and their question banks. |

## Prerequisites

- Comfort with Python. You do not need prior quantum experience.
- Linear algebra helps but is not assumed, Module 2 builds what the course needs.
- An IBMid (free) and a working Qiskit install. Both are set up in Module 1.

## Expected Effort

3-4 hours per week.
