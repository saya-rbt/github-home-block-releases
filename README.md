# GitHub Home Block Releases
## A simple Tampermonkey script to hide the releases on GitHub's homepage

GitHub decided to show every repo you've starred's releases on homepage, cluttering it a lot and **without any option to disable it.** It's not like the option to enable it didn't exist either, it was an opt-in functionality in the Watch menu.

So I think this is dumb. I looked a bit online, and I'm [apparently not the only one](https://github.community/t/why-i-am-seeing-releases-from-repos-that-i-didnt-subscribed/184239).

So I decided take matters into my own hands and make this script to hide all the `divs` about releases myself.

## Usage

1. Install Tampermonkey
1. Copy the source of [no-releases-tamperscript.js](./no-releases-tamperscript.js)
1. Open Tampermonkey in your browser and click the Add Script tab (icon with a plus symbol)
1. Paste the source into the script window and hit save

## License

MIT
