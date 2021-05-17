# QuAX Data
This repository contains the original datasets from the paper "QuAX: Mining the Web for High-utility FAQ"

In this paper, we have proposed three novel datasets.

1. **FAQ Webpage Detection:** "faq_page_detection_standard.csv" is the corresponding file for this module. This comma separated file contains two columns per row. First row is the HTML textual content of a website, second row is the associated class label (FAQ or NOT). 
2. **General Vs. Specific:** "general_specific_standard.tsv" is a tab separated dataset for detecting general or specific questions. There are two rows, first row is the textual content and second row is the associated class label ("general" or "specific").
3. **Self-contained Vs. Incomplete:** "selfcontained_standard.csv" is a comma separated file with two rows for detecting self-contained or incomplete questions. The first row is a question (in textual format) and the second row is the class label ("c" for self-contained, "i" for incomplete)
