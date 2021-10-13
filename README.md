# fcc
Fedora CoreOS ignition config

## Usage:
```bash
fcct -ps ignition.yaml -o fcc.ign
coreos-installer install </dev/devicename> --ignition-url https://raw.githubusercontent.com/fimreal/fcc/current/fcc.ign
```

## 
You can use fcct, the Fedora CoreOS Configuration Transpiler in order to create Ignition JSON files for installing CoreOS from YAML.

Instead of installing fcct, you can use

[**Click here to go to TechOverflow FCCT Online**](https://fcct.techoverflow.net/)

Thanks to techoverflow.net
