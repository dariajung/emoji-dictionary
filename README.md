emoji-dictionary
=============

Creates a dictionary of emoji name to where emoji is hosted on Zulip.

If no pickle file of the dictionary exists, the `emoji.txt` file is loaded and a new dictionary is created. It is then dumped in a new pickle file.
Otherwise, it simply loads in the pre-existing dictionary.

Being used for [LED-bot](https://github.com/marqsm/LED-bot).
