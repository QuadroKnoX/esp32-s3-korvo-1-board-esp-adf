Fix for esphome based on this PR: https://github.com/espressif/esp-adf/pull/1113

Use it like this:

```yaml
esp32:
  ...
  framework:
    ...
    components:
      - name: esp32s3korvo1-board
        source: github://QuadroKnoX/esp32-s3-korvo-1-board-esp-adf@2.6
        refresh: 0s
```
