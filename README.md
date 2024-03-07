# exco

exco is a shell script to manage archives inspired by [patool](https://github.com/wummel/patool).

It supports the following formats: tar, tgz, tbz2, bz2, gz, 7z, rar, zip

## Installation

1. Clone the git repo: `git clone https://github.com/naav97/exco.git`
2. Make sure you are on the repo directory: `cd exco/`
3. Run the following comand: `sudo cp exco /usr/local/bin`

Done! exco is now installed in your computer.

## Updating

1. Make sure you are on the repo directory
2. Run the update.sh file `./update.sh`

## Usage

To extract archives:

`exco e <file1> <file2> ... <fileN>`

You can also use `x` and `extract` instead of e

To create an archive:

`exco c <archive-name> <file1> <file2> ... <fileN>`

You can also use `create` instead of c

To list the contents of an archive:

`exco l <archive-name>`

You can also use `list` instead of l
