# fm2repo

## Usage

Add following block to `/etc/pacman.conf`:

```
[fm2repo]
SigLevel = Optional TrustedOnly
Server = https://bgi-sz.github.io/$repo/$arch
```

### Local
`rsync -av x86_64 rsync://galaxy@10.225.10.113:5973/repo/`

```
[fm2repo]
SigLevel = Optional TrustedOnly
Server = http://10.225.10.113:5980/$arch
```

