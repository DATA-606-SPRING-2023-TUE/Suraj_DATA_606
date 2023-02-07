# Predicting posture of a person based on their personality
## Introduction
Back pains are very common in the working population. It does not have any underlying disease that causes it, which makes it difficult to predict it. It could be caused by working out or lifting too much, prolonged sitting and lying down, sleeping in an uncomfortable position, or wearing a poorly fitting backpack. <br>
There is enough evidence exists contribution of personality and posture to long-term pain management, pointing to a direct contribution of the mind-body axis. In this study we can find the relationships between posture and personality and hopefully find a model to predict the posture of a person based on their personality type obtained from the Myers-Briggs personality test. <br>


## Dataset
This dataset has been obtained from: https://www.kaggle.com/datasets/dhanasekarjaisankar/correlation-between-posture-personality-trait?resource=download <br>
There are a total of 97 rows and 20 columns in the dataset. <br>
### Columns:<br>
S No – Serial number of the rows<br>
AGE – Age of the participants<br>
HEIGHT – Height of the participants<br>
WEIGHT – Weight of the participants <br>
SEX – Gender of the participants <br>
ACTIVITY LEVEL – Relative level of activity of the participants<br>
Pain columns - The pain scale data consisted of a number between 0(low) to 10 (high)<br>
PAIN 1 – Pain in the neck<br>
PAIN 2 - Pain in the thoracic <br>
PAIN 3 - Pain in the lumbar<br>
PAIN 4 - Pain in the sacral  <br>
MBTI - personality inventory / Myers-Briggs personality test and their respective scores in the next columns<br>
E – Participant prefers Extraversion<br>
I - Participant prefers introversion<br>
S - Participant prefers Sensing while taking information<br>
N - Participant prefers Intuition while taking information<br>
T – Participant prefers Thinking while making decisions<br>
F – Participant prefers Feeling while making decisions<br>
J - Participant prefers Judging<br>
P - Participant prefers Perceiving<br>
POSTURE – Posture of the participant <br>

The posture of the person is categorized into 4 types:<br>
A - Ideal posture<br>
B - Kyphosis-Lordosis<br>
C - Flat back<br>
D - Sway-back<br>
The columns “MBTI”, “E”, “I”, “S”, “N”, “T”, “F”, “J”, “P” represent the scores of the participants from the Myers-Briggs personality test. This test aims helps to find the personality of the participant. The below mage gives the meanings of the letters used in the test. <br>

## Developing the model
I plan to use logistic regression and Random Forest as my first classification models and choose the next model based on the results. I intend to try at least another 2 models depending on the data.<br> 
I will be using combination of Age, height, weight, Gender, activity level and results from the personality test as the parameters for the model to hopefully get a desired result. The pain columns would not be used, as the main objective of the project is to predict the posture of the participant just based on their personality. 

