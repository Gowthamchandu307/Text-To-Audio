# Text-To-Audio

## Overview

The "Text-To-Audio" project is designed to convert text into audio using various methods. This includes utilizing external APIs and employing a gender prediction model to enhance the audio output based on the predicted gender of the text's author.

## Files and Directories

### Notebooks
- **Gender prediction model.ipynb**: A Jupyter notebook that uses machine learning techniques to predict the gender of the author from the provided text. This model can be integrated with the text-to-audio conversion to choose appropriate voice parameters.
  
- **Text to audio using external API.ipynb**: This notebook demonstrates how to convert text to audio using an external API. It includes examples and instructions for setting up and using an API service for text-to-speech conversion.
  
- **Text to audio.ipynb**: Converts text to audio without relying on external APIs. This notebook uses local libraries and tools to perform text-to-speech conversion, providing an offline solution.
  
- **voice.ipynb**: An additional notebook related to voice processing. This can include various audio processing techniques and experiments.

### Data and Resources
- **data/**: (Optional) Directory for storing datasets related to the project, such as training data for the gender prediction model.

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed below)
  
## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Text-To-Audio.git
    cd your_project_name
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
## Usage

Start Jupyter Notebook: Run the above jupyter files 




