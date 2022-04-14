# Feed Forward Neural Network for Breast Cancer Wisconsin (Diagnostic)
_Using a Feed Forward Neural Network (Deep Learning) model to predict whether the cancer is benign or malignant_

## Description

- The model utilises the [Breast Cancer Wisconsin (Diagnostic) Data Set from UCI Machine Learning Repository][df1] to predict whether the cancer is benign or malignant
- In a summary, the data set are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
- A Feed Forward Neural Network is used for the project because of the relatively high number of the features, 30 (before the Data Preprocessing)

## Methodology
#### The project can be divided into several sections:
- Data Acquisition
- Data Preprocessing
- Data Features & Label Definition
- Data Scaling
- Model Creation
- Model Training
- Model Prediction

## Results
- The training was set to run for 50 epochs. However, Early Stopping has occured the 17th epoch.
- Model evaluation was done after model training and the results are:
    -  Test loss = 0.17
    - Test accuracy = 0.96

## License
Copyright (c) [2022] [Fatimah Zahrah binti Mohd Badry]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
MIT

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [df1]: <https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29>