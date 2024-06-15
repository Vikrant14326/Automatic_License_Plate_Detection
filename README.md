# Automatic License Plate Detection

This project uses the YOLO (You Only Look Once) object detection model to identify and read license plates from images or video streams. It leverages computer vision techniques and is deployed using Streamlit for an interactive user experience.

## Features

- **Real-time Detection**: Accurate and efficient license plate detection.
- **Model Training**: YOLOv5 model trained for 100 epochs on 433 pre-annotated images.
- **High Accuracy**: Achieved mAP@0.5-0.7 and mAP@5_0.95-0.5.
- **Deployment**: User-friendly web interface using Streamlit.

## Technologies Used

- Python
- PyTorch
- YOLO
- Streamlit

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/automatic-license-plate-detection.git
    cd automatic-license-plate-detection
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the YOLOv5 model weights and place them in the `weights` directory.

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open your browser and go to `http://localhost:8501`.

3. Upload an image or provide a video stream to detect license plates.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

