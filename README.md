# Cloud Image Processing App

The Image Processing App is a Streamlit-based web application that allows users to upload images and apply various image processing operations. The app connects to a remote server to process the images and provides users with the ability to download the processed images.

## Sample Videos
- [GUI User Guide](https://drive.google.com/file/d/1xMva0H6TjYCj3Jngo-TJj_DvIYubBR6E/view "Streamlit APP GUI")
- [Backend Explanation](https://drive.google.com/file/d/1mlQHX3cwp0UdyVv_ogGD9HJUy2IGUoE8/view?usp=sharing "Backend Explanation")

## Features

- **Upload Multiple Images**: Users can upload multiple images in JPEG, JPG, and PNG formats.
- **Individual and Global Operations**: Users can select different image processing operations for each image or apply a single operation to all uploaded images.
- **Real-time Processing**: The app sends images to a remote server for processing and receives the processed images in real-time.
- **Download Processed Images**: Users can download individual processed images or all processed images at once.
- **GIF Feedback**: Visual feedback with GIFs is provided for actions such as connection closing and successful image processing.

## Supported Operations

The app supports the following image processing operations:

1. Edge Detection
2. Color Manipulation
3. Corner Detection
4. SIFT Feature Detection
5. Denoise Image
6. Erosion
7. Dilation
8. Histogram Equalization

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/image-processing-app.git
    cd image-processing-app
    ```

2. **Install dependencies**:

    Make sure you have Python 3.7+ installed. Then, create a virtual environment and install the required packages:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Run the app**:

    ```bash
    python app.py
    ```

    The app will automatically open in your default web browser.

## Usage

1. **Upload Images**:
    - Click on the "Upload Image(s)" button to upload one or more images.
    
2. **Select Operations**:
    - For individual images, expand the section for each image and select an operation from the dropdown list.
    - For applying the same operation to all images, select an operation from the sidebar under "Global Operations".

3. **Process Images**:
    - Click the "Process Image" button for individual images or "Process All Images" for global operations.
    - The app will display the original and processed images side by side.
    - If the process is completed you are expected to see this confirmation: -
      
    ![Bye_Gif](https://github.com/OmarMDiab/AWS-Distributed-Computing-Server_Client-App/blob/main/Client%20App/GIFS/Mission%20Accomplished.gif)

4. **Download Images**:
    - After processing, you can download each processed image by clicking the "Download Processed Image" button.
    - Alternatively, download all processed images at once by clicking the "Download All Images" button from the sidebar.

5. **Close Connection**:
    - To close the connection to the server, click the "Close Connection" button in the sidebar.

## Thank you
![Bye_Gif](https://github.com/OmarMDiab/AWS-Distributed-Computing-Server_Client-App/blob/main/Client%20App/GIFS/Close%20Connection.gif)
