## aerial-watchdog

Little helper script. Installs a LaunchAgent that monitors `legacyScreenSaver` and automatically kills it if it detects that the saver process has hung and is eating the CPU.

This problem seems to occur on some macOS Sonoma 14 machines. See: https://github.com/JohnCoates/Aerial/issues/1341

### Install

- Download the `ss_watchdog` script
- copy it to `/usr/local/bin`
- execute `ss_watchdog --install` to install the Agent

### Uninstall

- execute `ss_watchdog --uninstall`
