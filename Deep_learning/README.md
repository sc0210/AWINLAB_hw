# Question 1: deep learning

## **Description**

- Classification problem
- [Flower datasets](https://www.kaggle.com/alxmamaev/flowers-recognition) (5 classes)

1. Setup model via `KERAS` methods
2. Deep learning model option:  DNN(Deep neural network)  or CNN(convolution neural network)
3. After training, show performance & list the comparsion of 10 prediction versus groundtruth.

----

## **MY SOLUTION**

***(last updated: 3/21)***

- **prediction result**

<img src="./output/cnn_pred_result.png" width="100%">

<!-- ![image alt](./output/cnn_model.png) -->

- **Performance**

|                 |precision |recall   |f1-score  |support|
|      ----       |   ----   |   ----  |   ----   | ----  |
|       daisy     |  0.89    |  0.86   |   0.88   |    147|
|   dendelion     |  0.90    |  0.86   |   0.88   |    200|
|        rose     |  0.77    |  0.75   |   0.76   |    151|
|   sunflower     |  0.75    |  0.92   |   0.84   |    140|
|       tulip     |  0.82    |  0.74   |   0.78   |    192|
|    accuracy     |          |         |   0.83   |    830|
|   macro avg     |  0.83    |  0.83   |   0.83   |    830|
|weighted avg     |  0.83    |  0.83   |   0.83   |    830|

- **Prediction result**

![image alt](./output/result_accuracy_loss.png)

- **Confusion matrix**

![image alt](./output/confusion_matrix.png)

- **Snapshot of the model**

<img src="./output/cnn_model.png" width="200%">
