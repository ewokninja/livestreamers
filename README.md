# livestreamers
A Python script that uses Twitch.tv API to check if a user's followed channels are live.

## Installation
Clone the repository.

Create a file in the repo's directory called `.env` - it should contain the line:
```export TWITCH_OAUTH="OAuth YOUR_TWITCH_OAUTH_KEY_HERE"```

Alter the line:
```load_dotenv(dotenv_path="/home/jt/bitbucket/livestreamers/.env")```
So that it contains the absolute path to your .env file.

## Dependencies
This script uses the 'requests' package and the 'dotenv' package. 
They can be installed with ```pip -r install requirements.txt```

## Usage
Then simply run the ```live.py``` script. Example output:
![output](https://thumbs.gfycat.com/WatchfulTepidAdamsstaghornedbeetle-size_restricted.gif)
