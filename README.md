# HealthWatcher Web Demo

Camera RGB Reading + Simple Heart Rate Estimation Demo.

This project is a web-based adaptation of the original [HealthWatcher](https://github.com/YahyaOdeh/HealthWatcher) project by **YahyaOdeh**.

The original project is an Android application that uses the mobile camera to capture RGB intensity data and estimate vital signs such as heart rate, blood pressure, respiration rate, and SpO₂.

This repository reuses and modifies parts of the original implementation to demonstrate camera-based RGB signal acquisition and simple heart rate estimation in a web browser.

## Original Project

* Original repository: https://github.com/YahyaOdeh/HealthWatcher
* Original author: YahyaOdeh
* Original project: HealthWatcher

The code in this repository has been **adapted and modified** from the original project for a web-based demonstration.

## Modifications

The original Android implementation has been adapted to a browser-based environment.

Main changes include:

* Reimplemented camera access using Web APIs
* Captured RGB information from camera frames
* Adapted the signal processing flow for the web environment
* Implemented simple heart rate estimation
* Created a lightweight standalone web demo

## Disclaimer

This project is intended for **educational and demonstration purposes only**.

The heart rate estimation provided by this demo is not intended for medical diagnosis or clinical use. Measurement accuracy may vary depending on the camera, lighting conditions, device hardware, and measurement environment.

## License and Attribution

This project is based on and contains modifications of code from the original **HealthWatcher** project by YahyaOdeh.

Please refer to the original repository for its license and attribution requirements:

https://github.com/YahyaOdeh/HealthWatcher

All original copyrights and license notices from the upstream project are retained where applicable.
