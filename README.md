# 📘 Simple Knowledge Representation using facts + rules

## 👤Student Information
Name: Angel Wesonga<br>
Registration Number: 672296<br>
Course: Knowledge Based Sytems

## 🧠Overview
In this project, knowledge is represented using facts in the form of a tuple (subject, relation, object) and rules infer new information from existing facts, such as reptile and animal relationships.It also involves queries to get both given and inferred facts.The implementation is written in Python and executed in a Jupyter Notebook.

## 🧩Knowledge Representation

**Base Facts:**

"cobra", "is_a", "snake"<br>
"python", "is_a", "snake"<br>
"lizard", "is_a", "reptile"


**Rules:**

"snake -> reptile", snake_isa_reptile<br>
"reptile -> animal", reptile_isa_animal

## 🔄 Inference Process
New facts are derived from the existing facts using the defined rules.
These rules are used to get new knowledge, such as animal and reptile relationships.
The knowledge base is updated with any new facts until there are none left.
Queries can then be run to get both the original and inferred facts from the knowledge base.

## ✅Expected Output
All facts:
('cobra', 'is_a', 'animal')<br>
('cobra', 'is_a', 'reptile')<br>
('cobra', 'is_a', 'snake')<br>
('lizard', 'is_a', 'animal')<br>
('lizard', 'is_a', 'reptile')<br>
('python', 'is_a', 'animal')<br>
('python', 'is_a', 'reptile')<br>
('python', 'is_a', 'snake')

All animals:
[('cobra', 'is_a', 'animal'), ('python', 'is_a', 'animal'), ('lizard', 'is_a', 'animal')]

## ▶️ How to Run
Open the file  knowledge_representation.ipynb on Vscode<br>
Run the cells top to bottom<br>
Check if outputs are correct

## ⚠Originality
I came up with new base facts rules and queries to an entirely new situation that deals with animals and reptiles.