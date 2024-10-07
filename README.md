# Source Engine Diff Checker

This repository tracks the evolution of game movement code in the Source engine.  
Additionally, a more comprehensive misc directory contains updates from the TF2 engine branch to the CS:GO engine branch.

## Repository Structure

The repository is organized into several key directories:

### `collections/`

Contains a collection of all files from across different SDK versions. This directory serves as a reference point for comparing files across all versions simultaneously.

### `hl2/`

Contains the commit history showing the evolution of game movement code for Half-Life 2 across the following versions:
- Source SDK 2004
- Source SDK 2006
- Source SDK OrangeBox
- Source SDK 2013
- HL2 Source 2018 (TF2 branch)

### `csgo/`

Contains the commit history showing the evolution of game movement code for Counter-Strike: Global Offensive across the following versions:
- Source SDK 2004
- Source SDK 2006
- Source SDK OrangeBox
- Source SDK 2013
- CSGO Source 2018

### `cstrike-vs-csgo/`

Contains a specialized commit history that shows the evolution of game movement code from Counter-Strike: Source to Counter-Strike: Global Offensive:
1. Starts with HL2 Source 2018
2. Updates to CSGO Source 2018
3. Includes mod-specific overrides for Counter-Strike: Source and Counter-Strike: Global Offensive

### `misc/`

Contains a specialized commit history that:
1. Starts with HL2 Source 2018
2. Updates to CSGO Source 2018
3. Contains complete structure, without overwriting cstrike with cstrike15 content
- This is primarily directories of interest to me for back-porting maps and other various curiosities.

## Usage

1. Browse the commit history in each directory to see step-by-step changes.
2. Use GitHub's compare feature to view differences between specific versions.
