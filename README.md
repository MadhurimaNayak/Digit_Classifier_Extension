# Digit Classifier Extension 🔢
## Description
> A fun chrome extension that identifies the digits you draw.🤔

This project integrates the power of chrome extensions and serverless deployment to successfully classify the digits you draw. The ML model 
is run in the browser itself by converting it into ONNX format and loading the same in the extension using ONNX.js. This allows the extension 
to run without internet access while giving it faster inference time.

## Features
> Check out the README.md files inside the folders for additional info!🤓

- _Real time analysis:_ Extension actively modifies the output based on what you draw.
- _Probability display:_ Each number has a dynamic prediction column that shows the probability of the digit drawn being that specific number.
- _Machine Learning Integration:_ Using [ONNX.js](https://microsoft.github.io/onnxjs-demo/#/) and [Pytorch's MNIST model](https://github.com/pytorch/examples/blob/main/mnist/main.py).

## Benefits of running a model in the browser
> A viable method for smaller models!😯

- Faster inference times.
- Easy to host and support (only static files).
- Offline support.
- Enhanced user privacy, as data is kept on the device.

## Visuals

> Demo of the project via images.🖼️

<img width="127" alt="image" src="https://github.com/MadhurimaNayak/Digit_Classifier_Extension/assets/124715194/7d183625-cb7b-46ee-aaaa-d8a0b62521bd">
<img width="128" alt="image" src="https://github.com/MadhurimaNayak/Digit_Classifier_Extension/assets/124715194/29621c9f-7f00-4b0d-910b-1f7dcbae876a">
<img width="128" alt="image" src="https://github.com/MadhurimaNayak/Digit_Classifier_Extension/assets/124715194/2b574a31-8d79-4f71-b277-e9453073cbc1">
<img width="129" alt="image" src="https://github.com/MadhurimaNayak/Digit_Classifier_Extension/assets/124715194/f80526c5-4cf9-464f-a23e-5510d0e85686">
<img width="129" alt="image" src="https://github.com/MadhurimaNayak/Digit_Classifier_Extension/assets/124715194/4909aaed-1a36-4d20-a9d2-4f0bdab639ea">







