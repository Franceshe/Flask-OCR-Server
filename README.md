# Flask-OCR-Server

## Motivation
Save time for the following task:
* 1. Image recognition and text saving
* 2. Handwriting text transform to digital text
* 3. Handwritten Math equation to latex form

## Solution:
* For structured digital image input, using tesserac + opencv + pytorch.

* For unstructured image input, using neural network approach:
Possible candidate include:
[SimpleHTR-Handwritten Text Recognition (HTR) system implemented with TensorFlow
Using RNN](https://github.com/githubharald/SimpleHTR).
and [Off-Line Math Formula Recognition Using Deep Neural Networks]
(https://github.com/jungomi/math-formula-recognition) Based on [Multi-Scale Attention with Dense Encoder for Handwritten Mathematical Expression Recognition](https://arxiv.org/pdf/1801.03530.pdf)


## Further development after the web app
* So many people charge money for OCR app in ios store. Why not make it free?
* IOS port the traning model to COREML, following guide:[Intro to machine learning on iOS: Using Core ML to recognize handwritten digits](https://heartbeat.fritz.ai/intro-to-machine-learning-on-ios-building-app-recognize-handwritten-digits-coreml-6c2cdd04b00b)


## Reference
* [A comprehensive guide to OCR with Tesseract, OpenCV and Python](https://nanonets.com/blog/ocr-with-tesseract/#installingtesseract)