# Lucas's toolbelt

This folder contains scripts that help me do my day-to-day work more easily.

## Installation

To install `tb`:
1. Install [task](https://taskfile.dev/installation/)
2. Clone this repo
3. Add the repo to your `PATH`
4. Create a `.env` file with your variables, based on `.env.default`
5. In each folder you'll use `tb`, create a `.tb` file with extra folder-specific variables.

Some commands need extra dependencies, e.g `kube` commands may need `kubectl` and/or `istioctl`. Make sure you install the dependencies of the commands you use.

## Usage
Find available commands
```
tb --list-all
```
