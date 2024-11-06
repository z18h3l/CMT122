java c
Module Code CMT122
Academic Year 2024-2025
Module Title Machine Learning for NLP
Assessment Title Coursework 1
Assessment Number 1
Date Set Thursday, October 24th, 12:00pm
Submission Date and Time Friday, November 22nd at 9:00am Return Date TBA
CMT122 Coursework 1 
This assignment is worth 50% of the total marks available for this module. If coursework is submitted late (and where there are no extenuating circumstances):
1.  If the assessment is submitted no later than 24 hours after the deadline, the mark for the assessment will be capped at the minimum pass mark;
2.  If  the  assessment   is  submitted   more  than  24   hours  after  the  deadline,  a mark of 0 will be given for the assessment.
3.  You need to submit a cover sheet (that can be downloaded from LC).
Please note that by submitting your work you declare that you have
●  Read and understood the academic regulations.
●  That  you  are  aware  of  the   consequences  of  applying  for  extenuating circumstances.
●  That you are aware of the consequences of applying for a deferral.
●  That  your  submission  (or  your  contribution  to  it  in  the  case  of  a  group submission) is in accordance with the academic integrity policy which covers a range  of  topics   including  cheating,  collusion,  plagiarism  and  the  use  of generative AI.
You can find the academic regulations here:
● https://www.cardiff.ac.uk/public-information/policies-and-procedures/academic-regulations The  academic  regulations  for  COMSC  (which  notes  which  rules  apply  to  degree programmes in COMSC) can be found under ‘Assessment  Feedback’ in the COMSC- ORG-SCHOOL organisation on Learning Central.
If you wish to apply for extenuating circumstances, please see
● https://intranet.cardiff.ac.uk/students/study/exams-and-assessment/extenuating-circumstances 
● https://intranet.cardiff.ac.uk/students/study/exams-and-assessment/extenuating-circumstances/extenuating-circumstances-policy-for- undergraduate-and-postgraduate-taught-students/new-system-pilot 
If you wish to apply for a deferral, please see
● https://intranet.cardiff.ac.uk/students/study/exams-and-assessment/extenuating-circumstances 
● https://intranet.cardiff.ac.uk/students/living-here/international-students/visas-and-immigration/making-a-change-to-your-studies/deferring-assessments 
You can find the academic integrity policy here
● https://intranet.cardiff.ac.uk/students/study/exams-and-assessment/academic-integrity 
Submission Instructions 
This coursework consists of a portfolio divided into two parts with equal weight:
- Part 1 consists of a selected homework similar to the one handed in throughout the course. The final deliverable consists of a single PDF file, which may include the methodology, snippets of a Python code and solved exercises.
- Part 2 consists of a machine learning project where the students implement a basic machine learning algorithm for solving a given task. The deliverable is a zip file with the code, a readme, and a written summary (up to 1 ,200 words) describing the solutions, design choices and a reflection on the main challenges faced during development. - Any code submitted will be run in Python 3 (Linux) and must be submitted         as         stipulated         in         the         instructions         above. Note that we are using the Harvard referencing style. for citing any related work.You can               refer               to               the               following               guidelines https://xerte.cardiff.ac.uk/play_4191?utm_source=refexamplesutm_medium=ref erral#page1
- Any deviation from the submission instructions above (including the number and types of files submitted) will result in a mark of zero for the assessment or the question part.
-  Staff  reserve  the  right  to  invite  students  to  a  meeting  to  discuss  the  coursework submissions
Assignment 
In this coursework, students demonstrate their familiarity with the topics covered in the module via two separate parts with equal weights (first part: 50%; second part: 50%).
Part 1 (50%) 
In Part 1, students are expected to answer two practical questions.
Practice 
1. Your algorithm gets the following results in a classification experiment. Please compute the precision, recall, F-measure and accuracy *manually* (without the help of your computer/Python, please provide all the steps and formulas). Include all the computation steps included in the process to get to the final result. (20 points) 
ID 
Prediction 
Gold 
1 
positive 
positive 
2 
positive 
negative 
3 
positive 
negative 
4 
negative 
negative 
5 
negative 
neutral 
6 
neutral 
positive 
7 
neutral 
neutral 
8 
neutral 
positive 
9 
positive 
negative 
10 
negative 
negative 
11 
negative 
positive 
12 
positive 
positive 
13 
positive 
positive 
14 
neutral 
positive 
15 
positive 
negative 
16 
negative 
negative 
17 
negative 
positive 
18 
positive 
positive 
19 
positive 
negative 
20 
negative 
negative 
2.  You are given a dataset (named “IMDB reviews” ) with movie reviews and their
associated sentiments (dataset available in Learning Central). Your goal is to train machine learning models in the training set to predict the sentiment of a review in the test set. The problem should be framed as both a regression and a classification problem. The task is therefore to train two machine learning models (a regression and a classification model) and check their performance. 
You can choose the Python SkLearn models to solve this problem.
Write, for each of the models, the main Python instructions to train and predict the labels (one line each, no need to include any data preprocessing instructions in the pdf) and the performance in the test set in terms of Root Mean Squared Error (regression) and accuracy (classification).
While you will need to write the full code to get the results, only these instructions are required in the pdf. (30 points) 
Part 2 (50%) 
In Part 2, you are provided with a text classification dataset (named “bbc_news”). The dataset contains news articles assigned to five categories: tech, business, sport, politics and entertainment. Using this dataset, you need to preprocess the data, select features, train and evaluate a machine learning model of your choice to classify the news ar代 写CMT122 Machine Learning for NLP 2024-2025Python
代做程序编程语言ticles. 
You should include at least three different features to train your model, one of them should be based on some sort of word frequency.
You can decide on the type of frequency (absolute or relative, normalised or not). Text preprocessing is mandatory for the word frequency feature.
The remaining two (or more) features can be chosen freely. Then, you will have to perform. feature selection to reduce the dimensionality of all the features.
Note 
Training, development and test sets are not provided. It is up to you to decide on the evaluation protocol and partitions (e.g., cross-validation or predefining a training, development and test sets). This choice should be explained in the report.
Deliverables 
For this part, the deliverables are a Python code including all the steps and a report of up to 1,200 words.
The Python code should include the Python script. and a small README file with instructions on how to run the code in Linux. Jupyter notebooks with clear execution paths are also accepted.
The code should take the dataset as input and output the results according to the chosen evaluation protocol.20% of the marks are for the code (10 points) and 80% are for the report (40 points). The code should include all the necessary steps described above: to get the full mark for the code, it should work properly and should clearly perform all the required steps. The report should include:
1.  A description of all the steps involved in the process (preprocessing, choice of
features,feature selection, training and testing of the model). This description should be such that one can understand all the steps without looking at the code.
(10 points - The quality of the preprocessing, features and algorithm will not be considered here.) 
2.  A justification of all the steps. Some justifications may be numerical, in that case, a development set can be included to perform. additional experiments.
(10 points - A reasonable justification is enough to get half of the marks here. The usage of the development set is required to get full marks.) 
3. A report on the overall performance (accuracy, macro-averaged precision,   macro-averaged recall and macro-averaged F1) of the trained model on the dataset.
(10 points - Indicating the results, even if very low, is enough to get half of the marks here. A minimum of 65% accuracy is required to get the full mark.) 
4. A critical reflection on how the deliverable could be improved in the future and on the potential biases that the deployed machine learning models may have.
(10 points - The depth and correctness of the insights related to your deliverable will be assessed.) 
The report may include tables and/or figures.
Extra credit (optional) - 10% extra marks in the second part (5 points): For the
second part students can get extra credits by writing an essay on one specific task
related to Part 2 (except for option d, see instructions below). The essay will need to
contain a maximum of 500 words (figures/tables are allowed and encouraged) and will
deal with one of the following four specific topics:
● Error analysis Check the types of errors made by the system submitted for Part
2 and reflect on possible solutions to the observed issues. Conducting a qualitative analysis on specific examples is encouraged.
● Literature review Write an essay about the state of the art of the field (i.e., text classification/categorization). Retrieve relevant articles and digest them, connecting them to your proposed solution to the problem in Part 2.
● Model comparison Propose and evaluate machine learning systems of a
different nature from the ones taught during the course. Write a table with all the results and analyse the strengths and limitations of the proposed approaches.
● Code release Create a GitHub or Bitbucket repository with the data and Python code used for Part 2. Add clear instructions on how to run the code from the terminal and about its different functionalities/parameters. Include all the necessary data, provide full documentation and comment on the code. Students only need to include the link to the repository in the pdf. 
Note The maximum marks for the second part will be 50 in any case.
Criteria for assessment 
Credit will be awarded based on the following criteria.
Part 1 
The main criterion for the assessment is the correctness of the answers, for which an explanation of the methodology is also required. Full marks will be given to answers that include the correct answer and justification or methodology. 
Part 2. This part is divided into Python code (25%) and an essay (75%). The code will be evaluated based on whether it works or not, and whether it minimally contains the necessary steps required for the completion of Part 2. Four items will be evaluated in the essay, whose weights and descriptions are indicated in the assessment instructions.
The main criteria to evaluate these items will be the adequacy of the answer with respect to what was asked, and the justification provided.
Assessment Criteria 
High 
Distinction 80%+ Full understanding of all the concepts, correct answers and methodology, 
well-documented and working code, excellent justification and description of all steps and critical analysis. 
Distinction 70-79% Full understanding of all the concepts, correct answers and methodology, well-documented and working code, accurate justification and description of all steps and critical analysis. 
Merit 
60-69% 
Good understanding of all the concepts, working code, justification and description of steps and analysis. 
Pass 
50-59% 
Few errors in questions and code, methodology with issues and no detailed description of steps and justification or with issues 
Marginal Fail 40-49% 
Code with errors, flawed methodology, incorrect solutions, and no clear description of justification of steps. 
Fail 
0-39% 
Considerable flaws in the methodology and errors in the code, incorrect solutions, and no clear description of justification of steps. 
Feedback and suggestions for future learning 
Feedback on your coursework will address the above criteria. There will be an opportunity for individual feedback during an agreed time.
Feedback for this assignment will be useful for subsequent skill development, such as machine learning in general, data science, natural language processing and deep learning (which will be studied during the second part of the module).

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
