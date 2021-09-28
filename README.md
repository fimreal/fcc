# fcc
Fedora CoreOS ignition config

## Usage:
```bash
fcct -ps ignition.yaml -o fcc.ign
coreos-installer install </dev/devicename> --ignition-url https://raw.githubusercontent.com/fimreal/fcc/main/fcc.ign
```
