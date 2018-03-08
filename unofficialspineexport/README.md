# Unofficial Spine Export

Experimental Krita 4 Python Plugin to export into the Spine JSON format

## How to install

Copy ``unofficialspineexport.desktop`` and the ``unofficialspineexport`` folder into the ``pykrita`` directory inside the Krita Resource directory. You can find your Resource Directory within Krita via ``Settings > Manage Resources > Open Resource Folder``

Restart Krita and make sure the plugin is enabled, which means ``Settings > Configure Krita > Python Plugin manager > Unofficial Spine Export Plugin`` should be checked.

## How to use

This plugin is inspired by the official [Photoshop plugin](https://github.com/EsotericSoftware/spine-scripts/tree/master/photoshop).

It works nearly the same but not all the features are implemented. You can find the script under ``Tools > Scripts > Export to Spine``. Select a folder and all your images will be exported into it as well as ``spine.json``

Supported in Group Layers:
* (Bone)
* (Slot)
* (Merge)
* (Ignore)

Notes:
* Skins and subfolders are **not** supported
* No configuration options
* Images will be in ``png`` format
* Both () and [] can be used
* Invisible layers are ignored
* Be careful with filter layers. They will export as merged layer like they are shown in Krita. Consider organizing your scene with merge folders for better control.
