# 🎵 **YukkiMusic** 🎶

[**HyperMusic**](https://github.com/ll-hyper/HYPER) is an enhanced version of the original [**HyperMusicBot**](https://github.com/ll-hyper/HYPER), optimized for high-quality music streaming in Telegram voice chats. Built with Python and Pyrogram. 🚀

## ⭐ Support the Original
If you're using or forking this project, please show your support by starring the original repo:
[**HyperMusicBot**](https://github.com/ll-hyper/HYPER)


## 🚀 Quick Deployment Options
l
### Deploy on Heroku
Get started quickly by deploying to Heroku with just one click:

<a href="https://dashboard.heroku.com/new?template=https://github.com/ll-hyper/HYPER">
  <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="200"/>
</a>

### 🖥️ VPS Deployment Guide

  - Update and Install Dependencies: `sudo apt update && sudo apt upgrade -y && sudo apt install -y ffmpeg git python3-pip python3-venv tmux nano`

  - Create the Virtual Environment: `python3 -m venv .venv`

  - Activate Virtual Env: `source .venv/bin/activate`

  - Clone the Repository: `git clone https://github.com/ll-hyper/HYPER && cd HYPER`

  - Install Python Requirements: `pip install -r requirements.txt`

  - Copy and Edit Environment Variables:

    Copy the sample environment file: `cp sample.env .env`

    Edit the variables in the .env file: `nano .env`

  After editing, press `Ctrl+X`, then `Y`, and press **Enter** to save the changes.


  -  Run the Bot: `bash start`

  - Keep the Bot Running with tmux: `tmux`

To exit the **tmux session** without stopping the bot, press `Ctrl+b`, then `d`.
