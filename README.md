# Encryptix
Encryptix is an image captioning AI that combines computer vision and natural language processing to generate captions for images. It uses a pre-trained ResNet model for feature extraction and an LSTM for generating captions.
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/uwadukunze/Encryptix.git
   cd Encryptix
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
## Usage

1. Place your images in the `data/` directory.
2. Run the `src/image_captioning.py` script to extract features and generate captions.
## Training

To train the model, follow these steps:
1. Load and preprocess your dataset.
2. Extract features from the images using the pre-trained ResNet model.
3. Train the captioning model using the preprocessed data.
