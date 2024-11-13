# assets_brick
Brick TG3040 SD base package

# SD base package - 20241105
First release
File 'tg3040_Brick_SD_base_package_20241105.zip' is the SD base package.
File 'Brick_Emus_compatibility_replacement' provides 2 styles for Emus UI.

The v1.0.5 config.json for Emus/Apps added new json-key "icontop".
Example:
# {
      "label":"MAME",
      "icontop":"../_theme/ic-mame.png",
      "icon":"",
      "background":"../_theme/bg-mame.png",
      "themecolor":"63C3F3",
      "launch":"launch.sh",
      "rompath":"../../Roms/MAME",
      "imgpath":"../../Imgs/MAME",
      "useswap":1,
      "shortname":1,
      "hidebios":1,
      "extlist":"zip"
# }

json-key 'icon' is old icon in firmware v1.0.0 ~ v1.0.4,
the icon will be stretched to full frame of grid.
json-key 'icontop' is newly added in firmware v1.0.5, 
the icon will be stretched to the center area of grid.

In v1.0.5, if 'icon' is also avalible, 
the 'icon' will be the same behavior as v1.0.4 and show 'icon' and 'icontop' in two layers.

TRIMUI Brick's firmware is starting from v1.0.5.

