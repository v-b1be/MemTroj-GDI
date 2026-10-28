# MemTroj GDI Screen Distorter

A fun, open-source **Joke Program (GDI Trojan Simulator)** written in C++ using the Windows API. It generates chaotic visual glitches on the screen, plays an audio loop, and simulates system manipulation for entertainment and educational purposes. 

This project demonstrates how to interact with Windows graphics contexts (`HDC`) and use basic WinAPI functions.

## ⚠️ Disclaimer & Warning
**This software is provided "as is", without warranty of any kind.** 
The author is not responsible for any accidental disruptions. 

* This is a **harmless joke**—it does NOT delete, encrypt, or steal your data.
* It contains a loop that blocks standard Windows administration tools (Task Manager, CMD, PowerShell) to keep the visual effects running.
* **DO NOT run this on your main hardware.** Always test it safely inside a **Virtual Machine** (e.g., VirtualBox) or **Windows Sandbox**. To stop the program without restarting, ensure the console window is active and press `Alt + F4`.

## Features
* **GDI Visual Effects:** Screen melting, glitching screen stripes, and blood-red filling lines.
* **Cursor Tracking:** Destructive drawing of error icons (`IDI_ERROR`) that follow the mouse pointer.
* **Mouse Manipulation:** Randomly forces the cursor to bounce around the screen.
* **Sound Effects:** Loops a background audio track (requires `horror.wav` in the same directory).
* **Self-Defense Simulation:** Automatically kills Task Manager, Command Prompt, and PowerShell processes to prevent easy termination.

## How to Build
1. Open the project in **Visual Studio**.
2. Create a new C++ Console Application.
3. Paste the code from `memtroj.cpp` into your main file.
4. Set the build configuration to **Release** and **x86** or **x64**.
5. Compile the project.
6. Place your custom `horror.wav` file in the same folder as the compiled `.exe` to hear the sound effects.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
