# Drawing Difference Detection

## Overview

The Drawing Difference Detection project is designed to compare two revision drawings of a spring and highlight the differences between them. This tool helps engineers quickly identify changes between old and new versions, improving accuracy and reducing errors in design analysis.

## Features

- **Automated Difference Detection**: Uses Structural Similarity Index (SSIM) to detect changes between two images.
- **Visual Highlighting**: Marks the detected differences with bounding boxes for easy identification.
- **User-Friendly Interface**: Web-based application using Flask for seamless image uploads and processing.
- **Fast and Efficient**: Processes images in seconds, saving time for engineers and designers.

## Installation

### Clone the Repository
```bash
git clone https://github.com/JayachandranSA/Drawing_Difference_Detection.git
cd Drawing_Difference_Detection
```

### Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage

### Running the Application
```bash
python app.py
```

Once running, open your browser and go to:
```
http://127.0.0.1:5000/
```
Upload two images and click **Compare** to visualize the differences.

## Repository Structure
```
├── uploads/        # Stores uploaded images
├── results/        # Stores processed images with differences marked
├── src/
│   ├── detect_diff.py   # Core script for image comparison
│   ├── app.py          # Flask application
├── requirements.txt    # Required Python dependencies
├── README.md           # Project documentation
```

## Future Improvements

- **Enhancing detection accuracy** with deep learning-based image comparison.
- **Adding support for multiple image formats** such as PDF and vector drawings.
- **Deployment as a cloud-based API** for enterprise use.

## Contributions

Feel free to contribute by submitting issues or pull requests.

## Contact

For any queries, reach out to JayachandranSA via GitHub or email: [jayachandran.sa@outlook.com]

🚀 Happy Coding!
