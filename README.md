# React-Native Modal simple demo

This sample app is uploaded to reproduce issue in Modal component.
Code is almost same as [official guide](https://facebook.github.io/react-native/docs/modal.html)

## Issue
On android 7.1.1, Modal component becomes invalid state when power button is pressed.

## Steps to reproduce

0. Run android emulator whose API level is 25.
1. Show Modal component
2. Press power button, screen turns off. 
3. Press power button again, screen turns on.
=> Modal component disappears but it's transparent background still remains.

ON android 6 or 8, Modal component remains after the step 3.
