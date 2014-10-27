#integrity-checker

Just a simple utility to recursively check directories of files using md5sum.

Useful to spot corrupted files and whatsoever. 

Useful when working with big data and/or proprietary software which screw up everything without saying what happened.


Inspired by the Steam `Verify integrity of game cache` functionality.


    Usage: integrity save <directory> <output>
    Use integrity save to save the state of a <directory> in a <output> file

    Usage: integrity check <directory> <input>
    Use integrity check to compare the state of a <directory> with a <output> file previously generated with integrity

##Licence
MIT
