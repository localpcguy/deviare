# Deviare 

URL Shortener built using Node, Express, Mongo and Angular. Mainly as a learning experiment.

## Todo

* √ Check if short URL exists before assigning it

* Add basic authentication
	* √ Twitter
	* Store user in database
	* Username/Password
	* Associate shortened URLs with Twitter ID
	* Update account page to show user information, allow user to update info

* Setup click count for tracking

* Fix view "click" to delete to require confirmation

-----

## Change Log

**08/30/14 - Update to add basic authentication**

* Use Passport to enable Twitter login
* Set landing page to require login
* Add login and account page
* Update delete to use &times; rather than checkbox

**07/05/14 - Initial Build pushed live**

* basic url shortening working
* allows add/remove urls to shorten
* allows generating unique short URL if a custom short URL is not entered
* checks for existing short URL and returns error if exists

-----

### Why deviare? 

It is Italian for: ```to deflect, to divert, to lead astray, to ward off```

-----

License:
MIT - http://lpg.mit-license.org/