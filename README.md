# automl-tensorflowjs

I trained a custom object detection model using Google Cloud AutoML and exported the model as a TensorflowJS package.
However, when I try running the model using the HTML deployment example they have here https://cloud.google.com/vision/automl/object-detection/docs/tensorflow-js-tutorial?hl=en_US, it does not seem to work.

My tensorflowjs package from the export (model.json, dict.txt, group1-shard1of3,group1-shard2of3, group1-shard3of3)
are in the same directory as the index.html. I also have an index2.html. In index.html I use the same
imports for tfjs and tfjs-automl as the example here. In the index2.html I use CDN sources for tfjs and tfjs-automl.

The create web app example is here: https://github.com/tensorflow/tfjs/blob/master/tfjs-automl/code_snippets/object_detection.html

My repo that follows that example using my custom object detection model is: https://github.com/mmmwembe/automl-tensorflowjs.git including the tensorflowjs model and the test-images.


What am I missing here?...I've run this with Chrome browser using Live Server in vscode editor as well as with nodejs using http-server -p 8000






