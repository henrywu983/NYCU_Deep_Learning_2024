# NYCU_Deep_Learning_2024
## Challenge 2: VGG-16 Pre-trained Weights using the dense layer the professor provided

### Tutorial:

#### Step 1: Install Necessary Libraries
First, ensure your development environment has 'h5py' and 'tensorflow' or 'keras' installed.

```bash
pip install h5py tensorflow
```

#### Step 2: Load the Pre-trained Weights
After setting up your model architecture to match the VGG-16 model, load the pre-trained weights using the following command:

```python
model.load_weights('path_to_your_model_weights.h5')
```