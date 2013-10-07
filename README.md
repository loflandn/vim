My vim Configuration
===

My full vim configuration, including my vimrc file, plugins, etc. Essentially, it's everything you need to drop into place on a new system and have your vim environment exactly as you like it.

This is a fork of Daniel Miessler's vim config.

## Usage

Simply go to a new system, git clone this repo, and then symlink your ~/.vimrc file to .vim/vimrc. Pathogen will be completely set up already and you sould be good to go.

## Updating plugins

Currently, you can just go to each individual plugin under ~/.vim/bundle and run <code>git pull</code>. I'm working on potentially using submodules to make this more automated.

## Feedback

If you have any ideas for improvements to my vimrc or for handling the portability and upgradeability of this config, please shoot the original author a message at daniel@danielmiessler.com. 
