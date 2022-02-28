# exco

exco is a shell script to manage archives inspired by [patool](https://github.com/wummel/patool).

For now, it only supports the following formats: tar, bz2, gz, 7z, rar

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

To create an archive:
`exco c <archive-name> <file1> <file2> ... <fileN>`
