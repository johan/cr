# CR

`cr` is a tool to help you work on the Chromium browser sources

## What can it do for me?

- Download fresh Chromium sources (`cr clone`)
- Build Chromium browser (`cr build`)
- Update Chromium sources (`cr update`)
- Install Chromium depot_tools and dependencies (`cr clone` checks if you have them and installs them if not)
- Download separate WebKit sources (`cr webkit` replaces your `third_party/WebKit` with actual WebKit sources)
- Update separate WebKit sources automatically (`cr update` detects separate WebKits and updates them as well)

## What not?

- Run Chromium (soon)
- Help upload Chromium patches (soon)
- Help upload WebKit patches (soon)

## Usage

    usage: cr <command> [<args>]

    The cr commands are:

       clone     Clone the Chromium sources into a new repository
       build     Build the Chromium browser from sources
       webkit    Clone separate WebKit sources into your repository
       update    Update a Chromium repository and its dependencies
       help      Display this helpful message

## Install or Update

    sudo wget -O /usr/local/bin/cr "https://raw.github.com/jankeromnes/cr/master/cr" && sudo chmod +x /usr/local/bin/cr

## Uninstall

    sudo rm -rf /usr/local/bin/cr

