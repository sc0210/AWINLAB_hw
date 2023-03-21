# Quesstion 1: deep learning

- Classisfication problem
- [Flower datasets](https://www.kaggle.com/alxmamaev/flowers-recognition) (5 classes)

1. Setup model via `KERAS` methods
2. Deep learning model option:  DNN(Deep neural network)  or CNN(convolution neural network)
3. After training, indicate the performance from some metrics and list the comparsion of 10 predicaiton versus groundtruth

----

## MY SOLUTION (last updated: 3/21)

- **prediction result**

![image alt](./output/cnn_pred_result.png)


<!-- ![image alt](./output/cnn_model.png) -->

- **Performance**

||precision|recall|f1-score|support|
|----|----|----|----|----|
|       daisy     |  0.73    |  0.90   |   0.81   |    147|
|   dendelion     |  0.90    |  0.81   |   0.86   |    200|
|        rose     |  0.76    |  0.75   |   0.75   |    151|
|   sunflower     |  0.82    |  0.88   |   0.85   |    140|
|       tulip     |  0.82    |  0.72   |   0.76   |    192|
|    accuracy     |          |         |   0.81   |    830|
|   macro avg     |  0.81    |  0.81   |   0.81   |    830|
|weighted avg     |  0.81    |  0.81   |   0.81   |    830|

- Confusion matrix 
![image alt](./output/result_accuracy_loss.png)

- **Prediction result**
![image alt](./output/confusion_matrix.png)

- **Snapshot of the model**

<img src="./output/cnn_model.png" width="20%" hight="50%">
