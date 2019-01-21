# home-assistant-sleepcycle_custom_component

homeassitant emulated_hue custom component for Sleep Cycle

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

