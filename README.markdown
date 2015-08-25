file.io utility
==

Use [file.io](https://www.file.io) - an ephemeral file sharing service - from your terminal!

It will upload your file and copy the generated link to your clipboard (it uses `pbcopy`).

Usage
==

Give it execution permission:

```
chmod +x fileio
```

As this is just a shell script you can add it to your path to have global access.

For detailed instructions just type `./fileio --help`.

Basically the only optional parameter is the expiry date, e.g. `./fileio -e 1m somefile.png`

Example:
==

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
