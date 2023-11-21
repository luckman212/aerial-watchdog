### aerial-watchdog

Little helper script. Installs a LaunchAgent that monitors `legacyScreenSaver` and automatically kills it if it detects that the saver process has hung and is eating the CPU.

This problem seems to occur on some macOS Sonoma 14 machines.

see: https://github.com/JohnCoates/Aerial/issues/1341
