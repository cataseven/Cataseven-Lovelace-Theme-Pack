#  Cataseven Lovelace Themes for Home Assistant



## Build your own

You can build your own theme by using the variables.

`em` unit is relative to container height.

```
     
```

## Installation

Add the following code to your configuration.yaml file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Open HACS
2. Go to "Frontend" section
3. Click three dots on the top right of the page and selecekt "Custom Repositories"
4. add https://github.com/cataseven/Cataseven-Theme-Pack/find/main as a custom theme repository
5. Click download on the opened page



