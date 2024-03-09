# xmake-plugins

## Usage

1. Add submodule to your repository

```bash
git submodule add https://github.com/MarcusMogg/xmake-plugins.git plugins
git submodule update --init --recursive
```

2. Add plugindir in your `xmake.lua`

```
add_plugindirs(path.join(os.projectdir(), "plugins"))
```

3. Check plugin by `xmake --help`, you will find plugins in detail

## Plugins

### build-and-run 

Quick build and run binary target

```bash
xmake br <target>
```