# Neural Style Transfer

## Overview
This project implements neural style transfer in Python, applying the artistic style of one image to the content of another using deep convolutional neural networks. It demonstrates the power of deep learning for creative applications, image manipulation, and feature extraction.

## Key Features
- Transfers artistic style from one image to another using pretrained CNNs
- Allows users to choose any pair of content and style images
- Outputs high-resolution, visually compelling stylized images
- Easily extendable for batch processing and different image types

## Technologies Used
- Python
- TensorFlow or PyTorch (specify which used in your code)
- NumPy
- Matplotlib / PIL for image handling

## How to Run
1. Clone the repository: `git clone https://github.com/venkatbhaskar4u/Neural-Style-Transfer.git`
2. Install dependencies (`pip install -r requirements.txt` or include setup instructions)
3. Place your content and style images in the `/images/` directory.
4. Run `Nst.py`: `python Nst.py --content images/content.jpg --style images/style.jpg`
5. Output stylized images will be saved in `/output/`.

## Results & Example Outputs
- Example:  
![Stylized Output](output/sample_result.png)  
*Figure: Example stylized image produced by neural style transfer.*

## Author
Venkat Bhaskar Reddem

