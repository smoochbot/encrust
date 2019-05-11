# «encrust»

encrust is a command line tool that converts iTerm2 color files (`*.itermcolors`) to color files usable by Dwarf Fortress.

## Installation

encrust requires Ruby. If you have a current version of Ruby installed, it's as simple as:

    $ gem install encrust

Otherwise, head on over to [Ruby's website](https://www.ruby-lang.org/en/downloads/) and find a version that works for your machine.

## Usage

Just point encrust at the files you'd like converted:

    $ encrust gruvbox-dark-soft.itermcolors

It handles multiple files just fine:

    $ encrust elflord.itermcolors Earthsong.itermcolors

Your Dwarf Fortress color files will be generated in the directory where you ran the command, and encrust will tell you where Dwarf Fortress expects its active color file to be.

If you want to try out your new color schemes without having to wait for your fortresses to open and close, try uploading the generated files to the [Dwarf Fortress Color Generator](https://manmademagic.github.io/DFColorGen/). DFColorGen also works great for small adjustments to your color schemes.

## Why iTerm?

I chose `itermcolors` as my input format primarily because it supports 24-bit color and is easy to read.

iTerm2 is also pretty popular, and dozens if not hundreds of color schemes for it can be easily found online.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/smoochbot/encrust. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Code of Conduct

Everyone interacting in the Encrust project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/smoochbot/encrust/blob/master/CODE_OF_CONDUCT.md).
