fakevm
======
POC kernel driver to make a normal Windows desktop show up as a VM.

usage of the controller:
========================
```
controller.py [options]

Options:
  -h, --help    show this help message and exit
  -w, --vmware  Switch fake VMware ON/OFF
  -x, --vbox    Switch fake VBox ON/OFF
  -o, --hook    Hook all functions
  -u, --unhook  Unhook all functions
```