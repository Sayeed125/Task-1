student<- read.csv(file.choose())
student
plot(student)

model= lm(student$Scores~student$Hours)
model

abline(model,col='blue')

prediction= 2.484+9.776*9.25
prediction

