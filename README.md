# Expectation Decider 🚀📊🎯

## Project Overview 📚🧠

**Expectation Decider** is an educational data-analysis project that demonstrates probability concepts using a synthetic student dataset. The goal is to analyze probability patterns and answer instructor-style questions (random variables, contingency tables, conditional probability, Bayes' theorem, Venn diagrams, etc.) and produce an integrated analysis report. 🔍🧮✨

## Project Objective 🎯✅

You are given sample data for 200 students (generated to support the assignment). Using the dataset and appropriate statistical techniques, tasks include: explaining probability basics, calculating empirical and theoretical probabilities, constructing a probability distribution for a random variable, drawing a Venn diagram for attendance/study thresholds, building a contingency table for group discussion vs final exam outcomes, interpreting conditional probabilities, and applying Bayes' theorem. 📝📈🧩

## Dataset (fields) 🗂️📋

Each student record contains:

- `study_hours` — Number of hours a student studied per week ⏰📘
- `attendance` — Percentage attendance in lectures 🧑‍🏫👩‍🎓📆
- `group_discussion` — Participation in group discussions (Yes/No) 💬🤝
- `previous_test_score` — Marks out of 100 from the last internal test 🧪🔢
- `final_exam_pass` — Whether the student passed the competitive exam (Pass/Fail) ✅❌

Note: The dataset is expected to be generated (or synthesized) such that all assignment tasks can be completed. 🔁🎲

## Contents of this repository 📁🖇️

- `Expectation_Decider.ipynb` — Primary Jupyter notebook with analysis, visualizations, calculations, and narrative answers to the assignment prompts. 🧾📊
- This `README.md` — Project summary, how to run, and pointers. 📄✨

## Assignment Tasks Covered 🧩🔎

The notebook and supporting materials cover the following tasks from the assignment brief:

- Understanding the basics of probability and key terminology. 📚🔤
- Identifying empirical and theoretical probability scenarios and calculating values. 🧮📐
- Defining a random variable for the number of students passing out of 3 randomly-selected students, constructing its probability distribution, and computing mean and variance. 🎲📊
- Drawing a Venn diagram for:
	- students who study > 10 hours/week 📘➡️10+ hrs
	- students who attend > 80% of classes 🧑‍🏫➡️80%+
	- including the overlap (students who satisfy both). 🔗➕🔁
- Building a contingency table for `group_discussion` (Yes/No) vs `final_exam_pass` (Pass/Fail), and computing joint, marginal, and conditional probabilities. 🧾📈🔍
- Interpreting conditional probabilities and testing independence vs dependence. 🤔🔄
- Applying Bayes' theorem with the provided historical-statistics style numbers and showing step-by-step calculations. 📜🧠🔁

## How to run 🛠️💻

1. Install Python and Jupyter (or use JupyterLab / VS Code notebook support). 🐍💡

2. Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/Prath-Digital/Mathematics_and_Advanced_Statistics-PR.-2-Expectation-Decider.git
cd Mathematics_and_Advanced_Statistics-PR.-2-Expectation-Decider
``` 

3. Install typical data-analysis packages if you plan to run the notebook interactively:

```bash
python -m pip install -r requirements.txt
```

3. Open the notebook:

```bash
python -m notebook Expectation_Decider.ipynb
```

4. Run the cells in order — the notebook contains sections that import a synthetic dataset and then performs each required calculation and visualization. ▶️📈📊

## Notes on Reproducibility 🔁🔬

- All formulas, substitutions, and step-by-step calculations required by the assignment are shown in the notebook cells and visualized where applicable. 📝🧾📐

## Deliverables / Expected Output 🏁📦

- A written analysis (in the notebook) answering each numbered assignment item. 🧾✅
- Tables: contingency table for group discussion vs final exam pass, probability distribution table for the random variable. 📊📋
- Visuals: Venn diagram (or equivalent set visualization), bar charts or pie charts for marginal/joint distributions. 🥧📈
- A final summary highlighting which factors most affect passing probability. 🔍💡

## License ⚖️📜

See the repository [`LICENSE`](./LICENSE) at the workspace root for licensing information. 📄🔒