# dropbox-ignore

> Ignore files and folders in Dropbox based on [Dropbox's half-assed](https://help.dropbox.com/files-folders/restore-delete/ignored-files) ignore support

Only supports MacOS right now, but PRs are welcome to add Linux/Win support!

Maybe one day Dropbox will support a `.dropboxignore` file? One can only dream right? 🤔

## Install

```bash
curl https://raw.githubusercontent.com/danawoodman/dropbox-ignore/master/install.sh | bash
```

This will download the `dropbox-ignore` shell script to `/usr/local/bin`.

## Usage

Ignore all `node_modules` (or any other file/folder):

```bash
dropbox-ignore all node_modules
```

Other examples:

```bash
# Ignore a file/folder:
dropbox-ignore add path/to/file/or/dir

# Recursively ignore all files/folders matching the given name:
dropbox-ignore all node_modules .git

# Stop ignoring a file/folder
dropbox-ignore rm path/to/file/or/dir
```

## License

MIT - &copy; 2020 Dana Woodman
