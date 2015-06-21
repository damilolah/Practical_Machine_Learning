# Practical_Machine_Learning
Course Assignment


Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of 
data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – 
a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their
behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity 
they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on 
the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 
5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har
(see the section on the Weight Lifting Exercise Dataset). 

The data processing and prediction algorithm can be found in the R Markdown named:  CourseAssignment.

The HTML Version of the analysis is named CourseAssignment.html


A prediction model using the rpart function was created but found to have low accuracy after Cross validation. 
Our final model was gotten using the randomForest algorithm and rf method in caret.

