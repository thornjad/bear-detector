# Literally just a simple bear classifier

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thornjad/bear-detector/main?urlpath=%2Fvoila%2Frender%2Fbear_detector.ipynb)

Nothing fancy here, this is a dead-simple bear classifier. Use the notebook to input a photo of a bear, and it will tell you what kind of bear it is. The program is currently able to classify brown, black, grizzly, polar, koala and teddy bears. Improvements may be coming, we'll see.

The model included was transfer-trained from a [ResNet-101 CNN](https://arxiv.org/abs/1512.03385) architecture created with PyTorch. The classifier included here is a simple jumble of ipywidgets which run the model.
