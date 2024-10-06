# LSEG Tech Engineering Workshop 2024 - Robocode Tank Royale Tournament

Welcome to the LSEG Tech Engineering Workshop 2024 - Robocode Tank Royale Tournament.

This is a chance for you to showcase your team's engineering abilities by building bots to battle against bots developed by other teams in a virtual arena.

This event is based on the opensource Robocode Tank Royale platform.

### Tournament Structure

The tournament is structured into three rounds, featuring a series of battles which will be screened at the Engineering Workshop:

- Preliminary Rounds - Participants compete in various battles, and the top scorers from each will advance to the Semi-Finals, while others will be eliminated.
- Semi-Finals - The highest scorers from the Preliminary Rounds face off for a chance to secure a spot in the Finals.
- Finals - The four top scorers will compete in the ultimate showdown for grand cash prizes.


## Example of a battle

<img src="docs/robocode-battle-anim.gif" alt="GIF animation of tanks battling each other on a 2D battlefield">

## Documentation 

Please refer the below documentation to understand the TankRoyale bot APIs as well as various strategies you can implement.

[Tank Royale Home](https://robocode-dev.github.io/tank-royale/)

[Tank Advanced Concepts](https://robocode-dev.github.io/tank-royale/tutorial/beyond-the-basics.html)

[API Overview](https://robocode-dev.github.io/tank-royale/api/java/index.html)

[Bot API - Classes, Interfaces & Methods](https://robocode-dev.github.io/tank-royale/api/java/dev/robocode/tankroyale/botapi/package-summary.html)

## Getting started

### Step 1

Start by cloning the repository to your local machine. Open your terminal and run:

```bash
git clone https://gitlab.dx1.lseg.com/app/app-00687/mit-stp-platform/engineering-workshop-robocode.git
```

### Step 2

We have provided the _src/main/java/org/lseg/engineering/workshop/robocode/bots/YourTeamDisplayName_ to help you get started.

Please refactor this package and the files within to match your actual display name.


### Step 3

After programming your bot, zip your folder and upload to the Submission Form that you will be provided with.

## Testing your bot in the battleground

You can use the provided sample bots to test your bot.

### Step 1

Locate the file _robocode-tankroyale-gui-0.24.3.jar_ under the _gui_ directory

### Step 2 

Run the GUI jar with the following command executed from teh GUI directory

```bash
java -jar robocode-tankroyale-gui-0.24.3.jar
```

### Step 3 

Once the GUI is running, under _Config_ tab select _Bot Root Directories_ and add the location to _bots_ directory.

Inorder to test your bots against the sample bots additionally add the location to _sampleBots_ directory.

You can optionally tweak other available settings to test your Bot.
# robotcode
