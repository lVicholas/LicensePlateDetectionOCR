# LicensePlateDetectionOCR
In this notebook, I fine-tune a model from the TensorFlow Model Garden to detect and bound car license plates. IThen I extract images of the ROI containing the license plates, use a super-resolution GAN to enhance the image of the ROI, and easyocr to read the text on the license plate.

I believe the base version of the generate TFRecord script is from here:
https://github.com/datitran/raccoon_dataset/tree/93938849301895fb73909842ba04af9b602f677a
