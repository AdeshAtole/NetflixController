Control Netflix in your browser with a gamepad or controller using this Chrome extension.

## TODO
* Dynamically determine whether a page has a billboard or not
* Firefox/Edge support (convert manifests, fullscreen action)
* Continue mapping navigation controls to additional page elements (such as other jawbone options)
* Support non-standard gamepad mappings / offer way to configure mappings
* Configure right joystick to control a virtual mouse
* Timeout page readiness checks (useful in case of no internet connection)
* Improve plugin design to be extendable for other websites
* Dual action hints for action pairs like volume up/down
* CSS classes for content outlines
* Fix visual bug that occurs on some billboard MyList buttons
* Scale bottom bar elements according to page size
* Hide jump 10s actions when unavaiable (player class `preplay`?)
* Identify interactive videos and only apply related settings/observers if needed
* Fix bug where search page handler does not finish loading until keyboard is closed when only one character has been entered into the search bar
* Organize page handler logic such that navigatables have clean access to the enclosing page handler
* Add additional styling to jawbone buttons to better indicate the selected option
* Use mutation observers or parse CSS transitions instead of using static timing in slider timeouts
* Fix bug where jawbone changes due to removing from my list the title with an open jawbone
* Show video controls when in fullscreen mode
* Add remaining jawbone pane types

## Libraries and Materials Used
* [pseudo:styler](https://github.com/TSedlar/pseudo-styler) - A module that allows for forcing an element to be styled with a pseudo-class.
* [Gamepads.js](https://github.com/FThompson/Gamepads.js) - A module for tracking Gamepads and events pertaining to their usage.
* [Chrome Live Storage](https://github.com/FThompson/ChromeLiveStorage) - A module that provides `chrome.storage` data as native JavaScript objects that automatically synchronize between all extension views (background, content scripts, popups, options, etc.).
* Project icons courtesy of https://material.io/icons/ and https://iconfu.com.
* Many thanks to [Tyler Sedlar](https://github.com/TSedlar) for creating pseudo:styler and for letting me bounce ideas off of him throughout development of this project.