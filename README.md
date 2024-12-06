> NOTE: this version is archived and will no longer be updated, please use https://github.com/floooh/dcimgui

fips-imgui
=========

fipsified imgui (https://github.com/ocornut/imgui)

fips build system: https://github.com/floooh/fips

## How to integrate:

Add the dependency to your fips.yml file:

```yaml
imports:
    fips-imgui:
        git: https://github.com/fips-libs/fips-imgui
```

Use imgui as dependency in your targets:

```cmake
fips_begin_*(...)
    ...
    fips_deps(imgui)
fips_end_*(...)
```
