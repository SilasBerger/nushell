# Nu Shell

A personalized fork of the Nu shell. The original README can be found [here](README_origin.md).

![Example of nushell](images/nushell-autocomplete.gif "Example of nushell")

## Status
This project is currently up-to-date with [nushell/nushell](https://github.com/nushell/nushell) release `0.14.0`.

The `develop` branch will be updated to the latest release of `nushell/nushell` from time to time, to get the latest stable changes. This merge will also take place before every release of `SilasBerger/nushell`.

## Personalization Ideas
This section lists some ideas of how I might want to adapt Nu for my personal use cases. They are just ideas, and I have not researched whether all of them are possible / feasible, and whether some of them maybe already exist.

### Features and Behavior
- Emulate general behavior of zsh on all platforms (Unix-style paths, zsh commands, aliases, environment vars in rc file, etc.)
- Infix completion of paths (e.g. `cd rep/nu/src` -> `cd repos/nushell/src`)
- Infix matching for auto-completion
- Dynamic auto-completion with updateable and cyclable filter
- In-line calculator (e.g. type `(2 + 3) * 4`, get `20`)
- A notion of profiles, that would allow the user to change certain behaviors depending on their current use case (e.g. work, private, ...)

### Commands
- `jre`: manage JREs and default JRE on this system (similar to `rustup`, but for JREs such as oracle-jdk, openjdk, graalvm)
