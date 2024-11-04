# AI-Based Pneumonia Detection System

## Demo Video

Watch the demo of the application here:  
[![Watch the demo](https://img.youtube.com/vi/Qr1q36yjAAg/0.jpg)](https://youtu.be/Qr1q36yjAAg)

## Overview

This project implements an AI-based system for pneumonia detection using machine learning techniques. The user interface is developed using Streamlit, allowing for easy interaction with the model. The application processes medical images to predict the presence of pneumonia, aiding in early diagnosis and treatment.

## Project Structure

```
.
├── .gitignore
├── Ai Base PND.mp4
├── LICENSE
├── README.md
├── app.py
├── main
├── pneumoniadetection.ipynb
├── saved_model.keras
└── util.py
```

## Getting Started

### Prerequisites

- Python 3.x
- pip
- [Anaconda](https://www.anaconda.com/products/distribution) (recommended for package management)

### Required Libraries

To run this project, you will need to install the following libraries:

- TensorFlow
- OpenCV-Python
- Pillow
- NumPy
- Streamlit

You can install these libraries using pip:

```bash
pip install tensorflow opencv-python pillow numpy streamlit
```

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ai-pneumonia-detection.git
   cd ai-pneumonia-detection
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv env_name
   source env_name/bin/activate  # On Windows use `env_name\Scripts\activate`
   ```

3. **Install Required Libraries**:  
   Use the command provided above to install the required libraries.

### Running the Application

1. **Start the Streamlit Application**:
   Run the following command to start the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Workflow

1. **Data Ingestion**:
   - The application processes medical images, typically X-rays, to prepare for pneumonia detection.

2. **Model Training**:
   - The model is developed and trained using the notebook `pneumoniadetection.ipynb`, which leverages deep learning techniques for accurate detection.

3. **Application Logic**:
   - `app.py` contains the main application logic, enabling users to upload images and receive predictions.

4. **User Interaction**:
   - Users can upload X-ray images through the Streamlit interface to determine the likelihood of pneumonia.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors and tools that facilitated the project, including libraries for machine learning and image processing.

