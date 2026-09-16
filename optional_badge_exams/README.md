# IBM Badge Practice Exams

Practice runs for the IBM Quantum Learning badges that this course lines up with. Open the
notebook for a badge and run it; it behaves like the weekly module quizzes (random draw, two
attempts per set, **New questions** to swap half the set), just longer and pooled across
everything the badge covers.

| Badge | Covered by | Practice exam | Questions come from |
|-------|------------|---------------|---------------------|
| [Basics of Quantum Information](https://quantum.cloud.ibm.com/learning/en/courses/basics-of-quantum-information) | Weeks 2-4 | [Basics_of_Quantum_Information_Practice_Exam.ipynb](Basics_of_Quantum_Information_Practice_Exam.ipynb) | the Module 2, 3, and 4 quiz banks |
| [Fundamentals of Quantum Algorithms](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/exam) | Week 5 | [Fundamentals_of_Quantum_Algorithms_Practice_Exam.ipynb](Fundamentals_of_Quantum_Algorithms_Practice_Exam.ipynb) | questions written against the badge course itself |
| [Foundations of Quantum Error Correction](https://quantum.cloud.ibm.com/learning/en/courses/foundations-of-quantum-error-correction/exam) | Week 6 | [Foundations_of_Quantum_Error_Correction_Practice_Exam.ipynb](Foundations_of_Quantum_Error_Correction_Practice_Exam.ipynb) | questions written against the badge course itself |
| [Quantum Business Foundations](https://quantum.cloud.ibm.com/learning/en/courses/quantum-business-foundations/exam) | Weeks 1, 5, 8 | [Quantum_Business_Foundations_Practice_Exam.ipynb](Quantum_Business_Foundations_Practice_Exam.ipynb) | the Module 1, 5, and 8 quiz banks |

## What these are and are not

- **Not graded, not required.** The course requirement is the weekly module quizzes (6 of 8 at
  90%). These exams are here only so you can gauge whether you are ready for IBM's real exam.
- **Not the badge.** Badges are earned by taking the exam on IBM Quantum Learning. They are yours
  to keep, independent of this course.
- **Not IBM's questions.** These are this course's own questions covering the same material. The
  pass mark shown (75%) is this course's practice bar, not IBM's — check the badge page for the
  score IBM currently requires.

Your best score on each exam is saved to `.quiz_progress.json` at the course root, the same file
the module quizzes use. Run the progress cells in [Start_Here](../Start_Here.ipynb) to see them.

## Requirements

`ipywidgets` (standard in JupyterHub). The controls only appear when the notebook is **run** in a
live kernel; a static preview will look empty.

## Files

Each badge has two files:

| File | What it is |
|------|------------|
| `<badge>_Practice_Exam.ipynb` | The notebook you run |
| `<badge>_exam_bank.json` | Its question bank. Prompts are base64-encoded and answers are stored only as salted hashes, so opening it does not hand you the answers. |

Both are generated. Instructors: see `_authoring/README.md` for how to rebuild them or add the
error-correction bank.
