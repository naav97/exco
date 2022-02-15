# exco

exco is a shell script to manage archives inspired by [patool](https://github.com/wummel/patool).

For now, it only supports the following formats: tar

## Installation

1. Clone the git repo: `git clone https://github.com/naav97/exco.git`
2. Make sure you are on the repo directory: `cd exco/`
3. Run the following comand: `sudo cp exco /usr/local/bin && chmod +x /usr/local/bin/exco`

Done! exco is now installed in your computer.

## Usage

To extract archives:
`exco e <file1> <file2> ... <fileN>`

To create an archive:
`exco c <archive-name> <file1> <file2> ... <fileN>`
