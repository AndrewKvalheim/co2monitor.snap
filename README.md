# co2monitor.snap

Packaging of Lars Pfannenschmidt's [CO₂ monitor] for [Ubuntu Core].

## Installation

Install the package:

```bash
sudo snap install co2monitor # Pending publishing
```

Optionally configure the USB device or HTTP server listening address:

```bash
sudo snap set co2monitor device='/dev/hidraw0' \
                         listen-address=':8080'
```


  [CO₂ monitor]: https://github.com/larsp/co2monitor
  [Ubuntu Core]: https://ubuntu.com/core
