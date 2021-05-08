# Pipe Install

A list of projects that use a shell pipe and [cURL](https://curl.se/) or
[Wget](https://www.gnu.org/software/wget/) to install themselves

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
|[basher](https://github.com/basherpm/basher)|Shell Package Manager|Shell|
|[bpkg](http://www.bpkg.sh/)|Bash Package Manager|Shell|
|[Calibre](https://calibre-ebook.com/)|E-Book Management|Python|
|[Google Cloud SDK](https://cloud.google.com/)|Cloud Service SDK|?|
|[Homebrew](https://brew.sh/)|macOS Package Manager|Ruby|
|[Nix](https://nixos.org/)|Reproducible builds and deployments|Crystal|
|[nvm](https://github.com/nvm-sh/nvm)|Node Version Manager|Shell|
|[Mail-in-a-Box](https://mailinabox.email/)|Email Server|Python|
|[micro](https://micro-editor.github.io/)|Text Editor|Go|
|[Oh My Fish](https://github.com/oh-my-fish/oh-my-fish)|Fish Shell Framework|Shell|
|[Oh My ZSH](https://ohmyz.sh/)|Z-Shell Framework|Shell|
|[Owncast](https://owncast.online/)|Self Hosted Video Streaming|JavaScript|
|[Pi-hole](https://pi-hole.net/)|Network Blocker|Shell|
|[Rust](https://www.rust-lang.org/)|Program Language|Rust|
|[Site.js](https://sitejs.org/)|Personall web tool|JavaScript|
|[SpaceVim](https://spacevim.org/)|A community-driven vim distribution|Vim script|
|[SDKMAN](https://sdkman.io/)|SDK Manager|Shell|
|[tmpmail](https://github.com/sdushantha/tmpmail)|temporary email in terminal|Shell|
|[termv](https://github.com/Roshan-R/termv)|iptv player in terminal|Shell|
|[ugit](https://github.com/Bhupesh-V/ugit)|Git helper|Shell|
|[vimiv](https://github.com/thameera/vimv)|Batch-rename files Vim like|Shell|
|[ytfzf](https://github.com/pystardust/ytfzf)|Find and watch YouTube videos|Shell|
|[...](http://example.com/)|Your contribution|...|

## Commit

You know about more of this Projects? Pls. commit projects you know fit in this
list. You find all on the [issue list](https://github.com/KubikPixel/pipeinstall/issues),
feel free to commmit your knowledge.

## License

This project is under the MIT license, see for more th [LICENSE](https://github.com/KubikPixel/pipeinstall/blob/main/LICENSE)
file.

---

Curated by the community and [KubikPixel](https://thunix.net/~kubikpixel/)
