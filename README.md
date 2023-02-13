# Installation instructions

## NOTE
This bot requires python version >3.11

- Go to the [discord developers portal](https://discord.com/developers/applications) and create an application and bot for yourself (for testing).
- Copy the bot secret token for later.
- After cloning the repository, create a virtual environment and install dependencies

```python
python3.11 -m venv venv
venv/bin/pip3 install -r requirements.txt
```

- From the discord developer portal, add the bot to a discord guild by generating a URL. Note that you do not need to award the bot any permissions such as "Administrator", "Send messages", etc.

- Start the bot in the following way

```bash
./obiesourcebot <SECRET TOKEN>
```
