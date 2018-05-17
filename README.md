# Presentation skills demo slideshow #

## Summary ##

This is a short slideshow for Presentation skills workshop. The topic of the talk is warning about file encodings.

Every plain text is a text only if we know its encoding, otherwise it is just a binary blob. Source code is plain text and the interpreter must know the encoding. UTF-8 is now default, at least for Ruby and Python, but it has not been always like this.

There are some means how to specify the encoding of a source file. They have some caveats though. When we’re dealing with shebangs, there might even not be a solution.

## Credits ##

* [Ruby 1.9's Three Default Encodings](http://graysoftinc.com/character-encodings/ruby-19s-three-default-encodings)

## Notes ##

If you want to answer my [question on Stack Overflow](https://stackoverflow.com/questions/50331744/non-ascii-characters-in-python-2-shebang) on running a Python 2 script with a non-ASCII path in the shebang, go ahead!
