# clipd

Ruby based, minimal dmenu based clipboard managed -- based on http://mpov.timmorgan.org/super-simple-clipboard-history-for-linux/

## Setup

* Clone the repo to a local directory
* Customize dmenu presentation by modifying `DMENU_COMMAND`
* Run clip into background in your `xinitrc`, like this:
```
~/Source/clipd/clipd &
```
* Bind `clipd menu` to a specific key combination using `xbindkeys` or alias the invoication to a shorter command so you can call it from `dmenu`.
