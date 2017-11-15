# Devbox

Before running the scripts make sure:
 1. Your current directory is the *devbox root*.
 2. Devbox is in the *same directory* as other etheroscope repos.

## What this does.

- Installs necessary dependencies (e.g. `git`, `docker`...)
- Build & run development servers for:
  - etheroscope_ex
  - etheroscope_js

## Setup

To run the debox setup:
  1. Change to the directory of your desired dev OS.
  2. Run `./setup` (if that fails, run `chmod +x ./macos/setup` and try again), grab a coffee, sit back and wait for everything to be done for you.

(N.B. Linux setup not tested and Windows in development)

## Start/Stop Docker

You can both start and stop all docker containers running for etheroscope using the given scripts in root. i.e. just run `./start_docker` or `./stop_docker`.
