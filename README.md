# How to run

1. Unzip the uploaded file

2. Launch your terminal and go to `<Your Path>/LittleLemonApp/LittleLemonApp/`

2. Launch the Xcode application

3. Select `iPhone 15 (17.5)` from the top navigation bar

4. `LittleLemonApp` -> TARGETS -> `LittleLemonApp` -> `Starting & Capabilities`
   1. Team -> Set your team
   2. Bundle Identifier -> Add the date to the end of the string

5. `Build Phases` -> `+` -> `New Run Script Phase` -> `Run Script` -> Shell /bin/sh -> Copy and Paste the following string
   - `/usr/bin/env xcrun --sdk macosx swift ${SRCROOT}/LittleLemonApp/Styles.swift ${SRCROOT}/LittleLemonApp/LittleLemonApp.swift`

6. `Product` -> `Scheme` -> `Edit Scheme` -> `+`
   - Input: `IDEPreferLogStreaming=YES`

7. Press the triangle icon in the upper left corner.

8. Congratulations! The simulator will start soon.
   -The food ordering app will be automatically launched in a while

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/littleLemonReservation.gif">
</p>