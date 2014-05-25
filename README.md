Investigation on the Katowice special economic zone
===================

This app is the result of a 3-day workshop organized by Medialab Katowice, on May 23-25 2014.

!(static/images/group_pict.jpg)
The group at work.

Licence : GNU General Public License V3


## Installation

### Dependances

	$ sudo apt-get install build-essential python-pip python-dev

and install virtualenv

	$ sudo pip install virtualenv

Please also install [CoffeeScript](http://coffeescript.org/)

### Setup a virtualenv and download dependances

	$ make install

### Run the server

	$ make run

### Locales

	$ make update_i18n
	$ make compile_i18n

### Compile the static files

	$ make freeze

### Launch

	$ make run
