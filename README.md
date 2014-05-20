# Will Townsend's Liftoff Template

Inspired by [Ben Kreeger](https://github.com/kreeger/liftoff-templates), I'm also going to checkin my liftoff template. 

It differs ever so slightly, and is tailored to how I like my Xcode projects setup.

## Usage

First install liftoff [https://github.com/thoughtbot/liftoff](https://github.com/thoughtbot/liftoff)

### Installation for me
Clone into my project folder, then create a symlink

	cd ~/Dropbox/Projects
	git clone git@github.com:wtsnz/liftoff-templates.git ./.liftoff
	ln -s ./.liftoff/.liftoffrc .liftoffrc
	liftoff

### Installation for you

Depending on how you setup, you may want to clone into your home directory.

Clone into `~/.liftoff` and then create a symlink

	cd ~/
	git clone git@github.com:wtsnz/liftoff-templates.git ./.liftoff
	ln -s ./.liftoff/.liftoffrc .liftoffrc
	liftoff