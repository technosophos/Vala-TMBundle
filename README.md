# TextMate Support for the Vala Programming Language

This bundle provides [Vala](http://live.gnome.org/Vala) syntax highlighting, code completion, etc. for the 
TextMate text editor.

# Installing the TextMate Bundle

## Using Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/technosophos/Vala-TMBundle.git "Vala.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget https://github.com/technosophos/Vala-TMBundle/tarball/master
    tar zxf technosophos-Vala-TMBundle*.tar.gz
    rm technosophos-Vala-TMBundle*.tar.gz
    mv technosophos-Vala-TMBundle* "Vala.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

# Getting Vala on the Mac

The easiest way to get Vala on the Mac is to use Homebrew and run
the following:

    $ brew install vala

LibGee is strongly suggested:

    $ brew install libgee

This will install all you need to begin working with Vala.

# Credits

This is based on the original Vala TextMate bundle by Daniel Lucraft
[The original](http://danlucraft.com/blog/2008/12/vala-textmate-bundle/)

The Vala grammer is based upon the Java grammar that ships with TextMate.
