# ThreatSense: Autonomous Cyber Threat Prediction & Self-Healing Defense

## Introduction

In today’s world, cyberattacks are no longer limited to large companies or government organizations. Malware, phishing, ransomware, and unauthorized access attempts can affect anyone. Most cybersecurity systems only react after an attack has already taken place, which often leads to data loss, system damage, or privacy issues.

ThreatSense was created to solve this problem in a smarter way.

ThreatSense is an AI-powered cybersecurity platform that does not just detect threats — it predicts them before they become dangerous and automatically takes action to protect the system. It continuously monitors files, login activity, network traffic, and overall system behaviour in real time. If the system notices anything suspicious, it immediately responds through its self-healing defense mechanism.

This project was developed as a TY Semester 6 project at Sheth L.U.J. College of Arts & Sir M.V. College of Science and Commerce under [University Name], under the guidance of [Guide Name].

---

## What Makes ThreatSense Different?

Unlike traditional antivirus software or cybersecurity tools that simply show an alert after a threat is found, ThreatSense works proactively.

Instead of waiting for a cyberattack to happen, the platform studies patterns, predicts possible threats, and acts instantly. It can identify suspicious activity, block harmful files, isolate infected systems, and restore normal system functioning automatically.

Another important feature that makes ThreatSense unique is its strong focus on user privacy. Even though the platform includes an admin panel, the admin can never access private user information. All user login details and scan history are encrypted before being stored in MongoDB.

---

## Main Features

### Real-Time Monitoring

ThreatSense continuously keeps track of:

* Files being opened or uploaded
* Login attempts and user activity
* Network traffic and suspicious requests
* Running applications and system behaviour

The platform looks for unusual signs such as repeated failed logins, unknown software activity, suspicious file changes, or abnormal network usage.

### AI-Based Threat Prediction

The project uses Machine Learning algorithms such as:

* Random Forest
* Neural Networks

These models are trained using:

* Previous cyberattack datasets
* System logs
* User behaviour patterns
* Past scan history

By learning from this data, the system can identify:

* Malware
* Phishing attempts
* Ransomware behaviour
* Unauthorized access
* Suspicious network activity

The AI model is not fixed. Every time the system detects a new threat or receives new scan data, the model learns from it and improves itself. This continuous retraining helps ThreatSense become more accurate over time.

### Self-Healing Defense

When a threat is detected, ThreatSense automatically performs actions such as:

* Blocking malicious files or applications
* Isolating infected systems or processes
* Stopping suspicious network activity
* Restarting affected services
* Restoring the system back to normal

This reduces the effect of the attack and minimizes the need for manual intervention.

---

## Privacy and Security

One of the strongest parts of ThreatSense is its privacy-focused design.

* User login credentials are encrypted before being stored
* Scan history is also stored in encrypted form in MongoDB
* Even the admin cannot view usernames, passwords, or private scan records
* The admin panel is only allowed to:

  * View system performance
  * Analyse the Machine Learning model
  * Monitor overall threat statistics and logs
  * Manage platform settings

This creates a clear separation between system management and personal user data.

---

## Dashboard and User Features

ThreatSense includes a clean and interactive dashboard where users can:

* View live threat alerts
* Check scan reports and risk levels
* Monitor system health and model accuracy
* Review previous scans
* Export complete scan history in `.csv` format with timestamps

The exported file includes:

* Date and time of each scan
* Threat type
* Scan result
* Action taken by the system

---

## Accessibility Features

ThreatSense was designed to be easy to use for everyone. To make the platform more accessible, it includes:

* High-contrast mode
* Larger text support
* Keyboard navigation
* Screen-reader-friendly design
* Voice alerts for important warnings
* Dark mode
* Responsive design for desktop and mobile devices

These features make the platform more comfortable and inclusive for different users.

---

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript
* React

### Backend

* Python with Flask or Node.js

### Database

* MongoDB

### Machine Learning and Data Analysis

* Scikit-learn
* TensorFlow
* Keras
* Pandas
* NumPy

---

## Future Scope

ThreatSense can be improved further in many ways in the future:

* Adding Deep Learning and Reinforcement Learning for smarter predictions
* Supporting advanced cyber threats such as zero-day attacks and insider threats
* Connecting with cloud systems and IoT devices
* Introducing automatic backup and recovery
* Creating a mobile application for real-time monitoring
* Adding multilingual support and more accessibility tools
* Using live global threat intelligence for better accuracy
* Expanding the platform for use in banks, hospitals, industries, educational institutions, and smart cities

---

## Conclusion

ThreatSense is more than just a cybersecurity project. It is a step towards creating systems that can think, predict, protect, and recover on their own. By combining Artificial Intelligence, Machine Learning, privacy protection, and self-healing defense, ThreatSense provides a smarter and more modern approach to cybersecurity.

The project demonstrates how technology can be used not only to detect cyber threats, but also to prevent them before they become dangerous.
