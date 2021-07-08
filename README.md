# data-science-interview-question-bank
This repository contains typical technical questions asked in data science interviews. Most of them are asked in interviews of Iran's big companies, but other famous questions found on the internet are also included.

After you find yourself ready to take an interview, reviewing these questions could be a great help. Since most of these questions are gathered from people's experience, it's recommended to answer them as if they were asked in the interview, e.g., answering with loud sound (not mumbling), giving the best possible answer, etc.

**Note that** most of the answers are given in the interview, so they might not be entirely accurate. You are encouraged to think about the questions and prepare your best possible solution.

## How to contribute?
If you've taken an interview in the past and would like to add any questions here, please append your question to the end of the list using the following format and **beware that** your kind support is enormously appreciated :).

```
#### <How old are you?>
- **Added by**: <John Abbasi> (you could also link you github account)
- **Interviewer Company**: <Tesla>

<Since I was born, the Earth has revoluted 29 times around the Sun.>

[⬆ Back to top](#questions)
```

**Note that** The sections wrapped in `<>` should be changed by the author, and other parts **should remain the same**. **Please** preview your `README.md` file to make sure your question doesn't break the style. Also, the two bullet points are **optional**. Here is what a question and answer would look like:

---
#### How old are you?
- **Added by**: John Abbasi
- **Interviewer Company**: Tesla

Since I was born, the Earth has revoluted 29 times around the Sun.
 
[⬆ Back to top](#questions)

---
Alternatively, you could write your question(s) as issues (without following the format), and I will add them to the list in the above format.

If you have any problems/suggestions regarding the repository or want to add/change a question's answer, you can either submit a new issue about your concern or email me at <mzarei137@gmail.com>.

I would highly appreciate any other form of contribution.

## Questions
#### Imagine we have gathered the height of all the people in Tehran, how does the distribution look like?

Since every natural event roughly follows the normal distribution, we expect the distribution to have precisely one peak value, no/low skewness, and roughly symmetric. The more the population, the closer it will look like the normal distribution.

[⬆ Back to top](#questions)

#### How about the people whose age is between 20 and 30 years old?

It would still follow the normal distribution but with a lower variance (since the data is more similar) and probably a higher mean (since we remove a big chunk of data with low heights).

[⬆ Back to top](#questions)

#### What if we separate the heights by gender? How does the distribution of height of all the men in Tehran look like?

It still follows the normal distribution but with a different mean and variance.

[⬆ Back to top](#questions)

#### How does the people's income or salary look like?

Still normal but with a skewness (heavy tail) on the right side.

[⬆ Back to top](#questions)

#### How can we measure the similarity between two distributions?

1. [KL divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence)
2. [Q-Q plot](https://en.wikipedia.org/wiki/Q%E2%80%93Q_plot)

[⬆ Back to top](#questions)

#### Explain the following concepts: Matrix rank, invertible matrix, matrix determinant.

Basic linear algebra questions. I recommend watching [Gilbert Strang's 2005 linear algebra course (MIT)](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D).

[⬆ Back to top](#questions)

#### What are covariance and correlation? What is the difference between those two?

[Covariance and correlation](https://en.wikipedia.org/wiki/Covariance_and_correlation)

[⬆ Back to top](#questions)

#### What does each value in the covariance matrix represent?

Each value in the covariance matrix represents the covariance of two random variables (like features in a dataset) or two elements of a random vector. Its main diagonal values are variances of those random variables or random elements.

[⬆ Back to top](#questions)

#### We have trained two different binary classification models on a dataset; The first one has 70% accuracy, and the other has 90%. Can we say for sure that the second one is better? Why not? Which metric is better to use here?

Accuracy metric performs poorly on an imbalanced dataset, and since we don't know anything about the class distribution, we cannot say which one is the best. Other valuable metrics often used alongside accuracy are recall, precision, and F1-score. Note that with highly imbalanced datasets, ROC AUC **can be misleading**.

[⬆ Back to top](#questions)


## Future Improvements

- Improving the style.
- Adding individual answers to a question.
