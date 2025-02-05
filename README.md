# Neural Style Transfer Web App

This project is a neural style transfer web application built using Flask and TensorFlow. It allows users to upload a content image and a style image (or specify a style image URL) and then generates a stylized image by blending the content of one image with the artistic style of another. The pre-trained model is loaded dynamically from TensorFlow Hub.

## Features

- **Image Upload:** Users can upload a content image and a style image.
- **Style Transfer:** Uses a pre-trained TensorFlow Hub model for arbitrary style transfer.
- **Result Display:** The application displays the content image, style image, and the generated (stylized) image on a results page.
- **Download Option:** Users can download the generated image.
- **Professional UI:** Styled HTML pages for a clean and professional user experience.

## Project Structure


## Requirements

- Python 3.8 or higher
- TensorFlow 2.x
- TensorFlow Hub
- Flask
- Pillow
- NumPy

The complete list of dependencies is provided in the `requirements.txt` file.

## Installation

1. **Clone the repository:**

   ```bash
   git clone <your-repo-url>
   cd style_transfer_app
