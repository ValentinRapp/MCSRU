# MCSRU - Minecraft Server Resources Updater

## Spend less time doing repetitive tasks, and more time actually working

![image](productivity.png)
> Patch 0 day exploits before they even get found!

## What is this?

This tool allows you to update your minecraft server faster. You can use it to test which servermod/plugin/datapack/mod update works and which doesn't faster. You can see it like a kind of package manager but specifically for minecraft servers (except it isn't meant to produce production ready updates out of the box :p).


## Requirements
- [python](https://www.python.org/downloads/)


## Installation

- Clone the repo and put its files into a clone of your server.
```bash
git clone https://github.com/ValentinRapp/MCSRU.git
```
- Install the tool's dependencies.
```bash
pip -r requirements.txt
```
The tool is now installed.


## Usage
You can run the tool using `python MCSRU.py`.

There is a template `settings.json` file in the repo with a lot of resources pre-configured, you can look at it so you can write your own configuration file from it for your server's specific needs.

> This tool works by downloading the resources needed by fetching them from their sources directly, such as cursforge or modrinth for example, so you'll need to provide a link to the sources of the resources you want, but you'll only need to do that once for the initial configuration!

Once you've tested your updated clone and it works like it should, you can copy the relevent files into your main server, and tada, your server's now updated!