# JNAScreenShot

This repository contains a Java utility class `JNAScreenShot` that captures a screenshot of the entire desktop on a Windows system using the Java Native Access (JNA) library.

### Features:
- Utilizes JNA to interact with native Windows APIs.
- Captures the entire screen and saves it as a `BufferedImage`.
- Demonstrates usage of `User32` and `GDI32` APIs for screen capture.
- Handles memory management and bitmap operations efficiently.

### Dependencies:
- Java Native Access (JNA) library
- JNA Platform library

### Usage:
```java
BufferedImage screenshot = JNAScreenShot.getScreenshot();
// Now you can use the screenshot BufferedImage as needed
```

## License 
This project is licensed under the [MIT License](LICENSE).
