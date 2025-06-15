# Theia IDE Browser Build Automation

This repository contains GitHub Actions workflows to automatically build and release browser versions of Eclipse Theia IDE.

## Features

- **Scheduled builds**: Checks for new Theia releases every 6 hours
- **Manual triggers**: Allows building specific versions on demand
- **ARM64 support**: Builds run on Ubuntu 22.04 ARM runners
- **Automatic releases**: Publishes built artifacts to [theia-ide-browser-build](https://github.com/SilenWang/theia-ide-browser-build)

## Usage

### Scheduled Builds
The workflow runs automatically every 6 hours. No manual intervention needed.

### Manual Builds
1. Go to Actions tab
2. Select "BUILD" workflow
3. Click "Run workflow"
4. Enter the version tag you want to build
5. Click "Run workflow"

## Output
Built artifacts are published to:
https://github.com/SilenWang/theia-ide-browser-build/releases
