clnns
=====

clnns searches and downloads from newznab providers on the command line.

## dependencies:
* Python3
* [feedparser][feedparser]

## usage:
* clnns.py [--opts] [query]

## notes:
* currently *nix only - but compatible with windows too if you fix the config path.
* config is created on first run - requires editing.
* hosts format is: alias = http://www.url.com/;apikey;optional_desc

[feedparser]: https://pypi.python.org/pypi/feedparser/
