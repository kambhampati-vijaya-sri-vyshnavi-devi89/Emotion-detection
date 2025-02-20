# Facial Emotion Detection

## Overview
This project is a facial emotion detection system implemented in Google Colab. It processes an input image and performs multiple analyses:
1. Detects if the image contains a human face
2. Determines gender (male/female)
3. Classifies as kid or adult
4. Predicts age
5. Analyzes emotion

## Features
- Face detection using deep learning models.
- Gender classification.
- Age estimation.
- Emotion recognition using trained models.
- Outputs clear and structured results.

## Requirements
Before running the notebook, ensure the following dependencies are installed in your Colab environment:

```bash
pip install opencv-python numpy matplotlib tensorflow keras
```

## Usage
1. Upload the `emotionDetection.ipynb` notebook to Google Colab.
2. Run the cells sequentially to set up the environment and load models.
3. Provide an input image when prompted.
4. The system will analyze the image and display results for face detection, gender, age, and emotion.

## File Structure
```
|-- emotionDetection.ipynb  # Main Jupyter Notebook
|-- images/                 # Folder for input images (if applicable)
```

## Output
The notebook will output:
- Detected face (highlighted in the image)
- Predicted gender
- Age estimation
- Classified as kid or adult
- Recognized emotion

## Future Improvements
- Improve accuracy with larger datasets
- Add support for real-time video analysis
- Optimize model for better performance

## Contributors
-vijaya sri

## License
This project is open-source and free to use. Modify and distribute as needed.


