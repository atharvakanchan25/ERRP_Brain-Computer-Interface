# 🧠 CognitiLearn: Brain-Computer Interface for Cognitive Enhancement

CognitiLearn is an Android-based Brain-Computer Interface (BCI) application designed to enhance cognitive performance through EEG-based brain games. The app leverages Error-Related Potentials (ErrPs), such as Error-Related Negativity (ERN) and Error Positivity (Pe), to detect cognitive errors in real time and adapt training exercises accordingly.

---

## 📱 Features

- 🎮 **Cognitive Training Games**
  - Dual N-Back (Implemented)
  - Pattern Matrix
  - Word Association
  - Speed Math
  - Number Crunch
  - Emotion Match *(Removed)*
  
- 📊 **EEG-based Monitoring**
  - Detects Error-Related Potentials (ErrP)
  - Adaptive difficulty and feedback based on user brain activity

- 🧠 **Neurofeedback Mechanism**
  - Focuses on brainwave-based error detection
  - Enhances learning through BCI-driven interactions

- 🧩 **Clean MVVM Architecture**
  - Built in Java using Android MVVM
  - Material Design UI for intuitive experience

---

## 🧪 Technologies Used

| Component        | Technology         |
|------------------|--------------------|
| Platform         | Android (Java)     |
| Architecture     | MVVM               |
| EEG Integration  | Custom EEG SDK / Stream (e.g., OpenBCI / Muse SDK) |
| Game Logic       | Java               |
| UI/UX            | Material Design    |
| Signal Processing| Python (for backend/preprocessing ErrP detection) |
| BCI Focus        | Error-Related Potentials (ERN, Pe) |

---

## 🧠 Brain Games Overview

| Game             | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Dual N-Back      | Trains working memory through audio-visual N-back tasks                     |
| Pattern Matrix   | Enhances pattern recognition and visual memory                              |
| Word Association | Builds verbal fluency and semantic processing                               |
| Speed Math       | Sharpens mental arithmetic and reaction time                                |
| Number Crunch    | Trains short-term memory using number sequence recall                       |

> **Note**: Emotion Match was planned but later removed for simplicity and clarity of ErrP signal processing.

---

