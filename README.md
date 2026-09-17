# Oxeno Device Provisioner

Windows tool used at the counter to set up a new phone in one pass: installs the
System Manager app, turns on device management, and hands off to the on-device
enrollment screen.

This repository holds **releases only** — no source code. The `.exe` on each
release is built and published automatically from our private repository.

## Download

Grab the latest installer from the
[Releases page](https://github.com/oxeno-link/device-provisioner-releases/releases/latest) —
look for `Oxeno Device Provisioner Setup <version>.exe`.

Releases older than 30 days are removed automatically, so always use the
latest one.

## Using it

1. Install and open **Oxeno Device Provisioner**.
2. On the phone, enable **Developer options** → turn on **USB debugging**.
3. Connect the phone to this computer with a USB cable, and accept the
   "Allow USB debugging" prompt on the phone if it appears.
4. Select the phone from the list, wait for the checks to pass, then continue.
5. Wait for install → management setup → verification to finish, then hand the
   phone to the customer to complete on-device enrollment.

If a step fails, the app shows the specific reason (e.g. USB install blocked,
Play Protect, no storage) rather than a generic error — follow what it says,
or contact support with that message if unsure.
