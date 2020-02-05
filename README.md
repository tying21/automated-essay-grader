# automated-essay-grader

This repo contains the codes and data files for NLP project, as well as the presentation slides and the project report.

# Abstract
Essays have been considered an effective medium for measuring academic metrics compared to generalized multiple-choice tests. However, the cost and effort associated with scoring the essays have made instructors prefer the multiple-choice path. Automating the essay grading process would not only help overcome these obstacles but would also aid with removing subjectivity and biases that might sometimes occur with human graders. In our project, we aim to utilize NLP techniques and develop a model that would effectively predict the score of a given essay. We also hope to explore the possibilities of treating the scoring as both regression and classification tasks.
 
# Dataset Description
We’ll be using the Automated Essay Scoring dataset (https://www.kaggle.com/c/asap-aes/data) developed by the Hewlett Foundation for a Kaggle competition. The dataset contains 8 different essay sets, with each set containing essays written by students belonging to Grade 7 through Grade 10. Each of these sets also has a unique domain/topic and utilizes different scoring systems, which would help improve the quality of the training process. The dataset provides its own training (~13K essays) and validation (~4K essays) splits. The main feature set consists of the essay corpus and their corresponding scores [0, 12] provided by a number of human graders.
