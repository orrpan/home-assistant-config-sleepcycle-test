# home-assistant-config-sleepcycle-test

tests if both works (not both custom components at same time) with alexa and google home, first need a type, second does not. change port if needed for alexa and google home

put the folder "custom_components" in your configuration directory (same folder as configuration.yaml) . 

in configuration.yaml:

```yaml
emulated_hue_conf1: #type needed
  type: sleep_cycle
  listen_port: 80
```

```yaml
emulated_hue_conf2: #no type!
  listen_port: 80
```