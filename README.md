# Automatic Face Capture

Real-time face detection and automatic photo capture using TensorFlow BlazeFace and React.

## Overview

Web application that automatically detects faces using the camera and captures photos when a face is properly positioned. Built with TensorFlow.js BlazeFace model for fast, client-side face detection.

## Features

- Real-time face detection via webcam
- Automatic photo capture when face detected
- Client-side processing (no server required)
- Responsive React interface

## Tech Stack

- **React** - UI framework
- **TensorFlow.js** - ML runtime
- **BlazeFace** - Face detection model
- **MediaDevices API** - Camera access

## Installation

```bash
npm install
npm run dev
```

## Usage

1. Grant camera permissions when prompted
2. Position your face in the camera view
3. Application automatically captures when face is detected
4. Photos are saved locally

## How It Works

1. Captures video stream from webcam using `getUserMedia()`
2. Runs BlazeFace model on each frame to detect faces
3. When face detected with high confidence, triggers automatic capture
4. Saves captured image to local storage
