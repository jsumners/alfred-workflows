# alfred-workflows

This repo is a collection of [Alfred](https://www.alfredapp.com/) workflows
that I have built to solve my own needs. These are provided as-is. These are
not going to be developed and supported like [alfred-emoji](https://github.com/jsumners/alfred-emoji)
is.

## Install

You can download the `.alfredworkflow` for the workflow(s) you are interested
in. Double click the downloaded file, and it will be opened for install in 
Alfred. Alternatively, the resources necessary for building the workflow are
provided in each workflow directory. You can, instead, download those and
use them to build the package yourself.

## Workflows

### ff-new-private

"Firefox New Private Window" is a workflow to solve a
[long standing bug](https://apple.stackexchange.com/a/343604/14745) in Firefox
on macOS: you cannot use macOS's system level keyboard shortcut mapping to
change the shortcut from `cmd+shift+p` to `cmd+shift+n`. This workflow will
intercept `cmd+shift+n` when Firefox is the frontmost app and trigger the
`cmd+shift+p` shortcut in the browser to open a new private window. It can be
a slow process, but at least it works.

### new-sticky

"New Sticky Note" is a workflow that looks for the trigger `new note`. Upon
executing the action, the Stickies.app will be triggered to create a new
sticky note. The Stickies.app does not provide a way to do this itself, and
when you use multiple desktops like I do, it is frustrating to have to open
the app, get your desktop shifted to wherever it thinks the main desktop is
for the Stickies.app instance, and then use `File > New` to create a new
note. It's bewildering why Apple doesn't include a "new note" item in the
Dock icon's context menu.

## License

[BlueOak 1.0.0](https://blueoakcouncil.org/license/1.0.0)