Stroke Detection App
This web-app prototype is designed to detect early signs of stroke using device sensors, with a focus on accessibility and real-time offline analysis. The goal is to provide users—especially those in high-risk groups or remote areas—with a quick, intelligent screening tool that compares current health data with their own baseline to identify signs of stroke onset.

How It Works
Upon registration, users record their baseline data through:
  Camera: Captures facial structure while smiling to assess natural symmetry.
  Microphone: Records voice samples to analyze speech clarity.
  Accelerometer: Collects data from arm movements to monitor for potential weakness or drift.
This information is securely stored locally (no internet needed), forming a unique health profile for each user.
During a stroke test, the app requests the same inputs and performs real-time comparisons to flag:
Facial Drooping (first sign): Detected via facial landmark symmetry checks.
Slurred Speech: Identified by changes in voice articulation and cadence.
Muscle Weakness: Detected by analyzing arm stability using sensor data.
If deviations from baseline exceed defined thresholds, the app alerts the user and recommends immediate medical attention.

Key Features
Offline-first design: Works without internet after initial setup.
Privacy-first: All data is stored and processed locally on the user’s device.
Simple UI: Designed for elderly and non-technical users.
Extensible: Modular architecture allows easy integration of cloud services or ML models.

Status
Currently in prototype stage. This was made for Mission: Brain Hackathon 2025.
