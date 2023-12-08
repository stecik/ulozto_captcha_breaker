# Ulozto CAPTCHA breaker
## Because of the current changes (1.12.2023) this repository won't be updated anymore unless the situation changes.
Neural network trained to recognize CAPTCHA used by server uloz.to (WORK IN PROGRESS)<br />
This project is inspired by https://github.com/JanPalasek/ulozto-captcha-breaker and https://keras.io/examples/vision/captcha_ocr/
## Dependencies
If you want to install Tensorflow on GPU first follow the guide and than install other requirements<br/>
GPU Tensorflow installation guide: https://www.tensorflow.org/install/pip#windows-native<br/>
To install requirements run this command:
```
pip install -r requirements.txt
```
## Model
1) You can choose from several trained models in directory models (the higher the success the better). Specify selected model in cell __load model__
2) You can train your own
## Training a model
Dataset requirements:
- Images 175x70
- Black and white images (pixels have only 2 values: 0 for black, 255 for white). There is a function in functions.ypynb which converts rgb images into black and white.
- Images in PNG format
- Put your dataset into dataset directory

## Last Model
![image](https://github.com/stecik/ulozto_captcha_breaker/assets/74813606/a131b800-83e8-4167-b00e-9609e288c25d)
