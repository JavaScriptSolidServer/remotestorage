# remoteStorage Apps

Simple apps that sync via the [remoteStorage](https://remotestorage.io) protocol. Works with any remoteStorage server including [JSS](https://github.com/JavaScriptSolidServer/JavaScriptSolidServer).

## Apps

### [notes/](notes/)
Quick notes. Add, view, and delete plain-text notes synced to your storage.

### [bookmarks/](bookmarks/)
Save, tag, search, and organize your bookmarks. Compatible with the [webmarks](https://github.com/raucao/webmarks) data format.

### [grouptabs/](grouptabs/)
Split expenses in a group. Track who paid what, see balances, and get settlement suggestions.

### [editor/](editor/)
Minimal text editor with sidebar document list, auto-save, and keyboard-friendly workflow.

## Usage

Each app is a single `index.html` with no build step. Serve from any static host or open directly.

To connect to a JSS instance:

```
jss start --activitypub --idp
```

Then enter `user@hostname` in the remoteStorage widget.

## License

AGPL-3.0-only
