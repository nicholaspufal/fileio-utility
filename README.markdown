file.io utility
==

Use [file.io](https://www.file.io) - an ephemeral file sharing service - from your terminal!

It will upload your file and copy the generated link to your clipboard (depends on `pbcopy` at the moment).

Install
==

If you have `homebrew` installed you can simply do:

```
brew tap nicholaspufal/tap
brew install fileio
```

...and you are ready to use `fileio` from the terminal.

If you prefer to configure it manually, you will need to give the script execution permission:

```
chmod +x fileio
```

And you will need to add this folder to your PATH or move it to a place that is already part of it, so you can access it globally.

Usage
==

For detailed instructions just type `./fileio --help`.

Basically the only optional parameter is the expiry date, e.g. `./fileio -e 1m somefile.png`

### Example

**Input:**

```
  ./fileio somefile.png
```

**Output:**

```
Uploading to file.io...
Link: https://file.io/abcdef -> already available in your clipboard!
It will expire in 14 days
```
