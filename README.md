# AI-Powered-Psychological-Stress-Decision-Fatigue-Detection
## Overview
This project focuses on detecting psychological stress and decision fatigue using AI models trained on speech and text data. It leverages deep learning techniques to analyze stress indicators and provide meaningful insights.

## Features
- **Speech-Based Stress Detection**: Analyzes voice patterns to identify stress levels.
- **Text-Based Stress Detection**: Uses keystroke dynamics and text sentiment for stress assessment.
- **Pre-Trained AI Models**: Includes trained models for speech-based and text-based stress detection.
- **Applicable Use Cases**: Workplace stress monitoring, mental health analysis, and cognitive load assessment.

## Project Structure
```
├── data/
│   ├── speech_samples/         # Raw speech stress data
│   ├── text_samples/           # Raw text-based stress data
│
├── model/
│   ├── speech_model.keras      # Trained speech model
│   ├── text_model.h5           # Trained text model
│   ├── speech_label_encoder.pkl # Label encoder for speech model
│   ├── text_label_encoder.pkl   # Label encoder for text model
│   ├── tokenizer.pkl           # Tokenizer for text model
│
├── notebooks/
│   ├── speech_stress_model.ipynb  # Jupyter notebook for speech model
│   ├── text_stress_model.ipynb    # Jupyter notebook for text model
│
├── requirements.txt    # Required Python packages
├── README.md           # Project documentation
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/LAKAVATHRAGHURAM/AI-Powered-Psychological-Stress-Decision-Fatigue-Detection.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
- Run the speech stress detection model:
  ```sh
  jupyter notebook speech_stress_model.ipynb
  ```
- Run the text stress detection model:
  ```sh
  jupyter notebook text_stress_model.ipynb
  ```

## Dataset Information
The dataset includes:
- **Speech Samples**: Actor-based stress-inducing speech recordings
- **Text Samples**: Keystroke and text sentiment-based stress indicators

## AI Models
- **Speech Model**: `speech_model.keras`, `speech_label_encoder.pkl`
- **Text Model**: `text_model.h5`, `text_label_encoder.pkl`, `tokenizer.pkl`

## Future Enhancements
- Integration of real-time stress detection via microphone input
- Mobile application for stress tracking
- Improved accuracy with additional text analysis techniques

## Contributors
- **Lakavath Raghuram** (IIIT Kottayam) 


