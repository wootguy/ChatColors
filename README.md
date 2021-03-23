# ChatColors
Lets players choose a color for their name in chat. Only red, blue, green, and yellow are available.  

The plugin is automatically disabled on maps that use teams, or if another script or admin changes the classification of players to one of the colored team values (16-19).

# Installation
1. Add this to the top of default_plugins.txt
```
    "plugin"
    {
        "name" "ChatColors"
        "script" "ChatColors"
    }
```
It's important that this be the first plugin in the list. Otherwise, chat names will not be colored when another plugin handles a chat command. Note that reloading the plugin with `as_reloadplugin chatcolors`, it will be sent to the bottom of the list. So, always use `as_reloadplugins` when editing this plugin.
