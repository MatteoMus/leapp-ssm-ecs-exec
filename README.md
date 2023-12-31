<p align="center">
  <img src="https://github.com/Noovolari/leapp/blob/master/.github/images/README-1.png#gh-dark-mode-only" alt="Leapp" height="150" />
    <img src="https://github.com/Noovolari/leapp/blob/master/.github/images/README-1-dark.png#gh-light-mode-only" alt="Leapp" height="150" />
</p>

# Leapp ECS SSM COMMAND EXECUTION

## Introduction
This plugin simplify the process of executing command against your containers deployed in AWS ECS cluster through SSM.

## How it works
The plugin makes use of AWS Systems Manager (SSM) Session Manager to establish a connection with the running container and runs commands.
Executing the plugin, a terminal is open, asking interactively for some inputs:

1. Cluster ECS
1. Service
1. Task
1. Container
1. Command to execute

The plugin is a bash script.

## Prerequisites

1. OS: Linux, macOS
1. jq

## HOW TO INSTALL

Clone the repository and run:

```npm run build```

This command creates a folder named ```leapp-ssm-ecs-exec```

Copy this folder under your Leapp plugins folder:

```cp -r ./leapp-ssm-ecs-exec ~/.Leapp/plugins/leapp-ssm-ecs-exec```

