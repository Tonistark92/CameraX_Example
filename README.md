# CameraX Project

This project demonstrates the use of CameraX in Android to capture images and videos using the front or back camera, record videos with audio, display the elapsed recording time, switch between cameras, and view captured photos in a bottom sheet gallery.

## Features

- **Capture Images**: Use the front or back camera to capture high-quality images.
- **Record Videos**: Record videos with audio using either camera.
- **Elapsed Recording Time**: Display the elapsed time while recording videos.
- **Switch Cameras**: Easily switch between the front and back cameras.
- **Gallery**: View captured photos in a bottom sheet gallery.

## Requirements

- Android Studio
- Minimum SDK version: 21
- CameraX dependencies

## Demo



https://github.com/Tonistark92/CameraX_Example/assets/86676102/14e71b57-6dd5-4300-bd94-a994c65a0b9e



## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/CameraXProject.git
    cd CameraXProject
    ```

2. **Open in Android Studio**:
    - Open Android Studio.
    - Select `Open an existing Android Studio project`.
    - Navigate to the cloned repository and select it.

3. **Add CameraX Dependencies**:
    Ensure the following dependencies are added in your `build.gradle` (app level):
    ```groovy
    implementation "androidx.camera:camera-core:1.0.0"
    implementation "androidx.camera:camera-camera2:1.0.0"
    implementation "androidx.camera:camera-lifecycle:1.0.0"
    implementation "androidx.camera:camera-view:1.0.0"
    implementation "androidx.camera:camera-video:1.0.0"
    ```

4. **Sync Project**:
    - Click on `Sync Now` in the notification bar to sync the project with Gradle files.

5. **Run the Application**:
    - Connect an Android device or use an emulator.
    - Click `Run` to start the application.

## Usage

1. **Capture Images**:
    - Launch the app and tap the capture button to take a photo.

2. **Record Videos**:
    - Tap the record button to start recording a video.
    - The elapsed recording time will be displayed.
    - Tap the stop button to end the recording.

3. **Switch Cameras**:
    - Use the switch camera button to toggle between the front and back cameras.

4. **View Captured Photos**:
    - Swipe up on the bottom sheet gallery to view the captured photos.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the Android team for CameraX library.
- Inspiration from various open-source CameraX projects.

