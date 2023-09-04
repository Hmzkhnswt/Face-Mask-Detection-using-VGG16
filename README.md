# Face Mask Detection using VGG16

This repository contains a Convolutional Neural Network (CNN) model based on the VGG16 architecture for face mask detection. The model is trained to classify whether a person is wearing a mask or not in an image.

![babar azam predicted image](https://github.com/Hmzkhnswt/Face-Mask-Detection-using-VGG16/assets/95092387/33d8f35c-42eb-4a7b-bb95-de9a36f04e00)



## About

In the wake of the COVID-19 pandemic, the use of face masks has become crucial to public health. This project aims to provide a solution for automated face mask detection in images. The VGG16 model, a well-known deep learning architecture, has been fine-tuned and trained on a dataset of masked and unmasked faces.

## Dataset

The dataset used for training and evaluation consists of images of individuals with and without masks. You can find the dataset (https://www.kaggle.com/datasets/sumansid/facemask-dataset) (if you have created your dataset) or mention any other dataset source you used.

## Usage

- Clone this repository:

  ```shell
  git clone https://github.com/your-username/face-mask-detection.git
  ```

- Install the required dependencies:

  ```shell
  pip install -r requirements.txt
  ```

- Run the mask detection script:

  ```shell
  python detect_mask.py --image path/to/your/image.jpg
  ```

  Replace `path/to/your/image.jpg` with the path to the image you want to test.

## Training

If you want to train the model on your own dataset or fine-tune it further, you can follow these steps:

1. Prepare your dataset and organize it into appropriate directories (e.g., `train/` and `test/`).

2. Update the data paths and model configurations in the training script (`train_mask_detector.py`).

4. Once training is complete, you can use the newly trained model for inference.

## Results

You can describe the performance metrics, accuracy, and any other relevant results of your model here.

## Contributing

If you would like to contribute to this project, please open an issue or create a pull request. Contributions are welcome!
