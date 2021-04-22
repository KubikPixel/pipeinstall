# Pipe Install

A list of projects there how use shell script pipe and [cURL](https://curl.se/)
or [Wget](https://www.gnu.org/software/wget/) to install it self.

> Initial toot: [Mastodon](https://chaos.social/@kubikpixel/106107773137340086)

## Why

It is generally considered bad and unsafe practice to download a shell script
from the Internet and then run it directly in the shell via pipe unchecked.
However, many projects now use this and it is even their official way to install
their software. There are more elegant ways to do this and one would be to
check a hash sum first and then run the script, but this is mostly bypassed by
a pipe. The installation scripts are usually not designed for this and
therefore often a dangerous practice.

This list should not be a pillory but a list for the overview of which projects
use this and where you should be careful as a user. This means to take a look
at the install scripts before you run them unchecked.

## Projects

|Project|Type of Software|Lang.|
|---|---|---|
|[Bashhub](https://www.bashhub.com/)|Interactive Shell|Python|
|[nvm](https://github.com/nvm-sh/nvm)|Node Version Manager|Shell|
|[Oh My ZSH](https://ohmyz.sh/)|Z-Shell Framework|Shell|
|[Owncast](https://owncast.online/)|Self Hosted Video Streaming|JavaScript|
|[Rust](https://www.rust-lang.org/)|Program Language|Rust|
|[...](http://example.com/)|Your contribution|...|

## Commit

You know about more of this Projects? Pls. commit projects you know fit in this
list. You find all on the [issue list](https://github.com/KubikPixel/pipeinstall/issues)
, feel free to commmit your knowledgee

## License

This project is under the MIT license, see for more th [LICENSE](https://github.com/KubikPixel/pipeinstall/blob/main/LICENSE)
file.
