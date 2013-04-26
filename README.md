chainbreaker
============

This tool is developed for forensic examiner

Chain Breaker is able to extract user credential in a Keychain file with Master Key
Master Key candidates can be extracted from volafox keychaindump module.

##How to use:

If you have only keychain file as following

    # python chainbreaker.py -i [keychain file] -p [user password]

If you have memory image, you can extract master key candidates using volafox project
The volafox, memory forensic toolit for Mac OS X has been written in Python as a cross platform open source project.

[volafox project - google code](http://code.google.com/volafox/)

    # python volafox.py -i [memory image] -o keychaindump
    ....
    ....
    # python chainbreaker.py -i [keychain file] -k [master key]


## Example


## Contacts

chainbreaker was written by [n0fate](http://twitter.com/n0fate)

email : n0fate@n0fate.com

## License
[GNU GPL v2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
