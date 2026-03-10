# remoteStorage Apps

Simple apps that sync via the [remoteStorage](https://remotestorage.io) protocol. Works with any remoteStorage server including [JSS](https://github.com/JavaScriptSolidServer/JavaScriptSolidServer).

## Apps

### [notes/](notes/)
Quick notes. Add, view, and delete plain-text notes synced to your storage.

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
