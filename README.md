# home-assistant-config-sleepcycle-test

tests if both works (not both custom components at same time) with alexa and google home. Change port if needed for alexa and google home, I've tested both with Sleep Cycle (if you want to test sleep cycle on the first component you need to add `type: sleep_cycle` but not on the second component, but when testing with alexa or google home you should NOT have a type on either)

put the folder "custom_components" in your configuration directory (same folder as configuration.yaml) . 

in configuration.yaml:

```yaml
emulated_hue_conf1:
  listen_port: 80
```

```yaml
emulated_hue_conf2: 
  listen_port: 80
```
