# Exercise Description

## Rock, Paper, Scissors, Lizard, Spock.

In this week's exercise, you will train your model in the browser using your webcam. You will train your model in exactly the same way as in the Rock, Paper, Scissors example but now you will include the Lizard and Spock hand gestures.

Below are a few tips that can help you get started.

1. To prevent overfitting do not add a lot a of dense layers. Using the same layers as in the Rock, Paper, Scissors example should be good enough. 

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/1dfapGRpSYuX2qRkabmLwA_12c3877db335c38eb24f8c40babd3a31_model_week4.png?expiry=1707436800000&hmac=dTHSqinvwkkIzEmRyjGP87acfKfcuZm3LxYt4X87duI)

2. Collecting between 50 to100 images for each hand gesture should be good enough for most models. However, feel free to experiment and try to train your model with less or more images. 

3. **Wait until Training has Finished before you Download the Model**. To make sure training has completed, open the Developer Tools and look at the Console output. When the browser alerts that "Training is Done!" click Ok. After you click Ok, you will see the value of the LOSS being printed in Console. Once the LOSS values stop being printed, you can go ahead and click the "Download Model" button to download the model and its weights.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/RiXsoH5MQTSl7KB-TFE0pA_7e137e7b66f7b8659ef850b9649cb156_Screen-Shot-2019-12-16-at-10.04.03-AM.png?expiry=1707436800000&hmac=fdCYBruo5rTiR2rSy0AoxuS4-Tv_tTdEUZrWcMYoI8E)

4. Your model will be graded based on how it performs on our test set. Below are a couple of images from our testing set:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/8wiC2_OJREyIgtvzifRMXA_deaefff871b3422bafd866831bb5a655_hands.png?expiry=1707436800000&hmac=mD8iX-ZEkVLVnY2Iz3FNXGguMeTQXmJQjGICZkdUskk)

5. To train your model, don't stand too far away from the webcam and it's much better if you do not wear sleeves. Below are some sample training images.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/u_FPo-zORPmxT6PszqT5mg_b4e6ee50b9abb840d35fa755a226e78d_sample_training.png?expiry=1707436800000&hmac=vrJaGblFfT-cG56xJI-uAqpmrZH8kj4zvx6Y9Ck7j7k)

## Possible Issues

Because some of the weights of your model are initialized randomly, your model might get stuck in a local minima during training. When this happens your model may not perform optimally and may cause your submission to fail. If you are confident you did everything  correctly and your submission didn't pass, try re-training the model and re-submitting it. 