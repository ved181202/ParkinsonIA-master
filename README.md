# ParkinsonIA

ParkinsonIA is a Python-based application designed to assist in the detection of Parkinson's disease through voice analysis.
By leveraging machine learning techniques, the application analyzes vocal patterns to identify potential indicators of the disease.

## 🎥 Demonstration

Watch the presentation video to see ParkinsonIA in action:  
[![Watch the video](https://img.youtube.com/vi/K1oLz4x87Ug/0.jpg)](https://www.youtube.com/watch?v=K1oLz4x87Ug)

**Application Demo**  
![ExampleApp](https://github.com/user-attachments/assets/c4aa0e9e-0570-4759-bdff-767ee8869ffb)


## 📖 Related Article

For an in-depth understanding of the methodology and implementation, refer to this article:  
[Diagnosing Parkinson's Disease by Voice Using Linear Regression in Python](https://medium.com/@alan.marthineau/diagnosing-parkinsons-disease-by-voice-using-linear-regression-in-python-73aad2712fba)

## 🧠 Core Library

This project utilizes the [ParkinsonRecoLib](https://github.com/alan91620/ParkinsonRecoLib) for voice feature extraction and analysis.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or 3.8

### Installation

```bash
git clone https://github.com/ved181202/ParkinsonIA-master.git
cd ParkinsonIA-master
pip install joblib pandas numpy scikit-learn praat-parselmouth
```

#### PyAudio Installation

- **Windows**: `pip install pyaudio` (or install from .whl if needed)
- **macOS/Linux**: `pip install pyaudio` (ensure `portaudio` is installed)

## 🧪 Usage

### 1. Run the Application

```bash
python main.py
```

### 2. Using the Application

#### 🔊 Analyze an Existing Audio File

- Click on **Choose File**  
  ![ScreenAIStep1](https://github.com/user-attachments/assets/85cc120f-12aa-411c-a8c2-188c9eaea98e)

- Select a `.wav` audio file  
  ![parkinScreenWav](https://github.com/user-attachments/assets/de7c5956-096b-4282-98c2-63d9a92875c3)

- Click on **Detect** to process the file  
  ![ScreenAIStep2](https://github.com/user-attachments/assets/1de73731-da1a-43fa-a45e-f8227fac2739)

- View the result  
  ![ScreenAIStep3](https://github.com/user-attachments/assets/b5250695-eab8-4f32-9159-1f850b5e16ca)

#### 🎙️ Record Your Voice

- Click on **Recording**  
  ![ScreenAIRecordingStep1](https://github.com/user-attachments/assets/d098e625-99f3-4d1c-9586-8181c973decd)

- Read the displayed text aloud  
  ![ScreenAIRecordingStep2](https://github.com/user-attachments/assets/b97c65b7-ac53-4d09-84bf-71990c192bd2)

- Click on **Stop Recording**, then **Detect**  
  ![ScreenAIRecordingStep3](https://github.com/user-attachments/assets/2b96fa1e-4a0a-4593-aa5e-0050c9405933)

- View the analysis result  
  ![ParkiStep](https://github.com/user-attachments/assets/94a399d3-8ee5-4fc5-afae-92fb3bedb67c)

## 👥 Contributors

- Ved Joshi ([ved181202](https://github.com/ved181202))

## 📄 License

This project is licensed under the MIT License.
