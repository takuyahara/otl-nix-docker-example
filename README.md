### Works on

```bash
$ sw_vers
ProductName:            macOS
ProductVersion:         14.3.1
BuildVersion:           23D60
$ uname -m
arm64
$ nix --version
nix (Nix) 2.20.3
```

### Commands

```bash
nix flake show --extra-experimental-features "nix-command flakes"
```

```bash
nix build ".#dockerImage" --extra-experimental-features "nix-command flakes"
```
