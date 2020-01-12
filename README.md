# About

Tiny Python 3 module for sending notifications on macOS.

# Installing

```sh
git clone
cd python-macos-notifications
python3 setup.py install
```

# Usage

```py
import macos_notifications import *
set_bundle_identifier('com.apple.SoftwareUpdate')
send_notification('Updates Available', subtitle='Reboot required', text='Reboot to install updates')
```
