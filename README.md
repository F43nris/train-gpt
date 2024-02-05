# Training GPT on Wine Reviews

This project demonstrates how to train a GPT model using TensorFlow and Keras on a dataset of wine reviews. It's adapted from Apoorv Nandan's GPT tutorial on the Keras website, tailored to work with wine review data to generate wine descriptions.

## Getting Started

### Prerequisites

- Python 3.6+
- TensorFlow 2.x
- NumPy
- IPython

### Installation

Clone this repository and install the required packages using pip:

git clone train-gpt
cd train-gpt
pip install -r requirements.txt


### Dataset

The dataset used is the `winemag-data-130k-v2.json` file, which contains 130k wine reviews. Ensure the dataset is located at `/app/data/wine-reviews/` before running the notebook.

## Usage

To start training the GPT model on the wine reviews dataset, open the provided Jupyter notebook:

jupyter notebook gpt_wine_reviews.ipynb


Follow the steps in the notebook, which cover:

1. Loading and preprocessing the wine review dataset.
2. Tokenizing the text data.
3. Creating the training set.
4. Defining the model architecture, including transformer blocks and embedding layers.
5. Training the GPT model.
6. Generating wine reviews with the trained model.

### Training the Model

Run all cells in the notebook to train the model. The training process includes checkpoints and tensorboard callbacks for monitoring the training progress.

### Generating Wine Reviews

After training, use the trained model to generate wine reviews by providing a start prompt to the `generate` function of the `TextGenerator` callback class.

## Contributing

Feel free to fork this project and submit pull requests with enhancements or fixes.

## Acknowledgments

- Apoorv Nandan for the original GPT tutorial on the Keras website.
- The Keras and TensorFlow teams for providing the tools to build this project.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
