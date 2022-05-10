ResNet50_Classification project configured for fruits and vegetables image classification.

Original dataset: https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition?resource=download

Project developed in google colab.

Using of ResNet50_Classification project:

- Image class predicton:

Open Flask_Api.ipynb notebook in google colab, put your ngrok token and run all cells. Use webpage for uploading image with fruit or vegetable. Click on "predict class" button, after that API must return input image with predicted class name.

![alt text](https://github.com/Strider0531/ResNet50_Classification_Colab/blob/master/example/api_example.jpg?raw=true)

- 2-d image visualization:

Open fruit&vegetables_classification.ipynb in colab. Set path to model and filepaths to set of images. Run all cells. 
Fruit and vegetables 2-d vizualization example:

![alt text](https://github.com/Strider0531/ResNet50_Classification_Colab/blob/master/example/example-tSNE.png?raw=true) 

- Training of custom ResNet50 classification model in Colab:

Open fruit&vegetables_classification.ipynb in colab. Set needed paths to subsets in train_dir, test_dir and validation_dir. Run all cells.
Also you can change configurations for image_generator and for the last layers of model.


