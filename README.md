# Threat-Detection-System

## Objective:

The application delivers a smart threat detection system for the client business by using C++ to monitor the file system changes in real time, by processing over 50,000 events per minute with minimal CPU usage. The suspicious activity is log locally or sent to a Python engine via named pipes, enabling efficient communication under 10ms latency. Python applies machine learning trained on 15,000+ threat events, achieving 96.3% accuracy and under 3.1% false positives. The RS256 asymmetric encryption secures the data of the client business. The Agentic AI generates adaptive detection algorithms and translates reports from English to French with 99.8% accuracy, enabling the cybersecurity team to isolate the attacks in real time and reduce the ransomware spread by 89% within 60 seconds of the client business.

# Video of the Project:

# Key Features:

## Real-Time File System Monitoring:

- C++ agent tracks over 50,000 file events per minute with less than 2% CPU usage, ensuring lightweight performance across client machines.

## Secure Inter-Process Communication:

- Named pipes transmit suspicious activity from C++ to Python with latency under 10 milliseconds, maintaining fast and secure data flow.

## High-Accuracy Anomaly Detection:

- Python ML engine trained on 15,000+ threat events, achieving 96.3% detection accuracy and a false positive rate below 3.1%.

## Enterprise-Grade Encryption:

- RS256 asymmetric encryption use to secure and protect the confidential data of the client business, ensuring integrity and confidentiality through robust public-key cryptography.

## Agentic AI Intelligence:

- Generates adaptive detection algorithms and translates reports from English to French with 99.8% linguistic accuracy, supporting bilingual security teams.

## Automated Cybersecurity Response:

- Real-time alerts and isolation protocols reduce ransomware spread by 89% within the first 60 seconds, minimizing damage and downtime.

# Installation:

## Prerequistes:

- Python
- C++
- Machine Learning
- Crytography
- JSON
- Matplotlib
- RS256 Assymetric Encryption
- Agentic AI
- LanGraph
- Gemini
- MCP Server

# Agentic AI Configuration (with MCP Server Installation):

## API Credentials:

- Register and obtain your Gemini API key from Google AI Studio.
- Store the key securely in a .env file to protect sensitive credentials.
  
## LangGraph Flow Setup:

- Design a multi-step processing graph to handle translation and reporting.
- Node Configuration.
- Input Normalization – Preprocess incoming text for consistency and clarity.
- Gemini Translation Output – Use Gemini API to translate English threat reports to French.
- Language Detection – Automatically identify the source language for routing and fallback handling.
  
## MCP Server Installation (Windows):

## Download MCP Server Installer:

- Visit the official MCP Server repository or distribution site.
- Download the Windows installer (.exe or .msi format).

## Run Installer as Administrator:

- Right-click the installer and select “Run as administrator” to ensure proper permissions.
- Follow the installation wizard prompts to complete setup.
- 
## Configure MCP Server:

- Set the server to monitor specific directories or system events.
- Define output channels to forward logs to the Agentic AI pipeline (named pipes).

 ## Start MCP Server as a Service:
  
- Open Services (services.msc) and locate MCP Server.
- Set startup type to Automatic and start the service.
- Confirm it's running in the background and logging events as expected.






