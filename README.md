# Local Dotfiles

**Note:** This repository is no longer used or maintained. My dotfiles are now
managed in [stevehanson/dotfiles](https://github.com/stevehanson/dotfiles).

The readme below is no longer relevant, though I'm preserving it for now.

---------

These are my local dotfile overrides which sit on top of thoughtbot's dotfiles. To use these, first install the base [thoughtbot
dotfiles](https://github.com/stevehanson/dotfiles). Then, clone this repo into
`~/dotfiles-local` and run `rcup`. 

## Installation

When setting up a new computer, the [thoughtbot
Laptop](https://github.com/thoughtbot/laptop) script should be used. Clone this
repo down and manually copy `laptop.local` to `~/.laptop.local` and then run the
Laptop script. Then set up the dotfiles, according to [the
instructions](https://github.com/stevehanson/dotfiles).

Future changes to `laptop.local` and any other files that don't start with a `.` in this repo are
automatically copied to the user directory when `rcup` is run.
