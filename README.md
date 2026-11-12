# Dhruv Gamepad - PS5 Edition
## Step 1: Controller design (Midnight black)

Only the look of the controller. No Bluetooth, no TV connection, no game input yet.

## How to run
1. Android Studio > New Project > Empty Views Activity (Kotlin). Package name: `com.dhruv.gamepad`.
2. Copy `GamepadView.kt` and `MainActivity.kt` into `app/src/main/java/com/dhruv/gamepad/` (replace the default MainActivity).
3. Replace the `AndroidManifest.xml` in `app/src/main/` with the one given here.
4. Run on your Android phone. It opens in landscape on a black background.

## What is in the design
- L1, L2, R1, R2 shoulder buttons
- D-Pad (up, down, left, right)
- Triangle, circle, cross, square buttons
- Left and right analog sticks (thumb moves a little when touched)
- Touchpad with blue light bar
- PS, Create, Options buttons

Touch only changes how a button looks while pressed. It does not send any input.

## Not tested yet
This code was written but not compiled or run on a device. Build it once and tell me about any error or anything that looks off.
