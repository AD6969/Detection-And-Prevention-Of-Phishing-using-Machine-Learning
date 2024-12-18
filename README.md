# Detection-And-Prevention-Of-Phishing-using-Machine-Learning (Chrome Extention) 

## Overview

This project focuses on developing a Chrome extension that detects and prevents phishing attacks by leveraging machine learning techniques. The extension aims to safeguard users from malicious websites by analyzing multiple features of a URL and providing real-time alerts. The solution is designed to be lightweight, user-friendly, and effective in combating cyber threats.

## Key Features

- **Real-Time Phishing Detection**: Instantly analyze URLs and classify them as safe or malicious.
- **Machine Learning Integration**: Utilize advanced ML algorithms trained on a comprehensive dataset of phishing and legitimate URLs.
- **Feature-Based Analysis**: Extract and evaluate over 25+ URL features, including domain age, URL length, and keyword usage.
- **Interactive User Interface**: Seamless integration with the Chrome browser to provide intuitive alerts and feedback.
- **Preventive Action**: Block access to identified phishing websites, ensuring user security.

## Components

1. **Machine Learning Model**:
   - Trained using datasets comprising phishing and legitimate URLs.
   - Features include lexical properties, domain information, and page behavior.
   - Utilizes classification algorithms for high accuracy.

2. **Chrome Extension**:
   - Developed using HTML, CSS, and JavaScript for a responsive user interface.
   - Communicates with the backend ML model to evaluate URLs in real-time.

3. **Backend Server**:
   - Hosts the trained machine learning model.
   - Processes feature extraction and classification requests from the Chrome extension.

## Benefits

- Protects users from falling victim to phishing attacks.
- Enhances awareness of cyber threats.
- Provides a proactive approach to internet safety.

## How It Works

1. The user visits a website, and the Chrome extension automatically extracts the URL features.
2. The extension sends the features to the backend server for analysis.
3. The ML model classifies the URL as safe or malicious.
4. If malicious, the extension alerts the user and blocks access to the website.

## Future Scope

- **Deep Learning Models**: Incorporating neural networks for improved detection accuracy.
- **Cross-Browser Compatibility**: Extending support to other browsers like Firefox and Edge.
- **Phishing Page Detection**: Identifying cloned web pages using visual and content-based features.
- **Dynamic Analysis**: Enhancing the system to detect threats that evolve over time.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Detection-And-Prevention-Of-Phishing.git
   ```
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" and click "Load unpacked."
4. Select the project folder to add the extension.
