# Project Setup Instructions

## Prerequisites
Ensure you have the following installed on your system:
- Node.js and npm
- Python 3.x
- FFmpeg (for audio processing)

---

## Installation Guide

### Step 1: Clone the Repository
```bash
git clone <repository-url>
```

### Step 2: Unzip the File
If the repository was downloaded as a zip file, unzip it to your desired location.

### Step 3: Install Node.js Dependencies
1. Open a terminal.
2. Navigate to the unzipped project folder.
3. Run the following command:
   ```bash
   npm install
   ```

### Step 4: Install Python Dependencies
Run the following commands to install the required Python libraries:
```bash
pip install Flask
pip install flask-cors
pip install pillow
pip install cryptography
pip install numpy
pip install opencv-python
pip install pydub
```

### Step 5: Install FFmpeg
FFmpeg is required for audio processing. Follow the instructions in this video to install FFmpeg: [How to Install FFmpeg](https://youtu.be/4jx2_j5Seew?si=GXK2bEAQay0FQDmf).

---

## Running the Application

### Start the Node.js Server
Run the following command in the terminal:
```bash
npm run dev
```

### Start the Python Application
Run the Python application (`app3.py`) using your IDE or terminal. In Visual Studio Code, press:
```plaintext
Ctrl + F5
```

---

## Additional Notes
- Ensure all dependencies are installed before running the application.
- Verify that FFmpeg is correctly installed and added to your system's PATH.
