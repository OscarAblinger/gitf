# gitf

A wrapper around git with a few useful extra command and seemless
[fzf](https://github.com/junegunn/fzf) integration.

## Installation

1. Install [fzf](https://github.com/junegunn/fzf) however you choose.
   The executable simply has to be found through your path variable.
2. Drop the contents of this git repository in any folder in your path.
   e.g. via `git clone git@github.com:OscarAblinger/gitf.git <any folder in your path>/gitf`

## Usage

> To be documented

## Extend gitf

The actual `gitf` shell script essentially only tries to load scripts from the `scripts` folder.
So if you want to add another command, just drop the shell script in that folder.
All shell scripts will be executed using `bash`.

# How is it different to [forgit](https://github.com/wfxr/forgit) or [git-fuzzy](https://github.com/bigH/git-fuzzy)?

Both forgit and git-fuzzy are full graphical interfaces.
There's nothing wrong with that, but I wanted a more light-weight version that doesn't change
anything fundamental, but rather just enhances the normal git experience.
Your default git editor will for instance still open and allow you to edit commits, rebase todos
etc..

This makes gitf better for quick commands and usage in conjunction with other programs (e.g. through
piping) and keeping the original CLI feeling.

In the end it's a personal preference and I encourage you to check out the other two projects.
