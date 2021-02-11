# Ubuntu PHP Switcher
Ubuntu PHP switcher is a simple script to switch your Apache and CLI configs quickly between major versions of PHP. This supports any version of php installed onto the ubuntu system

If you support multiple products/projects that are built using either brand new or old legacy PHP functionality and you find it a pain to change config files continually this will make the whole process just one command.

## Caveats
**requires sudo**

For use with Ubuntu (not tested on other linux systems). For OSX php switching, I recommend [brew php switcher by phil cook](https://github.com/philcook/brew-php-switcher). Apparently this script could resolve [Ports to Linux? #62](https://github.com/philcook/brew-php-switcher/issues/62) in the `brew-php-switcher` issues.

This does not check the validity of the version given or if that version exists/is installed on the system.

## Installation

    $ curl -L https://raw.githubusercontent.com/chancegarcia/ubuntu-php-switcher/master/sphp > /usr/local/bin/sphp
    $ chmod +x /usr/local/bin/sphp
    
    
## Usage
Simply type `sphp` and the version you want to switch to
    
    $ sphp 7.1
    $ sphp 5.6

## License
MIT
