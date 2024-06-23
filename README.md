# iPhone-VCAM
A virtual camera based on Cydia Substrate

## Purpose
Replace the iOS system camera feed

## Supported Software
Supports the vast majority of apps

## Supported System Versions
The development and testing version is iOS 13.3. Due to lack of other versions, real device testing is not available.  
Theoretically supports iOS 11.0 and above.  
iOS 15 may have some issues, and currently, there is no jailbreak solution for iOS 15.

## Getting Started

### Installation

### Usage
In the following instructions:
- `-` represents the volume down button
- `+` represents the volume up button
- Switching between these within one second triggers the actions

#### Full Mode
There are more pop-ups, and some software may pause operation after a pop-up.

- **Hotkey:** `+ -`
  - Function: See button description
- **Download Video**
  - Each time a download is completed, a system mute prompt will pop up.
- **Video File**
  - Online video address. Ensure this link points to an accessible video.
  - If the file is corrupted, unplayable, or unsupported, no changes will occur.
- **Streaming Media (Not supported yet)**

#### Convenient Mode
Minimize pop-ups to avoid interrupting the current program's operation.

- **Hotkey:** `- +` triggers video selection
  - If the download video function is set, this hotkey will trigger the download video instead.
  - When the download video link is set to empty, it continues to use video selection.
  - After downloading, a mute mode pop-up will appear.
  - If the remote file is unavailable, replacement is disabled.

## Frequently Asked Questions
In the following instructions:
- `-` represents the volume down button
- `+` represents the volume up button
- Switching between these within one second triggers the actions

### Q: How to select video resolution?
**A:** Use the camera and press `+ -`. Detailed information will appear. If the width is greater than the height, it indicates the video direction is rotated. In most cases, the rear camera needs a 90-degree counterclockwise rotation, and the front camera needs a 90-degree clockwise rotation. Sometimes, rotation and horizontal flipping are required. The specific video direction depends on the software's processing method and needs to be observed by yourself. The replacement preview always maintains the correct direction. If the video's width and height do not match the prompt, issues like screen displacement, preview stretching, or crashes may occur.

In short, the replacement video's width and height must match the `+ -` hotkey prompt's W and H. Adjust the replacement video angle based on the previewed image.

### Q: Screen rotation after taking a photo?
**A:** The preview always maintains the correct direction. Some software directly processes horizontal images but rotates the preview for the user.

In short, rotate the replacement video in the opposite direction of the rotated preview.

## TODO
- Audio support
- Fix the issue where some software fails to loop recording after a while
