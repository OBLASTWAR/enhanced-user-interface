# Enhanced User Interface

Fork of bc1's Enhanced User Interface (EUI) v1.28g, with crash and bug fixes for multiplayer.

`UI_bc1/` is the DLC folder exactly as it installs to
`Assets/DLC/UI_bc1`. The first commit is the untouched original; every change
after it is its own commit, so `git diff original` shows everything this
fork changes.

## Releases

Tags are `<upstream version>-oblastN`. A release zip holds the `UI_bc1/`
folder:

    git archive --format=zip -o UI_bc1.zip <tag> UI_bc1

## Fixes

See the commit log after the `original` tag.

Original EUI by bc1. Files are stored byte-for-byte (CRLF, Latin-1), see
`.gitattributes`.
