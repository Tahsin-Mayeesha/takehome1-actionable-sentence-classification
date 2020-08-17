# huddlehire



# Instructions

The following are the details of the assignment.

**Objective1**: Create a heuristic-based linguistic model for detecting actionable items from emails i.e. a rule-based model to classify sentences to actionable sentences and non-actionable sentences.

This step also needs you to ***download the dataset*** and ***preprocess the emails\*** and break them into ***meaningful sentences\***.

**Objective2**: Once done with Objective1 ping for some pre-tagged action item sentences (One label only). Then train a model to detect whether a given sentence is an actionable item or not. 

***NB: You will be given ONLY the action item sentences, you might need to use your model from objective 1 to get the Non-actionable sentences.***

Actionable item => A sentence which asks someone to do something

example: "Please create an assignment and forward it by EOD"

\-------------------------------------------------------

**About data set:**

The data set contains below 1 CSV file:

1.Enron email dataset

**Download** dataset from the following link.

https://www.kaggle.com/wcukierski/enron-email-dataset

\-------------------------------------------------------

**Instructions:**

Please create a **private** repository in Github and share it with git userid '**[huddlhire](https://github.com/huddlhire)**'. We ABSOLUTELY should be able to see your check-ins/commits from the beginning and NOT just a single commit at the end. Include instructions on how to run the project and set up the requirements. Kindly, ensure that the entire project is repeatable from scratch i.e. from raw data to the final model.

 

Explain the following things in README of Github

  1) Explain your project pipeline.

  2) Explain in detail the process of feature extraction.  

  3) Report recall, precision, and F1 measure

  4) Explain the challenges you've faced while building the model.

# To do 

* [x] Extracting email content
* [ ] Tokenizing emails to list of sentences
* [ ] lemmatizing sentences
* [ ] Making the list of keywords
* [ ] Depending on the keywords making a dataset with labels set
* [ ] Add code for downloading and preprocessing the data
* [ ] Asking for labelled text from company

# Rule Based Model

According to [1](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/ActionableItem_camera-ready-1.pdf) and [2](https://pdfs.semanticscholar.org/beed/b0bac9657fe61dd3910c411aa45b49e57f96.pdf) actionable items in meetings would include discussions on scheduling, emails, action items, and search. keywords used in this paper combined with some brainstormed ones :  

```python
keywords = ["find email","send email","respond","check","plan","create reminder", "find calendar entry","search","add agenda item","create calendar entry","open agenda", 
            "send email","find email","make call","open setting","assign","deliver","suggest","order","request","create assignment","forward","tag","todo","call me","call us","give us a call","email"]
```





# Feature Extraction





# Results



| Model | Precision | Recall | F1   |
| ----- | --------- | ------ | ---- |
|       |           |        |      |



# Challenges

* Raw data had raw email strings only. Content had to be extracted from raw emails. Discarded other metadata because in the tagged dataset only tagged sentences will be given.