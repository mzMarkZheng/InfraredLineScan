# InfraredLineScan
This project utilises a pre-trained segmentation model to identify the edges of a fire in infrared line scan images. As there were a limited amount of training data, we utilised albgumentation to create more data to train our model on. 

The model will take in an infrared image such as:
![WALHALLA_353_P1_201902031625_MGA94_55](https://user-images.githubusercontent.com/78593106/159660377-9b45013c-d805-42c2-80b8-a2c53ede7d19.png)

and produce a grayscale image such as this:

![WALHALLA_353_P1_201902031625_MGA94_55](https://user-images.githubusercontent.com/78593106/159660178-d96571fd-0424-4760-9b35-d412f1f1d804.png)
