# homeassistant-local-purpleair
YAML file to configure a local PurpleAir sensor.

This file is designed to be a package. I keep mine in a packages directory that is
referenced from the main configuration.yaml like this:

```
homeassistant:
  packages: !include_dir_named packages
```
