Royal GTPS Helper DLL
A custom utility and Discord Rich Presence (DRP) mod built for Royal GTPS, designed to enhance the game experience with custom window controls, FPS unlocking, server redirection, and live Discord status updates.

Features
Discord Rich Presence (DRP): Displays your current game status on Discord in real-time.

Shows whether you are in the Main menu, World menu, or playing in a specific World.

Displays live player counts fetched directly from the Royal GTPS server stats.

FPS Unlocker & Optimization: Bypasses default frame-rate limits for smoother gameplay using MinHook.

Window Enhancements:

Adds proper minimize and system menu options to the game window.

Automatically applies Windows Immersive Dark Mode to the title bar.

Server Redirection: Automatically routes official Growtopia domain requests ([www.growtopia1.com](https://www.growtopia1.com) / [www.growtopia2.com](https://www.growtopia2.com)) to the Royal GTPS server IP (15.235.167.45).

Debug Logging: Writes live game screen transitions and states to gtps_debug.log for easy troubleshooting.

Installation
Place the compiled DLL file (typically named dinput8.dll) into your main Royal GTPS game directory (where the game executable is located).

Ensure you have the required dependency files (such as discord_rpc.dll if required by your build setup) in the same folder.

Launch the game normally. The mod will automatically initialize via DLL proxying (DirectInput8Create).

Troubleshooting
If you encounter any issues or want to check what screen state the game is currently reporting:

Open the gtps_debug.log file located in your game directory using any text editor (like Notepad). It logs screen events and world changes in real-time.

Credits & Built With
MinHook for function hooking.

Discord Rich Presence API for status integration.
