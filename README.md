# Menu Project

Welcome to my menu project! This Python application uses the Tkinter library to provide a graphical user interface for various utility functions. The app includes features such as volume control, Google search, text-to-speech, image processing, and more.

## Features

- **Set Volume**: Adjust the system volume.
- **Google Search**: Perform a Google search and display results.
- **Text to Speech**: Convert text to spoken words.
- **Capture Image**: Capture an image using your webcam.
- **Apply Sunglasses Filter**: Apply a sunglasses filter to an image.
- **Send SMS**: Send SMS messages using Twilio.
- **Get Location**: Retrieve your current geographical location.
- **Apply Filters**: Apply various image filters (blur, sharpen, grayscale, etc.).
- **Create Custom Image**: Create and display a custom image.
- **Crop Image**: Detect and crop faces in an image.
- **Send WhatsApp Message**: Schedule a WhatsApp message.
- **Make Phone Call**: Initiate a phone call using Twilio.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/utility-app.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd utility-app
   ```

3. **Install the required Python libraries:**

   Create a virtual environment and install dependencies using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

4. **Create a `requirements.txt` file with the following content:**

   ```txt
   pycaw
   googlesearch-python
   pyttsx3
   opencv-python-headless
   pillow
   numpy
   twilio
   pywhatkit
   geocoder
   matplotlib
   ```

   Alternatively, you can install the libraries manually:

   ```bash
   pip install pycaw googlesearch-python pyttsx3 opencv-python-headless pillow numpy twilio pywhatkit geocoder matplotlib
   ```

## Usage

1. **Run the application:**

   ```bash
   python app.py
   ```

2. **Interact with the GUI:**

   - Click on the buttons to perform various tasks.
   - Follow the prompts and dialogs to provide necessary inputs.

## Code Overview

- **`app.py`**: The main Python script containing the Tkinter application and all utility functions.
- **Dependencies**: Ensure all required libraries are installed as specified in the `requirements.txt` file.


## Acknowledgements

- **Tkinter**: For the graphical user interface.
- **Pillow**: For image processing.
- **PyCaw**: For controlling system volume.
- **Google Search API**: For performing Google searches.
- **Pyttsx3**: For text-to-speech functionality.
- **Twilio**: For SMS and phone call functionality.
- **PyWhatKit**: For scheduling WhatsApp messages.
- **Geocoder**: For retrieving geographical locations.
- **OpenCV**: For image capture and face detection.
- **Matplotlib**: For displaying images.

