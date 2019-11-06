# How to Get the Best Group Photo

## 1. Overview
When we take group photos, we often see someone who blinked his/her eyes, someone who is blurred because they move at that moment or someone who didn't do the promised motion (e.g. making a V sign). These types of people spoil a nice group photo. However, it is bothersome to find the best group photo by checking such people manually among the series of photos. The purpose of our project is to find the best group photo among these series of photos. We will first apply optical flow to detect any movements in the photo, followed by applying eye blink and face detection, followed by hand localization, and finally, hand classification. The algorithm then excludes the photos which has blinking or blurred image and make a sensible recommendation based on the resulting photos.

## 2. Criteria for Best Group Photo and Input Assumption

- Everyone in the group photo are stationary.
- Everyone in the group photo are non-blinking.
- Everyone in the group photo take the same motion.

**Assume that enough input images are given and the images are sequential group photos.**

## 3. Steps for our project

- 3.1 Detecting Stationary Photos
- 3.2 Eye Blink Detection
- 3.3. Hand Pose Detection

[Click for Details](https://github.com/blackco66/2019CV-FinalProject/blob/master/Final_How%20to%20Get%20the%20Best%20Group%20Photo.pdf)