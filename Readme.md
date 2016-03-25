# gpmdp

Get info about the current playing song in Google Play Music Desktop Player

I made this for use in [`neofetch`](https://github.com/dylanaraps/neofetch)

## Installation

### OS X

- Run `brew install iandrewt/tap/gpmdp-bash`

### Others

Clone the repo and run `make install`

## Uninstallation

Uninstall with your package manager, otherwise run `make uninstall`

## Usage

    usage: gpmdp <option>

    info            Print info about now playing song
    title           Print current song title
    artist          Print current song artist
    album           Print current song album
    album_art       Print current song album art URL
    rating          Print current song
    time_current    Print current song time in milliseconds
    time_total      Print total song time in milliseconds
    status          Print whether GPMDP is paused or playing
    help            Print this help message
 
