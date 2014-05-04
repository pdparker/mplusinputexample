Mplus Snippets
====================

The Mplus plugin for [Sublime Text](https://github.com/bkeller2/Mplus) is amazing. So to is [Nettuts-Fetch](https://github.com/weslly/Nettuts-Fetch). So why not put the two together?! Here you will find:

1. Example Mplus input files taken from the [mplus user's guide](https://www.statmodel.com/ugexcerpts.shtml).
2. An example gitignore file for use with git.
3. A json file for use in Nettuts-Fetch (instructions below).


Getting Started
-----------------

Install both the mplus and nettuts-fetch packages using package control `shift+command+p` then start typing install. If you do not have package control go [here](https://sublime.wbond.net/installation).

After that you need to set up Nettuts-Fetch to get mplus snippets:

1. First `shift+command+p` then start typing fetch: manage
2. Copy and paste the information from [here](https://raw.githubusercontent.com/pdparker/mplusinputexample/master/fetch.json) and `command+s` save. *NOTE* If you use Nettuts-Fetch already just integrate the this info into your current fetch file.

Usage
--------
To fetch a file press `shift+command+p` and type fetch: file and select the input file you want. This will load the mplus snippet then type `shift+command+p` and begin typing ss: mplus input and select.

If you want to download all examples (not sure why you would want to), press `shift+command+p` and type fetch: package and select MplusexampleFolder. 

Participate
---------

I through this together on a Sunday morning as a proof of concept. I am hoping people will add useful example files rather then me adding all the mplus examples.
