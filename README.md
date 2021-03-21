# ArtsyNet: Classifying Art Styles

ArtsyNet is a ResNet34 CNN that classifies a painting's art style into on 25 possible categories with ~67.2% accuracy (on the validation set) on the WikiArt dataset. This project was done as an independent project, to introduce myself to computer vision.

Following [(Lecoutre 2017)](https://hal.archives-ouvertes.fr/hal-02004781/document), the WikiArt dataset was used, and ArtsyNet outperforms the model in that paper by ~6.1%.

Artsynet is coded using fastai v1 (a now depecated language) and PyTorch. The notebook for training ArtsyNet is entitled "ConnoisseurNet" and the trained parameters lie in the file "stage4.pth".
