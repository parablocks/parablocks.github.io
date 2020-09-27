# <img src="https://github.com/parablocks/parablocks.github.io/raw/master/logo_close.png" width=25 alt="logo"> Parablocks
Parablocks is an alternative, highly parallelized Minecraft server. It is written in C# and uses heavy multithreading to take advantage of modern many-thread CPUs.

## Features
 * Highly threaded pipeline
   * Uses different thread(pool)s for each significant task.
   * For example, you can assign x threads to handling Player communications, and then assign y tasks to world generation.
 * Fully custom and open-source code
   * Doesn't depend on Mojang's server, like Bukkit/Spigot/Paper does.
   * This also, sadly, breaks all plugins and server-side mods ever made.

## The state of Parablocks
Parablocks is a very new project. The server currently does not have any releases, and has very few features implemented. This website is a draft/concept too.

Check back later for more updates.
