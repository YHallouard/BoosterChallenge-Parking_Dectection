Parking Detection
=================
Total @Booster Challenge - Build a neural network that classify satellite pictures.

Pipeline
-----------
#### Global Architecture
I used a RetinaNet build from ResNext101 backbones. For backbones I used 7x7, 14x14 and 28x28 layers.




#### ResStack

ResStack is composed of one "Conv2D + BN + Linear", two stages of "Conv2D + BN + relu + Conv2D + BN + Linear + Shortcut" and then a Maxpooling


Results
-------------
Results on train set :  
![40% center](pictures/resultstrain.png)  

Results on test set :  
![40% center](pictures/resultstest.png)


Finally, I obtained 98% of prediction over 90% of confidence on the test part.


What's Next ?
-----------
- [ ] Early Stoping
- [ ] K-fold validation

## Author

* **HALLOUARD Yann** TOTAL SA
