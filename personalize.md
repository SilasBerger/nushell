# Personalize
This file lists some ideas of how I could adapt NuShell for my personal use cases. They are just ideas, and I have not researched whether all of them are possible / feasible, and whether some of them maybe already exist.

## Features and Behavior
- Emulate general behavior of zsh on all platforms (Unix-style paths, zsh commands, aliases, environment vars in rc file, etc.)
- Infix completion of paths (e.g. `cd rep/nu/src` -> `cd repos/nushell/src`)
- Infix matching for auto-completion
- Dynamic auto-completion with updateable and cyclable filter
- In-line calculator (e.g. type `(2 + 3) * 4`, get `20`)
- A notion of profiles, that would allow the user to change certain behaviors depending on their current use case (e.g. work, private, ...)

## Commands
- `jre`: manage JREs and default JRE on this system (similar to `rustup`, but for JREs such as oracle-jdk, openjdk, graalvm)
