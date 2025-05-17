# Threat Logger Addon for Turtle WoW

## Requirements
1. Enable 'TWThreat' addon and 'ThreatLogger' Addon,
2. Stay in a `party` or `raid`,
3. Attacking an `elite` or `boss` level mob.

## Overview

The **Threat Logger** is a simple addon designed for Turtle WoW that helps players monitor their threat levels during combat. It logs threat changes and provides useful information in the chat window.

## Features

- Monitors threat levels for the player.
- Logs threat changes and displays them in the chat.
- Allows players to enable or disable the logging feature.
- Customizable player name for monitoring.

## Installation (Vanilla, 1.12)

1. Download the Threat Logger addon files.
2. Unpack the Zip file
3. Rename the folder "ThreatLogger-main" to "ThreatLogger"
4. Copy "ThreatLogger" into Wow-Directory\Interface\AddOns
5. Restart WoW game client.


## Commands

You can control the Threat Logger using the following commands in the chat:

- `/tlg on` - Enable the Threat Logger.
- `/tlg off` - Disable the Threat Logger.
- `/tlg save` - Save the logged data to a file.
- `/tlg name <PlayerName>` - Set the player name to monitor (default is your character's name).
- `/tlg about` - Display the current version of the Threat Logger.

## Saving Logs

To save your logged data, just wait for leaving combat or use the command `/tlg save` in the middle of a combat, and do a quick '/reload' to save the data to the file `ThreatLogger.lua` file located in your character's `SavedVariables` folder.