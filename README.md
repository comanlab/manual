# CiCL Manual

A guide for working on projects with the Cognition in Collectives Lab

## Introduction

## Onboarding

### Slack

### GitHub

## Setting up your computer

To work on our projects from your computer, you will need to install & configure a few primary software services and tools. Some of these are graphical user interfaces (GUIs), while others are command line interaces (CLIs).

### JavaScript environment

We use [Node Version Manager (NVM)](https://github.com/nvm-sh/nvm) to consistently manage Node.js and its versions in our projects that use JavaScript. To install, paste the following command into your Terminal application and run

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```

This will install `nvm` as a CLI, which will allow you to install and use various releases of the Node.js software. The installation should also have updated some of your system files that enable use of the `nvm` CLI. To verify your installation, run

```bash
command -v nvm
```

which should output `nvm` if successful.

#### Node

Once NVM is installed, you're ready to setup your default version of Node.js for working on CiCL projects using JavaScript. Start by running

```bash
nvm install 18.18.2
nvm alias default 18.18.2
```

Then, to check the Node.js version, run

```bash
node -v
```

which should output `v18.18.2`.

#### Node Package Manager (NPM)

Check the installation of Node Package Manager (NPM) that comes with Node.js and make sure it has the correct version by running

```bash
npm -v
```

which should output `v9.8.1` or higher.
