
# URL Content Downloader

A simple Python application with a graphical user interface (GUI) that allows users to download content from URLs, track download progress, and save the downloaded files to a specified location. The application also supports pausing and resuming downloads and maintains a history of downloads.

## Features

- **URL Validation**: Verifies if the entered URL is valid before attempting to download.
- **Download Progress**: Displays a progress bar with the download percentage, speed, and estimated time remaining.
- **Pause/Resume**: Allows users to pause and resume the download.
- **Download History**: Saves a record of each download, including the URL and file path, in a JSON file.
- **Log Output**: Displays log messages for various download events (e.g., download started, download completed, errors).
- **File Save Dialog**: Prompts users to select where to save the downloaded file.

## Requirements

- Python 3.6+
- `requests` library
- `tkinter` (for GUI)

You can install the required dependencies by running:

```bash
pip install requests
```

## How to Use

1. **Run the Application**:
   - Run the `gui.py` script to start the application.
   - The GUI will open, allowing you to enter the URL for the file you want to download.

2. **Enter the URL**:
   - In the "Enter URL" field, paste the URL of the content you want to download.
   - Click "Download" to begin downloading the content.

3. **Download File**:
   - A file dialog will open, prompting you to choose where to save the downloaded file.
   - Once the download starts, the progress bar will show the current download percentage, download speed, and estimated time remaining.
   
4. **Pause/Resume**:
   - You can pause the download by clicking the "Pause" button. The download can be resumed by clicking "Resume".

5. **Download History**:
   - You can view the download history by clicking the "Download History" button. A new window will open, showing the URLs and file paths of previously downloaded files.

6. **Log**:
   - The application maintains a log of events during the download, which will be displayed in the log text widget in the GUI.

## Download History

The download history is stored in a file called `download_history.json` in the same directory as the application. The file contains a list of all downloads with the following details:
- **URL**: The URL from which the file was downloaded.
- **File Path**: The location where the file was saved.

## License

This project is licensed under the MIT License.

## Acknowledgments

- This project uses the `requests` library for HTTP requests and downloading content.
- The `tkinter` library is used for creating the graphical user interface (GUI).

## Sample Image
<img width="502" alt="Gui" src="https://github.com/user-attachments/assets/1c327a79-7669-4740-a7f9-dc1bd3e1d59c">
