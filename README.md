# Lyrics Generator using GPT-2 in HuggingFace

## Description
This project is a Lyrics Generator that utilizes the GPT-2 model from HuggingFace. It demonstrates how to fine-tune the GPT-2 model on a lyrics dataset to generate new lyrics. This project is implemented in a Jupyter Notebook, leveraging the capabilities of HuggingFace's `transformers` library and Google's Colab for GPU acceleration.

## Features
- Fine-tune GPT-2 on a custom lyrics dataset.
- Generate new lyrics based on the trained model.
- Utilize HuggingFace's `transformers` library for model training and generation.
- GPU acceleration using Google Colab.

## Technical Details
### Model Training
The GPT-2 model is fine-tuned using a lyrics dataset. The training process involves the following steps:
1. **Data Preprocessing**: The dataset is preprocessed to tokenize the lyrics using HuggingFace's tokenizer.
2. **Model Configuration**: The GPT-2 model is configured with specific hyperparameters such as learning rate, batch size, and number of epochs.
3. **Training Loop**: The model is trained using a training loop that iterates over the dataset, updating the model weights to minimize the loss function.

### Advanced Techniques
- **Transfer Learning**: Leveraging the pre-trained GPT-2 model and fine-tuning it on the lyrics dataset.
- **Data Augmentation**: Techniques such as data shuffling and splitting are used to enhance the dataset.
- **Early Stopping**: Implementing early stopping to prevent overfitting by monitoring the validation loss.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Uzumaki-na/Lyrics-generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Lyrics-generator
   ```

## Usage
1. Open the Jupyter Notebook `Lyrics_Generator_using_GPT2_in_HuggingFace.ipynb`.
2. Follow the instructions in the notebook to fine-tune the GPT-2 model on your dataset.
3. Generate new lyrics using the trained model.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

