# Furry Image Model
Hey there! This is my project on labeling furry artwork!

## How To Use

1. Create a python enviornment using your favorite flavor of enviornment creation (venv, conda, etc).
2. Use `pip install -r requirements.txt` in the root directory of this project to install all dependencies required for this project.
3. Follow [the appropriate steps](https://www.tensorflow.org/install/pip) for installing GPU accelerated TensorFlow (if necessary).
4. Download a model from the Model List (below).
5. Try out the [Jupyter Notebook](./example_usage.ipynb) to see how to use this project!

## Model List

Since models are very large, you need to download them separately. Here are some links for you to do this:

| Model Name       | Link                                                                                     |
|------------------|------------------------------------------------------------------------------------------|
| effnet_b3_300_2c | [link](https://drive.google.com/uc?export=download&id=1n-qEMXU86G8A_UEpZ9_CmAPWdBkMO_zY) |

## Model Architecture

This model uses multiple prediction heads in order to predict for the 6 different categories. These categories are `action`, `body`, `clothing` `identity`, `rating`, and `species`. In the `./categories/` folder, you can see a detailed description of all the tags for each category.

Here is an image showcasing the model `effnet_b3_300_2c`:

![Image of model's architecture. Starts with an Input layer](images/readme/model_architecture.png)

(write more here)

## Datasets

## Performance

### Loss

### Accuracy

First, we're going to look at overall accuracy:

Now, here's per-tag accuracy:

## Other

### Todo

- Finish README
- Add more usable models
- Develop a testing procedure to evaluate how a model performs on furry artwork.
