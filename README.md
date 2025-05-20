# 🧍‍♂️ PostureScan-AI

**PostureScan-AI** is an AI-driven application designed to monitor and improve a user’s posture in real time. By utilizing a webcam or smartphone camera, the system captures body movements and identifies poor posture habits such as slouching, forward head tilt, or improper wrist positioning.

PostureScan-AI provides instant feedback and corrective suggestions, making it an ideal tool for improving posture throughout the day, preventing musculoskeletal issues, and enhancing overall comfort.

## 📌 Features

- 📸 **Real-Time Posture Monitoring**:
  - Uses webcam or smartphone camera for posture tracking
  - Detects common posture issues like slouching, forward head tilt, and improper wrist angles
  - Provides visual feedback with annotated overlays on the user's image

- ⚡ **Instant Correction Suggestions**:
  - Offers immediate feedback on posture corrections
  - Highlights areas requiring improvement (e.g., spine alignment, shoulder positioning)
  - Step-by-step guides for better posture

- 📊 **Posture Analytics & Progress Tracking**:
  - Tracks posture over time with daily, weekly, and monthly reports
  - Visual charts showing posture improvements and areas of concern
  - Sets reminders for posture checks during prolonged sitting or standing

- 🧘‍♀️ **Exercise & Stretch Recommendations**:
  - Personalized stretching exercises based on detected posture issues
  - Customizable routines to improve mobility and prevent discomfort
  - Integration with fitness apps for a holistic wellness approach

- 🔐 **Privacy & Security**:
  - All data processing happens locally on the device
  - No video or image data is stored or uploaded to the cloud
  - Option to sync progress data securely with cloud storage if preferred

## 🛠️ Tech Stack

- **Frontend**: React Native, TensorFlow.js, Three.js (for 3D posture visualization)
- **Backend**: Python (TensorFlow, OpenCV)
- **Computer Vision**: PoseNet, BlazePose (for posture tracking)
- **Storage**: SQLite (local), Firebase (optional cloud sync)
- **Security**: HTTPS, AES encryption, OAuth2

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- Python 3.9+
- TensorFlow.js
- Expo CLI
- Webcam or smartphone with camera support

### Clone & Run

```bash
git clone https://github.com/your-username/posturescan-ai.git
cd posturescan-ai
npm install
npx expo start
