# Finding the correlation between Posture and Personality trait
## Introduction
Back pains are very common in the working population. It does not have any underlying disease that causes it, which makes it difficult to predict it. It could be caused by working out or lifting too much, prolonged sitting and lying down, sleeping in an uncomfortable position, or wearing a poorly fitting backpack.
There is enough evidence exists contribution of personality and posture to long-term pain management, pointing to a direct contribution of the mind-body axis. In this study we can find the relationships between posture and personality. 

## Dataset
This dataset has been obtained from: https://www.kaggle.com/datasets/dhanasekarjaisankar/correlation-between-posture-personality-trait?resource=download <br>
There are a total of 97 rows and 20 columns in the dataset. <br>
The last row represents the posture of the person which is categorized into 4 types:<br>
A - Ideal posture<br>
B - Kyphosis-Lordosis<br>
C - Flat back<br>
D - Sway-back<br>
The columns “MBTI”, “E”, “I”, “S”, “N”, “T”, “F”, “J”, “P” represent the scores of the participants from the Myers-Briggs personality test. This test aims helps to find the personality of the participant. The below mage gives the meanings of the letters used in the test. 

![image](https://user-images.githubusercontent.com/90857782/216875984-2676d339-dba5-4399-840b-97898a030b3d.png)

I plane to use logistic regression and Random Forest as my first classification models and choose the next model based on the results. I intend to try at least another 2 models depending on the data. 
