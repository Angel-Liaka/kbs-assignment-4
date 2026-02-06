# 📘 Simple Knowledge Representation using facts + rules

## 👤Student Information
Name: Angel Wesonga<br>
Registration Number: 672296<br>
Course: Knowledge Based Sytems

## 🧠Overview
In this project, knowledge is represented using facts in the form of a tuple (subject, relation, object) and rules infer new information from existing facts, such as parent, child, and ancestor relationships.It also involves queries to get both given and inferred facts.The implementation is written in Python and executed in a Jupyter Notebook.

## 🧩Knowledge Representation

**Base Facts:**

"paul" "parent_of" "alex"<br>
"alex" "parent_of" "cole"<br>
"cole" "parent_of" "tara"


**Rules:**

"parent -> child", parent_implies_child<br>
"parent -> ancestor", parent_implies_ancestor<br>
"ancestor transitive", ancestor_transitive


## 🔄 Inference Process
New facts are derived from the existing facts using the defined rules.
These rules are used to get new knowledge, such as child, parent, and ancestor relationships.
The knowledge base is updated with any new facts until there are none left.
Queries can then be run to get both the original and inferred facts from the knowledge base.

## ✅Expected Output
All facts:
('alex', 'ancestor_of', 'cole')<br>
('alex', 'ancestor_of', 'tara')<br>
('alex', 'child_of', 'paul')<br>
('alex', 'parent_of', 'cole')<br>
('cole', 'ancestor_of', 'tara')<br>
('cole', 'child_of', 'alex')<br>
('cole', 'parent_of', 'tara')<br>
('paul', 'ancestor_of', 'alex')<br>
('paul', 'ancestor_of', 'cole')<br>
('paul', 'ancestor_of', 'tara')<br>
('paul', 'parent_of', 'alex')<br>
('tara', 'child_of', 'cole')

Ancestors of tara:
[('cole', 'ancestor_of', 'tara'), ('alex', 'ancestor_of', 'tara'), ('paul', 'ancestor_of', 'tara')]

## ▶️ How to Run
Open the file  knowledge_representation.ipynb on Vscode<br>
Run the cells top to bottom<br>
Check if outputs are correct

## ⚠Originality
I edited the names from the original code to new unique names therefore making the facts different.