Remember to read this before starting with the bot.
# Installing Twython
 First you need to paste the following command, one at a time.
`sudo apt-get update`

`sudo apt-get upgrade`

`sudo apt-get install python-setuptools`

`sudo easy_install pip`

`sudo pip install twython`

***


# Registering a Twitter app
Now you are going to make a twitter app in this url: [https://apps.twitter.com/app/new](https://apps.twitter.com/app/new)

(In application type, set read and write).

***
## And now you can start with the bot code!

***
# How to repeat the bot action chronologically
Type `sudo crontab -e`

To repeat every hour, paste this line:  `*/60 * * * * python /home/pi/MikelCalvo/TwitterTemp4Pi.py` 
Remember to change the directory to yours.

***
# I hope to have been of help
