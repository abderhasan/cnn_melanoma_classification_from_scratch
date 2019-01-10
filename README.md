# Training a CNN From Scratch for Melanoma Detection Using Keras

Before running the code, make sure that you structure the data as follows (the numbers represent the number of images in each file):

![alt text](https://github.com/abderhasan/cnn_melanoma_classification_from_scratch_keras/blob/master/directory-structure.png)

You can download the data from, <a href="https://drive.google.com/drive/folders/126UgFt_xqnHpeV1Pr_qLDQLwzBbi4rrY?usp=sharing">here</a>.

To run the code:

`$ python cnn_from_scratch.py`

The results will not be optimal, as the purpose is to show how one can train a CNN from scratch.

<strong>What variables to edit in the code?</strong>

You need to edit the following variables to point to your data:

<em>train_directory</em> (path to your training directory)

<em>validation_directory</em> (path to your training directory)

<em>test_directory</em> (path to your testing directory)

<strong>What should you expect (outputs)?</strong>

<em>Training and validation accuracy</em>

<img class="aligncenter size-full wp-image-845" src="https://abder.io/wp-content/uploads/2019/01/accuracy.png" alt="" width="640" height="480" />

<em>Training and validation loss</em>

<img class="aligncenter size-full wp-image-846" src="https://abder.io/wp-content/uploads/2019/01/loss.png" alt="" width="640" height="480" />

<em>Test accuracy</em>

This will be a value. In my case, the test accuracy was around 77.1%.

<em>ROC curve</em>

<img class="aligncenter size-full wp-image-848" src="https://abder.io/wp-content/uploads/2019/01/ROC.png" alt="" width="640" height="480" />

In addition to some other values (i.e. confusion matrix) that will be displayed on the console.
