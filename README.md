# UTF-8 File Converter

A Python utility to convert text files within a specified directory to UTF-8 encoding. The script detects the current encoding of each file using the `chardet` library and then performs the conversion, handling any Unicode decode errors gracefully. It's designed for ease of use in a terminal environment and provides feedback with color-coded messages.

## Description

This script is designed to take the hassle out of converting text files to UTF-8 encoding. With the prevalence of UTF-8 as a standard encoding for text files, ensuring compatibility across different platforms and devices is important. This tool will scan all files in a specified directory, detect their encoding, and convert them to UTF-8. It will skip files already in UTF-8 format and handle any conversion errors encountered.

## Features

- Detects file encoding using `chardet`
- Converts files to UTF-8 encoding
- Skips files already in UTF-8 format
- Handles large files by processing in chunks
- Provides colored terminal output for easy status recognition
- Utilizes multiprocessing to handle multiple files concurrently
- Error handling for Unicode decode errors

## Installation

This script requires Python 3.x and the following Python packages: `chardet` and `concurrent.futures`. You can install `chardet` using pip if it's not already installed:

```bash
pip install chardet
```
No additional installation is needed for concurrent.futures as it is included in the standard library for Python 3.2 and later.


## Usage
1-Clone the repository or download the script to your local machine.

2-Open your terminal or command prompt.

3-Navigate to the directory where the script is located.

4-Run the script using Python:

5-python utf8_converter.py



The script will create a subdirectory named converted within the specified directory, where all the converted files will be stored.

Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

License
This project is open-sourced under the MIT License. See the LICENSE file for more details.

