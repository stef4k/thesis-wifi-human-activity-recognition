# From Single- to Double-Pair: Improving Wi-Fi Human Activity Recognition on ESP32 Devices for Elderly Care
 
Master's thesis, Erasmus Mundus **Big Data Management & Analytics (BDMA)**, carried out at **ZoeCare** (Paris).
 
**Author:** Stefanos Kypritidis

**Advisor:** Piotr Antonik (CentraleSupélec & ZoeCare)
 
## Contents
 
| File | Description |
|------|-------------|
| [`thesis_report.pdf`](https://github.com/stef4k/thesis-wifi-human-activity-recognition/blob/main/thesis_report.pdf) | Full thesis report |
| [`thesis_presentation.pdf`](https://github.com/stef4k/thesis-wifi-human-activity-recognition/blob/main/thesis_presentation.pdf) | Defense slides |
 
## Overview
 
The thesis studies device-free human activity recognition (HAR) from Wi-Fi Channel State Information (CSI) for monitoring elderly people at home, using low-cost ESP32-S3 boards. It compares a single transmitter–receiver link with a double-pair setup, with activities performed outside the direct line of sight of either link, and focuses on cross-room generalisation (train in two rooms, test in a third).
 
Main results:
 
- A Siamese trunk with shared weights per link, targeted augmentation and test-time adaptation reaches **0.766 macro-F1** on six activities and **0.918** after merging the chair and floor endpoints, in unseen rooms.
- Performance holds in **real-time** use and on **continuous recordings**, with errors mostly at transitions between activities.
- The second link helps most during data collection. At deployment, a single well-placed link comes within 3–4 macro-F1 points of the two-link fusion. Recommendation: **collect with two pairs, deploy with one.**
 
**Keywords:** Human Activity Recognition · Wi-Fi Sensing · Channel State Information · Cross-Environment Generalisation · Elderly Care · ESP32
 
