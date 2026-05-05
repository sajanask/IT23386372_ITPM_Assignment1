# ITPM Assignment 1 - Option 1 (IT23386372)

This repository contains the automated testing suite for Assignment 1 (Option 1) of the IT3040 - ITPM module. It utilizes Python and Playwright to automate the execution of 50 negative test cases against the PixelsSuite Chat Translator, verifying the system's robustness against informal Sinhala chat-style inputs (Singlish).

## Prerequisites

Before running the script, ensure you have the following installed on your system:
* **Python 3.11 or 3.12**
* **Google Chrome** (Recommended)

## Installation Instructions

1. Clone this repository to your local machine.
2. Open your Command Prompt or Terminal and navigate to the project folder.
3. Run the following commands sequentially to install the required dependencies:
```bash
# Upgrade pip to the latest version
pip install -U pip

# Install Playwright and Openpyxl (for Excel handling)
pip install playwright openpyxl

# Install the required Playwright browser binaries
python -m playwright install


## Execution Instructions
To run the automated test suite, ensure that all Excel files are closed. Then, run the following command in your terminal from the project root directory:

python test_automation.py --excel "IT23343948.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
