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

```bash
# Ignore a file/folder:
dropbox-ignore add path/to/file/or/dir

# Stop ignoring a file/folder
dropbox-ignore rm path/to/file/or/dir
```

## License

MIT - &copy; 2020 Dana Woodman
