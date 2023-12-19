# Fix-Notts-Moodle
Make Moodle Less 💩

Hacked together in an hour. It's a better idea to use something like [Stylus](https://github.com/openstyles/stylus) for the theme changes, but I already use uBlock.

## Install
Also, be sure to go to the moodle homepage -> Edit Mode in the top right -> add back Module Overview.
### Manually
- Go to uBlock settings
- Go to Filter Lists
- Scroll to bottom -> Import...
- Enter url: https://raw.githubusercontent.com/DoctorDinosaur/Fix-Notts-Moodle/main/Fix-Notts-Moodle.txt

### Automatically
Click the link on https://doctordinosaur.github.io/Fix-Notts-Moodle/

*Why github pages?*: uBlock has a [hardcoded](https://github.com/gorhill/uBlock/blob/d0dbc27c025b894bdc5cf32d501a1aaf36725b07/platform/firefox/manifest.json#L60) list of domains that can have a filter list url. Github markdown doesn't support protocol links

## Contributing
If you've found any horrible beige, please submit a pull request with a filter for it.
