# 📊 OpenClaw System Resource Monitor

A clean, reliable system resource monitor for CPU load, RAM, Swap, and Disk usage. Optimized for OpenClaw.

![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blue) ![Status](https://img.shields.io/badge/Status-Active-green)

## Overview

This skill provides concise, real-time server health reports using native system calls for maximum reliability and speed. It's designed to be a lightweight and efficient way to monitor your OpenClaw environment.

## Features

- **CPU Load**: Displays 1, 5, and 15-minute averages.
- **Memory**: Tracks both physical RAM and Swap usage.
- **Disk**: Monitors root partition capacity and percentage.
- **Uptime**: Shows how long your system has been running.

## Installation

> [!NOTE]
> This skill is designed to run within an OpenClaw agent environment.

No special installation steps are required beyond ensuring the skill files are present in your OpenClaw workspace.

## Usage

Simply ask your OpenClaw agent for system status, resource usage, or server health. For example:



> [!TIP]
> The skill executes the local  script to gather system information.

## Configuration

This skill does not require external configuration. All parameters are derived from system calls.

## File Structure



> [!IMPORTANT]
> Ensure the  script has execute permissions.


