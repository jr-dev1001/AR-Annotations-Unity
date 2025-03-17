# AR Doodle Application

A Unity-based Augmented Reality drawing application utilizing AR Foundation for mobile devices.

## Overview
AR Doodle is an interactive drawing application that allows users to create artwork in augmented reality space. The application uses Unity's AR Foundation package for cross-platform AR functionality, with optimized implementations for both Android and iOS devices.

![image](https://github.com/user-attachments/assets/0bc8af13-de8f-45e5-87de-b2eff5f1f47b)


## Architecture
The application follows a modular architecture that separates core functionality from platform-specific features. Here's the high-level system architecture:



The diagram above illustrates the application's architecture, where:



The AR Processing subsystem feeds spatial data to the Drawing System, enabling accurate placement and tracking of drawn elements in 3D space. This integration ensures that doodles remain properly positioned relative to the real-world environment.

## Platform-Specific Features
The application handles different AR capabilities across platforms:

![image](https://github.com/user-attachments/assets/8633fce0-3e73-4c2c-8b46-8c9c31e5c9ef)



The diagram above illustrates how AR Foundation handles platform-specific features:



## Requirements
### Hardware
- Android device with AR capabilities
- Rear-facing camera
- Minimum 4GB RAM
- Compatible with Android 10.0 or higher

### Software
- Unity Hub
- Unity 2023.2 or later
- AR Foundation package
- Android Build Support module

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/jr-dev1001/AR-Annotations-Unity.git
   ```
2. Open project in Unity Hub
3. Import required packages:
   - AR Foundation
   - AR Core (for Android)

## APK Usage
1. Enable installation from unknown sources on your Android device
2. Install the APK
3. Grant camera permissions when prompted

## Technical Details
- Built with Unity 2023.2
- Utilizes AR Foundation for AR functionality
- Optimized for Android devices
- Includes feature toggle system for performance optimization

## Known Limitations
- Web browser support is not available due to AR Foundation requirements
- Device must support AR capabilities
- Some features may require specific hardware capabilities

## Troubleshooting
- Ensure device supports AR capabilities
- Check camera permissions
- Verify sufficient storage space


