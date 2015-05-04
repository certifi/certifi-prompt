# certifi-prompt

A very basic application that I use to tell me if I need to update certifi.

## Requirements

Requires the Python requests library and the terminal-notifier command line
tool. Only functions on OS X.

## Installation

First install terminal-notifier:
`brew install terminal-notifier && brew linkapps terminal-notifier`. Then,
clone this repository and link `certifi-prompt` into
`/usr/local/bin/certifi-prompt`. Finally, copy the `plist` file in this
repository into `~/Library/LaunchAgents/` and run
`launchctl load ~/Library/LaunchAgents/uk.co.lukasa.certifi-prompt.plist`.

## License

This software is available under the MIT license.
