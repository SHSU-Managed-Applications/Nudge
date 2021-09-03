# Nudge

Nudge is an application for enforcing macOS updates, written in Swift/SwiftUI 5.2. The latest versions only support macOS 11.0+. The Python version for Nudge is EOL but still functions for MacOS 10.15.7 and below.

Nudge is developed and maintained by macadmins.

[macadmins/nudge](https://github.com/macadmins/nudge)

## Purpose

SHSU's Implementation of Nudge is intended for macOS 11.0 and Apple Silicon (M1) devices. Apple has made it substantially more difficult to manage Software Updates.

This .git is intended to host the JSON configuration file that Nudge will reference each time on launch. There will be a Production and Development JSON file for use with the respective devices.

## How it Works

[Nudge Wiki](https://github.com/macadmins/nudge/wiki)

Nudge has Three components that it uses to function:

1. The Nudge Application that must be installed on each workstation
2. The Nudge LaunchAgent responsible for running the application and referencing the desired configuration
3. The Configuration settings set be either a JSON file or Configuration Profile (Typically MDM)

## SHSU Implementation

TBD
