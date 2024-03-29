# ![surf logo](surf.png "surf logo")
surf is a simple Web browser based on WebKit/GTK+.

## Requirements
In order to build surf you need GTK+ and Webkit/GTK+ header files.

In order to use the functionality of the url-bar, also install [dmenu](http://gitlab.com/jaenek/dmenu).

## Installation
Edit config.mk to match your local setup (surf is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install surf (if
necessary as root):
```
make clean install
```

## Running surf
run
```
surf <URI>
```

See the manpage for further options.

## Running surf in tabbed
For running surf in [tabbed](http://tools.suckless.org/tabbed) there is a script included in the distribution,
which is run like this:
```
surf-open.sh <URI>
```

Further invocations of the script will run surf with the specified URI in this
instance of tabbed.
