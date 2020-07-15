# README #

This is a simple plugin for Spigot server 1.9.4 to work with Minecraft 1.9.4. The aim of the plugin is to prevent Endermen from picking up blocks

### Details ###

As stated this is a very simple plugin. Using the Spigot API (and bukkit) you create a listener to pickup entity change block events. Check it the entity is of type Endermen and then cancel the action.
At first I tried the on creature spawn event and then set the set pickup blocks attribute to false. This doesn't work however for Endermen hence my approach above.

I hope this will show how easy it is to create plugins. The Spigot API documentation is excellent. These are the resources I used:

https://hub.spigotmc.org/javadocs/spigot/

https://www.spigotmc.org/wiki/spigot/

https://www.spigotmc.org/wiki/spigot-plugin-development/

https://www.justdave.net/dave/2015/05/04/how-to-write-a-minecraftbukkit-plugin-for-spigot-1-8/