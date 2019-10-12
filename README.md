# Session-10

### In this assigment,we are applying cutout and  using LR Finder to find the best starting learning rate. Then we are using SGD with momentum to train the model till 100 epoch. 
### Finally we pick the best performing model (epoch). Then we calculate top 3 & 5 accuracy and finally perform gradcam on misclassified images.

<b> 1. Using LR finder, we get a learning of 0.1. <b>
  
  ![alt text](https://github.com/rp8081/Session-11/blob/master/LR.PNG)

<b> 2. Then we train our model with following functionality :-   <b>
<b>            learning rate of 0.1 + cutout + SGD with momentum  <b>
  
<b> 3. The best accuracy of 86.12% is acheived at 96th epoch . Also top 3 accuarcy is 97.52% and top 5 accuracy is 99.37%. <b>
  
<b> 4. Accuarcy Curves <b>
  
  ![alt text](https://github.com/rp8081/Session-11/blob/master/Accuracy%20Curves.PNG)
  
<b> 5. GradCAM on 25 Misclassified images <b>
![alt text](https://github.com/rp8081/Session-11/blob/master/GradCAM.PNG)

