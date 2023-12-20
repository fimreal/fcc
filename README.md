# fcc
Fedora CoreOS ignition config

## Usage:
```bash
fcct -ps ignition.yaml -o fcc.ign
# brew install butane
# butane -ps ignition.yaml -o fcc.ign
sudo coreos-installer install </dev/devicename> --ignition-url https://raw.githubusercontent.com/fimreal/fcc/main/fcc.ign
# sudo coreos-installer install </dev/devicename> --ignition-url https://cfdown.2fw.top/https://raw.githubusercontent.com/fimreal/fcc/main/fcc.ign
```

## Online fcct tool
You can use fcct, the Fedora CoreOS Configuration Transpiler in order to create Ignition JSON files for installing CoreOS from YAML.

Instead of installing fcct, you can use

[**Click here to go to FCCT Online**](https://fcct.epurs.com/)

