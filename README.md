# Incident-Response-Automation-with-Python

Overview:

This Python project automates the detection and response to Command and Control (C2C) attacks by analyzing Windows Event Viewer logs (EVTX files). Leveraging the python-evtx library, the system parses EVTX files, identifies C2C activity patterns, and responds to mitigate threats. The project enhances cybersecurity posture by facilitating proactive threat mitigation and efficient incident response mechanisms.

Features:

Automated parsing and analysis of Windows Event Viewer logs (EVTX files).
Detection of various C2C attack scenarios, including RDP tunneling via SSH.
Automated response actions such as blocking malicious IP addresses, terminating processes, and quarantining suspicious files.
Generation of detailed reports summarizing detected C2C activities.
Configurable and extensible for integration into existing security workflows.

Installation:

Clone the repository: git clone https://github.com/premihaa/C2C-Attack-Detection.git
Install dependencies: pip install -r requirements.txt

Usage:

Run the main script: python main.py path_to_evtx_file.evtx
Monitor console output for detected C2C activities and response actions.
Access generated reports in the specified output directory.

Configuration:

Adjust regex patterns in main.py to customize C2C detection criteria.
Configure email settings in config.py to enable email notifications for detected threats.

Contributing:

Contributions are welcome! Please submit pull requests or raise issues for feature requests, bug fixes, or improvements.

License:

This project is licensed under the MIT License. See LICENSE for more information.

Contact
For questions or feedback, please contact premihaa.m@gmail.com
