# Compiler design and its application is software engineering
By: **Dr. Saeed Parsa**

## Preface

Our laboraotry research interests lie in the areas of software engineering and compilers. I relate these two subjects through reverse engineering techniques. For the time being the main focus of my research is in software testing and reverse engineering. I use a mixture of compilers and statistical techniques and highly practical software engineering methods. I am interested in automated test data generation and fault localization. I have developed new methods and algorithms for detecting the domain of a program inputs rather than the inputs data, themselves. 

I believe that statistical approaches to fault localization are biased by the test sets and the bias could be avoided by applying the domain coverage criterion as a basis for evaluating the data sets. We have designed and developed some components to facilitate test data generation and automated fault localization. My main research areas are as following.

* Software Engineering: Including software methodologies, software refactoring,  dashboard system design, key performance indicators, and graph analysis.
* Software Testing: Including test data generation, domain testing, fuzz testing, and performance testing.
* Software Debugging: Including automatic fault localization, defect prediction, and automatic software repair.

## Software refactoring

Refactoring is a maintenance activity intended to restructure code to improve different quality attributes such as readability and usability. Refactoring appeared first in Opdyke’s Ph.D. thesis to address restructuring at the code level. Refactoring is defined as “A change made to the internal structure of software to make it easier to understand and cheaper to modify without changing its observable behavior”. Refactoring is an important activity in test-driven development (TDD) and Agile software development.

Kent Beck coined the term “code smell” in the context of identifying quality issues in code that can be refactored to improve the maintainability of a software. He emphasized that the presence of excessive number of smells in a software system makes the software hard to maintain and evolve. However, code smells are technically not erroneous but their presence point towards flimsiness in design, which could initiate the malfunction of system and risk of bugs in the near future.

Recently we encountered some projects in software testing and quality assurance that contains messy codes, design, architecture, and documents. We had problems to apply automatic software testing tools on these repositories, therefore we decided to provide some tools to detect smells in software and performed automatic refactoring. Our aim is to improve the testability of the software by applying these tools before testing. For the time being, we have focused on automatic software refactoring techniques for C++ applications.



