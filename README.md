# Getting Started with FPGA Project

# Dev Mode:

## Environment

This project has the following dependencies:

- **nodeJS.js** v12.16.1 or later [**Current tested running version: v18.5.0**]
- **npm** v6.13.4 or later [**Current tested running version: v8.12.1**]

### Installation through NVM

The Above mentioned node and Npm versions can be installed through NVM which is a tool for managing Node versions on your device.
You can install node/npm manually as well.

In your terminal, run the nvm installer like this:

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# or

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

You can use curl or bash depending on the command available on your device.
These commands will clone the nvm repository to a ~/.nvm directory on your device.

If you're using bash, that would be ~/.bash_profile...or some other profile.

If it doesn't automatically add nvm configuration, you can add it yourself to your profile file:

```sh
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

This command above loads nvm for use.

With your profile configuration updated, now you will reload the configuration for your terminal to use:

```sh
source ~/.bashrc
```

With this command executed, nvm is ready for you to use. You can confirm that nvm is installed correctly by running:

```sh
To check the nvm version
nvm -v
```

nvm install vX.Y.Z to install a specific version and nvm use vA.B.C to use a specific version

```sh
nvm install v18.5.0

nvm use v18.5.0
```

#### Windows(10 or later):

Download and install: - https://nodejs.org/download/release/v18.5.0/node-v18.5.0-x64.msi

## Run the Electron Application(Dev env):

### Clone:

     git clone git@gitlab.ignitarium.in:mips/fpga.git -b development

### Install node Package:

### `cd fpga`

### `cd frontend`

Install npm modules

### `npm install`

Run the electron application

### `npm run electron:dev`

Exit electron application
press ctrl+c in terminal

### `Ctrl+C`
