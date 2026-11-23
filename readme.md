## ReShade Preset: Reshade Kless Preset

This preset improves color, shadows, texture detail, and sharpness in supported games.

## Installation

### 1) Install ReShade

1. Go to the official ReShade website: https://reshade.me/
2. Download and run the installer.
3. Select your game `.exe`.
4. Choose the rendering API used by the game (DirectX 9/10/11/12, Vulkan, or OpenGL).
5. Complete installation and download the default shader package when prompted.

### 2) Download this preset as ZIP from GitHub

1. Open this repository on GitHub.
2. Click **Code** > **Download ZIP** above.
3. Extract the ZIP on your computer.

### 3) Copy preset files to the game folder

1. Open the extracted ZIP folder.
2. Copy the preset files (such as `ReShadePreset.ini` and related files/folders) to the same folder as the game executable.
3. Launch the game and open the ReShade menu (default key is usually `Home`) to load the preset.

## Shaders & Addons

| Shader                                | Description                                                                            |
| ------------------------------------- | -------------------------------------------------------------------------------------- |
| **Ambience** (`ambient_v3.fx`)        | Better shadows and vegetation color via ambient removal and contrast curves.           |
| **Colorfull** (`Colourfulness_v3.fx`) | Better color palette via colourfulness and vibrance adjustments.                       |
| **Unit Sharpen** (`qUINT_sharp.fx`)   | Better image clarity and texture details via depth-enhanced local contrast sharpening. |
| **Levels** (`light.fx`)               | Black/white point remap for contrast balance.                                          |

## Performance HUD Addon

| Parameter                    | Config key         | Description                                                  |
| ---------------------------- | ------------------ | ------------------------------------------------------------ |
| Show performance issues only | `ColorLinesByLoad` | Colors lines by load and auto-shows lines in a warning state |
| Show CPU usage               | `ShowCPU`          | CPU usage                                                    |
| Show core usage              | `ShowCore`         | Per-core CPU usage                                           |
| Show GPU usage               | `ShowGPU`          | GPU usage per adapter                                        |
| Show GPU temperature         | `ShowGPUTemp`      | GPU temperature                                              |
| Show power draw              | `ShowPower`        | GPU power draw                                               |
| Show VRAM usage              | `ShowVram`         | VRAM used in GB                                              |
| Show RAM usage               | `ShowRam`          | System RAM used in GB                                        |
| Show battery level           | `ShowBattery`      | Battery charge percentage on laptops                         |
