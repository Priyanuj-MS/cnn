# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info] Supervised ML leveraging Deep Learning to detect Melanoma from images using CNN
* [Technologies Used] Python, Tensorflow, Keras
* [Conclusions] In the first run, the code got better with adding dropouts, augmentation and normalization layers. Prior to that it showed instance of overfitting drastically.
However, due to connectivity lost, after re run, it showed better generalization from the first step itself of model.fit. 
Technically, the output should have followed the first order, however due to timelines and code run time consideration, submitting the final file (2nd version itself)
* [Acknowledgements]

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The project problem statement is to detect melanoma from images
- Leveraged CNN Deep Learning methodology to go ahead with the process of classification
- To identify if a person has Melanoma or not
- Data set used is International Skin Imaging Collaboration (ISIC)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initially the model definitely overfits (based on first iteration)
- Batch Normalization underfits the model as can be seen by the accuracy and loss over epochs graph as it is very zig zag
- Other techniques needs to be applied on top of this, maybe more drop outs to get better results

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python                       -     3.11.11
- tensorflow                   -     2.18.0
- tensorflow-datasets          -     4.9.8
- tensorflow-hub               -     0.16.1
- tensorflow-io-gcs-filesystem -     0.37.1
- tensorflow-metadata          -     1.16.1
- tensorflow-probability       -     0.25.0
- tensorflow-text              -     2.18.1
- keras                        -     3.8.0
- keras-hub                    -     0.18.1
- keras-nlp                    -     0.18.1
- tf_keras                     -     2.18.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by Priyanuj Misra - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
