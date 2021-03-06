# Challenges
ICDSS Advanced Data Science Team Challenges 2017-2018

> Deadline: 31 December 2017

## Datasets

Choose and work on **one** out of the four distinct datasets provided.
You can assume that they are correctly labelled and cleaned.
Detailed descriptions are provided in the `READEME.md` files of each challenge.

1. [Fashion-MNIST](computer-vision)
2. [Ames Housing Prices](real-estate)
3. [Pair Trading](finance)
4. [Volatility Prediction](time-series)

## Assessment

The submissions are assessed for their:

### **Target & Effectiveness**

Briefly summarise the goal of the challenge of your choice and provide an
abstract of your analysis.

Succinctness is always welcome!
If you can show something with 3 lines of math or use well-accepted terminology to
explain something concisely, please do so!
Long texts are, in general, not preferred.

### **Visualization & Statistics**

Descriptions of the datasets are intentionally not provided to enable you to
research for them and gain insight into the raw data.
Any type of meaningful visualization and basic statistical analysis of the data
is highly encouraged. Do not spend too much time on that,
you should be able to get this with just a few lines of code.

### **Assumptions**

Clearly state your assumptions before fitting any model.
This will, hopefully, lead you to better support your model theoretically and
also help us assess your model selection and approach.

For example, in the case of [Volatility Prediction](time-series) challenge,
assumptions on stationarity can lead to significantly different families of models.

### **Model & Model Selection & Validation**

Provide insight into the suggested model to address the problem.
Using `sklearn`'s API `fit`, `predict`, `score` methods is expected but
not the purpose of these challenges. **So just coding a model is not enough**!
We are interested in how you made the decisions for coming up with your model.

As far as model selection and validation go, we do not expect you to perform
grid cross-validation for everything, since this is computationally demanding.
We have relaxed the requirements for the optimality of the final model, as long
as there is a systematic approach.
On the other hand, we do not trust oracles, so if you plan to hardcode model
hyperparameters you had better come up with a good reasoning!

**Note**: Model accuracy is **not** the main objective of these challenges.
State-of-the-art models can be found online,
but if they are not properly presented and reasoned then the solutions will be consider of
inferior quality compared to accurate but well developed and explained solutions.

## Submission

### Format

Compress your solution and send us the `.zip` or `.tar` file via [email](mailto:icdss@imperial.ac.uk).
Format the email subject according to:
```
ADST Challenge: <challenge_name>_<imperial_login>
```
where:
* `<challenge_name>`: is one of `fashion-mnist`, `ames-pricing`, `pair-trading` or `volatility`
* `imperial_login`: your Imperial College username (i.e. `abc12`)

Note that you should be a member of [ICDSS society](https://www.imperialcollegeunion.org/activities/a-to-z/data-science)
in order to accept your submission. The membership is free for Imperial College students!

### Environment

You are allowed to **use any programming language**, as long as you provide us with
an automated way to setup our environment for reproducing your results. You should
expect us to use MacOS 10.13.1 or Ubuntu 16.04.3 LTS for this purpose.
If you have some particular preference between the two please specify it in your
submission. Nonetheless, we encourage you to use [cocalc](https://cocalc.com/),
as we did in the workshops, since it provides a reference environment and zero
setup is required.

### Deriverables

#### Challenge

You can choose to submit:

* a [Jupyter Notebook](http://jupyter.org/), which is supported in [cocalc](https://cocalc.com/) platform.

* a `pdf` report accompanied with documented scripts for reproducing the results. In this case we expect a well method-level documentation convention used so that we can follow the code along the report. There is no preference in the structure of the report, it can also look like a presentation.

**Note**: Quality matters **only**. The challenge can be successfully addressed and
reported with just a handful of jupyter-cells/slides/report-pages.

#### Resumé

Submit also a recent version of your **resumé**, highligting your Data Science experience (projects, courses).

## Logistics

### Issues

We will **not** answer to personal emails, please use [issues](https://github.com/Imperial-College-Data-Science-Society/Challenges/issues)
for asking questions!

### Deadline

Requests for deadline extensions will be ignored.
