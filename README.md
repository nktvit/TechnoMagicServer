# TechnoMagic server files

This repository contains the configuration and scripts for our Minecraft server.

## Setup Instructions

1. Clone this repository to your server.
2. Install the Minecraft server JAR file (not included in this repo).
3. Copy `config/server.properties.example` to `server.properties` and customize as needed.
4. Run `scripts/start_server.sh` to start the server.

## Directory Structure

- `config/`: Contains server configuration files.
- `mods/`: Store your mods here.

## Scripts

- `start_server.sh(.bat)`: Starts the Minecraft server.

## Updating

To update the server configuration:

1. Make changes locally.
2. Commit and push changes to GitHub.
3. On the server, pull the latest changes.
4. Restart the server to apply changes.