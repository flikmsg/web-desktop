# web-releases
Release tracker for Flik.

## Release Channels

* Master - The regular release cycle
* Beta - Some newer features currently in testing. May be more unstable, but supported.
* Canary - Unstable testing features. Not supported.
* Dev - Dev branch. Bleeding edge features, but certainly not supported and very unstable.

## Which channel should I use?

If you're not sure, use master. Don't change anything.

## How do I query this?

Send a curl to the following link:
```
curl https://api.flik.im/updates/latest/:branch
```

This will give you the hash of the latest upload. If this doesn't match the one you have installed, there's a version change.

Download the new .tar.gz:
```
wget https://api.flik.im/updates/:branch/download.tar.gz
```

Downloading old versions is unsupported, but can be done by manually going to the [releases page](/releases).
