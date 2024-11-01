# WoWSims to `add` commands
 Extracts gear from a WoWSims character `.json` and creates a set of `.add` for gear, enchants, gems, and glyphs.

Uses data from WOTLK 335a Spell.dbc and AzerothCore `acore_world.item_template`.

![ingame](images/example_output_after_use_macro_additems.jpg)

## How to use


### Data
export `.json` data from a WoWSims character sim

![wowsim site](web/img/how_to_export.png)


### Run script

#### Option1: Use web `web`
  no dependencies needed

https://wowsims.github.io/wowsims-to-commands

#### Option2: Use `notebook`
requires dependencies:
1. Spell.dbc exported to SQL with stoneharry spell editor
2. python 3.11+
3. jupyter notebook, pandas, sqlalchemy


### ingame
paste commands

optional (`superdupermacro`) addon to paste in 1 macro https://felbite.com/addon/4135-superdupermacro/



## Development


optional (`superdupermacro`) addon to paste in 1 macro https://felbite.com/addon/4135-superdupermacro/


`web`
```
npm install -g http-server
http-server -c-1 
```