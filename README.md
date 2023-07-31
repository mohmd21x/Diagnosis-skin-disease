# Diagnosis-skin-disease
in this project we try to classify two skin diseases(Eczema, Psoriasis) using transformers like VGG16, InceptionV3 and EfficientNet.
## VGG16
in this section we imported vgg16 model from keras and add some preprocessing layers like RandomZoom and RandomRotation for train model more efficient.
after that we test model on test data for evaluating:
![vgg16-skin](https://github.com/mohmd21x/Diagnosis-skin-disease/assets/81675003/deab83d2-eac2-485e-92d9-cd9ef69b7a4e)
and finaly for best training epoch accuracy of test data was about 78%
## InceptionV3
as same as VGG16 we imported InceptionV3 model from keras and some preprocessing layer was added to model.
![Inceotion-acc-skin](https://github.com/mohmd21x/Diagnosis-skin-disease/assets/81675003/11f3d83f-3f6a-4121-8621-1945a782c11e)
accuracy on test data for best epoch was about 82%

## EfficientNet
same as previous models we imported model from keras API and some preprocessing layer was added to model.
and the end of training we plot accuracy of model on both train and test data's:
![eff-acc-skin](https://github.com/mohmd21x/Diagnosis-skin-disease/assets/81675003/9d12d331-ba97-4a5d-a219-d45dc3e52c02)
best accuarcy on test data was about 87% that was the best accuracy in all of models.
