<p align="center">
  <img src="static/logo.png" alt="VideoCall Logo" width="120">
</p>

# VideoCall

## Introduction

**VideoCall** is the English edition of this digital avatar extension, built for the [SillyTavern](https://github.com/SillyTavern/SillyTavern) third-party extension system. When opened, it enters the video call flow directly, loads the bound avatar at runtime, and automatically plays AI voice replies with synchronized lip movement.

## Current Behavior

- Opening the extension enters the call flow directly
- Before the avatar finishes loading, a waiting screen is shown first
- During runtime, only the camera, hang up, and voice recording buttons remain in the bottom control bar
- While the avatar is loading, the camera and voice buttons stay disabled, and only hang up is clickable

## Features

- Real-time 3D avatar rendering during chat
- Automatic voice playback for AI replies
- Lip-sync animation driven by generated speech
- Bind avatars to a character or group
- Camera preview and snapshot capture inside the runtime view
- One-tap voice recording input after the avatar finishes loading
- Interrupt ongoing playback and generation

## Installation

### Method 1: SillyTavern built-in installer

1. Open SillyTavern.
2. Click the extensions button in the top bar.
3. Choose Install Extension.
4. Paste the repository URL:

```text
https://github.com/MrCzp/VideoCall
```

5. Refresh the page after installation finishes.

### Method 2: Manual install

```bash
cd SillyTavern/public/scripts/extensions/third-party
git clone https://github.com/MrCzp/VideoCall VideoCall
```

Then refresh the SillyTavern page.

## Requirements

- SillyTavern 1.12.0 or later
- A modern browser with WebGL 2.0 support
- Network access to Chinese service nodes
- Microphone permission for voice recording

## Related Links

- [GitHub Repository](https://github.com/MrCzp/VideoCall)
- [Report Issues](https://github.com/MrCzp/VideoCall/issues)
- [MIT License](./LICENSE)