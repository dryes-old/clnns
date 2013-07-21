clnns
=====

clnns searches newznab providers on the command line.

* configurable for multiple newznab hosts.
* 'send to SABnzbd+' functionality.
* pronounced 'coolness'.

## dependencies:
* Python3
* [feedparser][feedparser]

## usage:
* clnns.py [--opts] [query]

## notes:
* currently *nix only - but compatible with Windows too if you fix the config path.
* config is created on first run - requires editing.
* first host is searched by default; specify other with: -p alias
* hosts format is: alias = http://www.url.com/;apikey;optional_desc
* if [sabnzbd] section is uncommented and configured the default action becomes sendtosab - use -d switch to force nzb download.

[feedparser]: https://pypi.python.org/pypi/feedparser/
