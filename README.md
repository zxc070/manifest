To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/zxc070/manifest.git -b pie-caf

```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

