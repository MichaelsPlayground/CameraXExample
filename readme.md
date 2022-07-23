# CameraX example

Tutorial: https://medium.com/swlh/introduction-to-androids-camerax-with-java-ca384c522c5

Code: https://github.com/whichperson/cameraxtutorial

This app provides a live view of the camera feed. Additionally it shows the degrees of orientation 
(portrait is 0)

WORKING !

Gradle (original):
```plaintext
def camerax_version = "1.0.0-beta07"
implementation "androidx.camera:camera-camera2:$camerax_version"
implementation "androidx.camera:camera-lifecycle:$camerax_version"
implementation "androidx.camera:camera-view:1.0.0-alpha14"
```

Gradle (updated):
```plaintext
def camerax_version = "1.1.0"
    implementation "androidx.camera:camera-camera2:$camerax_version"
    implementation "androidx.camera:camera-lifecycle:$camerax_version"
    implementation "androidx.camera:camera-view:$camerax_version"
```

AndroidManifest:
```plaintext
<uses-feature android:name="android.hardware.camera.any" />
<uses-permission android:name="android.permission.CAMERA" />
```

