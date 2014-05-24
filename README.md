A history of the KSSE
===================

This app is the result of a 3-day workshop at Medialab Katowice, on May 23-25 2014.

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
