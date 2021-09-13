# Experts perception-based system to detect misinformation in health websites (datasets)

This repository contains data used in the paper Experts perception-based system to detect misinformation in health websites. This paper addresses the emergence of health-related websites that include fraudulent content.

To carry out this problem, medical experts have evaluated several web pages using their knowledge to classify a set of webpages. These evaluations have been compared with the opinions given by non-expert users. Also, how the use of visual design elements affect the evaluation of these experts have been analyzed.

Following is given a short description repository structure:
* extras: this folder contains some extra data used to validate some of the visual design elements, such as physical addresses and logos.
* evaluations: in this folder the evaluations made by the expert and non-expert users can be found. These evaluations take on a numeric value on a scale of 0 (the website is dangerous) to 4(the website is reliable). Two datasets have been created:
  * dataset_1: this dataset is formed by 133 webpages selected by data scientists and medical experts.
  * dataset_2: a set of websites have been modified adding and removing different visual design elements.
