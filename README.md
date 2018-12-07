# home-assistant-config-sleepcycle-test

homeassitant emulated_hue custom component for Sleep Cycle, tested with 0.83.3

in configuration.yaml:

```yaml
emulated_hue:
  listen_port: 80
  host_ip: 192.168.1.5
  expose_by_default: false
  entities:
    switch.kitchen:
      hidden: false
```

