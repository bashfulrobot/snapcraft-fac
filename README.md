# fac

This repo is the snap dev repo for the [fac](https://github.com/mkchoi212/fac) program.

## Status

🚧 This is currently a "work in progress".

Currently waiting on:

* requesting access to the `personal-files` interface in the snapstore

## Interfaces

This snap currently requires you to manually connect the interfaces.

``` shell
snap connect fac:dot-fac-yml :personal-files
snap connect fac:dot-gitconfig :personal-files
```

## Build Notes

* For some reason snapcraft v4 requires dependencies to be staged with the Go plugin, whereas v3 did not.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/fac)
