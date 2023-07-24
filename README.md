# qr-vid-gui
A method to extract code from qr codes in a video, output it to a live python editor, the terminal and a text file. This is a GUI fork of the qr-vid project found here: https://github.com/txtatech/qr-vid

# QR Code Video Decoder and Interactive Python Code Executor

This project decodes QR codes from a video, places the decoded text into a Python code editor, and allows you to modify and execute the code interactively.

## Features for: 'core-gui.py' which is the main entry point. Use it to create the core code base. 

It creates the needed JSON, SRT, TXT and PNG QR Codes and can be used for decoding qr codes from videos and extracting subtitles.

## Features for 'core-gui-code-editor.py'

- Video selection: Use the file dialog to select a video file.
- The application supports videos with `.mkv`, and `.mp4` extensions.
- QR code decoding: Decodes QR codes from the selected video and places the decoded text into the Python code editor.
- Interactive Python code execution: Modify the decoded Python code in the editor and execute it by pressing the "Run Code" button. The output of the code execution is printed to the console.
- Stop decoding: Stop decoding at any time by pressing the "Stop" button.

## Usage

1. Run the script with: `python3 core-gui-code-editor`
2. Click the "Open File" button and select a video file.
3. The application will start decoding any QR codes it finds in the video and placing the decoded text into the Python code editor.
4. Modify the code in the editor as needed.
5. Click the "Run Code" button to execute the code in the editor. The output of the code execution will be printed to the console.
6. Adjust the playback speed of the video as needed.
7. Click the "Stop" button to stop decoding.

## Dependencies

- Python 3
- OpenCV (`cv2`)
- `pyzbar`
- `wxPython`


# MIT License

Copyright (c) 2023

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

