# Practicle Machine Learning- Course Project

Human Activity Recognition - HAR - has emerged as a key research area in the last years and is gaining increasing attention by the pervasive computing research community, especially for the development of context-aware systems.

This human activity recognition research has traditionally focused on discriminating between different activities, i.e. to predict "which" activity was performed at a specific point in time. The approach we propose for the Weight Lifting Exercises dataset is to investigate "how (well)" an activity was performed by the wearer. The "how (well)" investigation has only received little attention so far, even though it potentially provides useful information for a large variety of applications,such as sports training.

In this study, six young health participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: 

1. Exactly according to the specification (Class A)
2. Throwing the elbows to the front (Class B)
3. Lifting the dumbbell only halfway (Class C)
4. Lowering the dumbbell only halfway (Class D) 
5. Throwing the hips to the front (Class E)  

Participants were supervised by an experienced weight lifter to make sure the execution complied to the manner they were supposed to simulate.


#Original study
http://groupware.les.inf.puc-rio.br/har  

The training data for this project are available here: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


#Model choosing.

split data to 75%training, 25%testing.
train 3 multi-class models, rpart, random forest, logit boost. choose the one with best accuracy(smallest test error)

The model can distinguish proper and inproper performance of barbell exercise.

