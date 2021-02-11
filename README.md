# yeet

Node.js Discord Message Nuker

**/!\ Warning: This is against Discord's TOS. Use at your own risk. I've had no issues running this constantly for months.**

## Installation

- Install [Node](https://nodejs.org/en/download/)
- [Download the repo](https://github.com/ChxseH/yeet/archive/main.zip)
- Open a terminal and cd into the script folder.
- Run `npm install`

## Config

- `cp _config/config.example.yml _config/config.yml`
- Edit the config file to add your token, time values, and servers/dms to exclude (if needed).

### Time Configuration
- The `run` value can be `once` or a local time `at 1:00 am` as an example.

### Grabbing your token
- Open Discord, then press CTRL+SHIFT+I
- Select the Network Tab
- Click on "XHR"
- Type `api/v` on the filter box.
- Click on any request, then click on `Headers`, you're looking for something like: `mfa.I_yJwSaP[.......]`  

[Here's an image with steps if this is confusing](https://i.imgur.com/q2esGXI.png)  

**DO NOT SHARE YOUR authToken!**  

*Sharing your authToken on the internet will give full access to your account! If you post your token by accident, LOGOUT from discord on that same browser you got that token imediately. Change your password and turn on 2FA right after.*

## Usage

**Running with `run` set to `once` is recommended for the first time if you have a lot of messages.**

**Run this on the same machine/IP you most commonly use Discord from, to prevent account locking.**

- Using a process manager (i.e. screen, tmux, pm2, etc) is recommended, so you don't have to keep restarting yeet.
- To launch yeet, simply run `npm run yeet` inside the script folder. Keep it running in the background if you want automated deletion.

## Credits
* GitHub User protospherical for originally writing this script, they appear to have deleted their account.
* [EsmailELBoBDev2](https://github.com/EsmailELBoBDev2/yeet)'s mirror of the repo.
