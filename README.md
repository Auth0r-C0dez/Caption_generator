# Caption Generator

This project is registered as a open source project in the Android Club Winter of Code (AcWoc) 24' event conducted by the Android Club of VIT Bhopal University.

## Overview
The **Caption Generator** project is an open-source tool that uses image recognition and caption generation to provide meaningful descriptions for images. It features a user-friendly interface built with Gradio, allowing users to upload an image and receive an auto-generated caption.

This project is written in Python and is open for contributions.

## Features
- **Image Content Recognition**: Detects objects and content within an image.
- **Caption Generation**: Provides descriptive captions for uploaded images.
- **Gradio Interface**: An intuitive web-based UI for easy interaction.
- **Customizable**: Modular architecture to extend and adapt functionality.

## Technical Details

### Technologies Used
- **Python**
- **Gradio** for the user interface
- **TensorFlow**/**PyTorch** for the backend models
- **OpenCV** for image processing (if applicable)

### System Architecture
- The image is uploaded via the Gradio interface.
- The backend processes the image and generates a caption using a pretrained model.
- The caption is displayed in the Gradio interface.

### Model Details
- Uses pretrained models for image captioning (e.g., ResNet + Transformer architecture).
- Open for customization with other models.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Auth0r-C0dez/Caption_generator.git
   cd Caption_generator
   ```
2. Install the dependencies through requirements.txt:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the application:
   ```bash
   python app.py
   ```
2. Open the URL provided by Gradio in your web browser.
3. Upload an image and view the generated caption.

## Examples

### Input Image
<img src="assets/images/A group of people sitting around a table with laptops.jpg" alt="Example Image" width="300" />

### Generated Caption
> "A group of people sitting around a table with laptops."

## What i look for improvement ??
The project allows customization to improve its functionality:

- **Dataset and Keywords**: The dataset and the manually added list of keywords for image orientation and recognition can be modified or expanded to enhance the system's performance and accuracy.
- **Caption Orientation**: The logic for caption generation can be optimized further to provide more coherent and contextually appropriate captions.
- **Model Improvement** : Make the model better thus increasing the contents of the caption or qualitative arrangement of words in the caption
- **Personal improvement** : In case you have an idea of improving the model that doesnot fall in the above requirements do create a PR it would be lovely to see that.

Contributors are encouraged to experiment with these aspects and propose improvements.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add a detailed description of the change"
   ```
4. Push your changes:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request on the [main repository](https://github.com/Auth0r-C0dez/Caption_generator).

### Contribution Guidelines
- Follow the PEP8 coding standards.
- Document your code where necessary.
- Include tests for new features or bug fixes.

## Support
- Report issues via the [GitHub Issue Tracker](https://github.com/Auth0r-C0dez/Caption_generator/issues).
- For further assistance, contact the maintainer at [kafirana1507@gmail.com].

## FAQ

**Q: What types of images are supported?**
A: Standard image formats like PNG, JPEG, and BMP are supported.

**Q: Can I use my own model?**
A: Yes, the project is modular and allows integration of custom models.

## Attribution
Created by [Auth0r-C0dez](https://github.com/Auth0r-C0dez).

## License
This project is licensed under the [MIT License](LICENSE).

# HaPPy Coding
