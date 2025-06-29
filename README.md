# file_dictd

## Setup

```sh
7z x <dicr>.7z.001
sudo ln -s "$(pwd)/<dict>/<dict>.dict.dz" /usr/share/dictd/<dict>.dict.dz
sudo ln -s "$(pwd)/<dict>/<dict>.index" /usr/share/dictd/<dict>.indexsudo systemctl restart dictd.service

