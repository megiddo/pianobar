# pianobar

pianobar is a console client for the personalized web radio [Pandora](http://www.pandora.com).

### Features

* Play and manage (create, add more music, delete, rename, ...) your stations.
* Rate played songs and let pandora explain why they have been selected.
* Show upcoming songs/song history.
* Configure keybindings.
* last.fm scrobbling support (external application)
* Proxy support for listeners outside the USA.

### Source Code

The source code can be downloaded at [github.com](http://github.com/PromyLOPh/pianobar/)
or [6xq.net](http://6xq.net/projects/pianobar/).

#### Ubuntu 18.04 Build instructions
1. sudo apt-get install libgcrypt11-dev libjson-c-dev libgnutls28-dev ffmpeg libao-dev libjson-c-dev git-core libmad0-dev libfaac-dev libfaad-dev libavcodec-dev libavformat-dev libavfilter-dev
2. make clean
3. make
4. sudo make install
4.B. Alternately,sudo cp pianobar /usr/bin/pianobar 

### Download/Installation

There are community provided packages available for most Linux distributions (see your distribution’s package manager), Mac OS X ([MacPorts](http://trac.macports.org/browser/trunk/dports/audio/pianobar/Portfile) or [homebrew](http://brew.sh/)) and *BSD as well as a [native Windows port](https://github.com/thedmd/pianobar-windows).
