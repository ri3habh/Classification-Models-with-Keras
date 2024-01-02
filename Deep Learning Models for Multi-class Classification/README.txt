The original dataset was pre-processed to downscale all images to 64x64 pixels and cropped to the centre of the image. All images are uint8 datatype. A training and test set were selected to balance the labels. A training and test set were selected to balance the labels. There are a total of 56,259 training examples of 10,800 test examples.

There are 12 images classes, which use integer labels of [0, 1, 2, …, 10, 11]. The meaning of the labels is described below.

label_map = {
    0: "bike",
    1: "cabinet",
    2: "chair",
    3: "coffee maker",
    4: "fan",
    5: "kettle",
    6: "lamp",
    7: "mug",
    8: "sofa",
    9: "stapler",
    10: "table",
    11: "toaster"
}

Data taken from Stanford Online Products Database (https://www.tensorflow.org/datasets/catalog/stanford_online_products). 

Best score achieved was 0.53734
