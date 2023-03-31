# ViT-implementation-for-the-fMRI-project

VIT is implemented using Huggingface and sample images to perform inference. 
In this issue:

We'll create a notebook which uses HF transformers, and use sample image to perform inference.

   - Do this for 2 images, making sure to study the length of the inputs, requirements for input to the model, and outputs. (You'll need to find some example images)

Then, repeat this implementation using the ViT Classes directly. This means you'll need to specifically use the feature extractor and the VitForImageClassification (or whatever the correct class name is) to implement the above, but using the specific classes. For this one, make sure to note the key names (as in the keys of a dictionary) of the outputs of the feature extractors, as these are the important inputs to the model.

Make sure to comment about the components of the model, namely:

- feature extractor and how it prepares the inputs requirements for feature inputs 
- Required inputs to the actual transformer model.

Anything else you find to be important in the context of us using this for fMRI or EEG signals.
