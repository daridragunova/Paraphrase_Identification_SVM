Machine Learning Midterm Project: Sentence Similarity Detection

This README provides an overview of the project, outlining its objectives, features description, data preprocessing steps, libraries utilized, algorithms tested, and the overall experience gained during the project.

Project Overview

The aim of this project is to develop a model capable of identifying the similarity between two sentences. By analyzing various structural aspects of sentences, such as length, word overlap, n-gram overlaps, capitalized words, and numbers, the goal is to devise an effective algorithm for sentence similarity detection.

Features Description

The following features were considered for the model:

- Word Count Difference: Compares the number of words in each sentence.
- Word Overlap: Calculates the number of common words between sentences.
- Word Union: Counts the unique words in two sentences.
- n-Gram Overlap (2-Gram and 3-Gram): Measures the overlap of n-grams between sentences.
- Numbers Overlap: Counts the occurrence of numbers in a sentence.
- Capitalized Words Overlap: Counts the occurrence of capitalized words in a sentence.
- Cosine Similarity Score: Computes the cosine similarity score for two sentences.

Data Preprocessing

Data preprocessing involved the following steps:

- Identifying bad lines: Handling formatting issues such as extra quotation marks and irregularities in the 'gold_label' column.
- Working with sentences: Standardizing sentences by converting them to lowercase, tokenizing words, removing stopwords, and lemmatizing words.

Libraries Utilized

The project made use of the following Python libraries:

- NLTK: Used for data preprocessing and feature extraction.
- Pandas: Utilized for data manipulation and analysis.
- Sklearn: Employed for implementing and testing various machine learning models.
- Re: Utilized for regular expression operations to extract features such as capitalized words and numbers.
- Math: Used for basic mathematical operations and matrix manipulations.
- Seaborn and Matplotlib: Utilized for data visualization purposes.

Algorithms Tested

Four different models were tested for the task:

- Linear Regression: Initial attempt, yielded low accuracy.
- Decision Tree: Similar to Linear Regression, produced unsatisfactory results.
- Logistic Regression: Showed improvement in accuracy compared to linear models.
- SVM (Support Vector Machine):
	- Linear SVM: Achieved moderate accuracy.
	- RBF SVM: Variability in performance.
	- Kernel SVM: Optimal model, achieved the highest accuracy after fine-tuning parameters.

Experience and Lessons

Key insights and learnings from the project:

- Dealing with large datasets and understanding the significance of data preprocessing.
- Experimentation with various algorithms provided insights into their strengths and limitations.
- Recognition of the importance of non-linear models like Kernel SVM for tasks with non-linearly separable data.
- Appreciation for neural networks and their superior performance in comparison to traditional machine learning models.
- Understanding the significance of feature selection and the impact of different features on model performance.

This README provides a comprehensive overview of the project, detailing its objectives, methodologies, and outcomes. For further details, refer to the project documentation and code implementation.




