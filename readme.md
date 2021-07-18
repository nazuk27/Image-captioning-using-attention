# Image Captioning using Attention Mechanism with BLEU Score evaluation
Implemeted the Encoder-Decoder mechanism of Image Captioning using Attention Mechnism. The model was trained on the [Flickr8k dataset](https://www.kaggle.com/adityajn105/flickr8k).
- The encoder model uses InceptionV3 as base model to extract features from the images.
- The attention part links up the extracted features with the captions of the image.
- Decoder is implemented using GRU.
- Model training checkpoints can be found [here](https://drive.google.com/drive/folders/1UcFkHRi06Qda4IFq9Y8K63zzZwh1FcXd?usp=sharing).

The model obtained an average BLEU score of 0.561036 on the validation data of 7000 captions.

- Developed by [Nazish Khan](https://github.com/nazuk27)
