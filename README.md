This repository contains small examples of my code, walking through parts of the pipeline from digitized text till text mining.
The image processing notebook shows basic tasks, such as image deskewing or binarization, which are often a prerequisity for the OCR. 
Text recognition, evaluation of its quality and post-corrections using hand-crafted rules or a BERT model are shown in the OCR notebook.
The recognized text is subsequently classified, either using linguistic features (such as TF-IDF) or more powerful BERT-based models.
A named entity recognition model is trained and applied on the example of extracting job titles from job advertisements.
The data visualition notebook shows a basic frequencies analysis of the extracted position.
