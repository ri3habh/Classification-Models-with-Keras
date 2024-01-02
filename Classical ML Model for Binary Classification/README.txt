The original dataset was pre-processed to downscale all images to 64x64 pixels and cropped to the centre of the image. All images are uint8 datatype. A training and test set were selected to balance the labels, and only classes 0 and 1 are used for the binary classification task. There are a total of 8,981 training examples of 1,800 test examples.

There are 2 images classes, which use integer labels of [0, 1]. The meaning of the labels is described below.

label_map = {
    0: "bike",
    1: "cabinet"
}

Data is from the Stanford Online Products Dataset. (https://www.tensorflow.org/datasets/catalog/stanford_online_products)

Best score achieved was 0.898.
