# Dogcraft Approved
> Note: This is not the "[Dogcraft](https://modrinth.com/modpack/dogcraft-official)" modpack containing canine-themed mods for your world. This is the modpack for the Minecraft server founded by ReNDoG (est. 2012, before the other pack!) Yes, it's been a [long running source of confusion](https://dogcraft.net/wiki/Frequently_Asked_Questions) ;-)

This is a Minecraft 26.3 modpack containing the [mods approved for use](https://dogcraft.net/rules) on the Dogcraft Server (with some exceptions). These mods can improve your playing experience by boosting performance and providing several quality-of-life features. While this pack is intended for Dogcraft players, it can be used on any server.

This is a community maintained pack and not an official distribution.

All mods in this pack have been approved by Ironboundred.

## Mods in this pack
This pack uses the Fabric mod loader.
* Iris Shaders
* Lambdynamiclights
* Lithium
* Zoomify
* Modmenu
* Raised
* Reese's Sodium Options
* Sodium
* Sodium extra
* Shulkerboxtooltip
* Continuity
* Controlify
* EntityModelFeatures
* EntityTextureFeatures
* CITFancy
* CullFewerLeaves
* DistantHorizons
* Fadeless
* Locator Heads
* NeoToolTipFix
* Not Enough Animations
* 3D Skin Layers
* BetterF3

## Not in this pack
* CIT Resewn - Has been replaced by CITFancy
* CullLessLeaves - Has been replaced by CullFewerLeaves
* Tooltipfix - Has been replaced by NeoToolTipFix
* No Fade - Has been replaced by Fadeless

* Phosphor - Not compatible & outdated
* Optifine/Optifabric - This pack opts to use Sodium, Lithium and Phosphor (and add-ons for those) in favour of Optifine (and packs containing Optifine are against license).

Several of the mods not/no longer in this pack are out of developement and have been replaced with new, actively maintained alternatives. Many of these alternatives are straight forks of the "original" and have the exact same functionality. See the list above for exact old vs new matches.

## Note on Distant Horizons "garbage collector" warning
If you are getting a "garbage collector" warning from distant horizons every time you open a world or join a server, you can either disable this warning in the distant horizons configuration via mod menu -> distant horizons, or you can change the garbage collector by adding "-XX:+UseZGC" to the JVM Arguments in your launcher.


# Building pack files
To build for [distribution on modrinth](https://modrinth.com/modpack/dogcraft), install [packwiz](https://github.com/packwiz/packwiz) and run the following in the root of the repository:
```shell
packwiz modrinth export
```
This will produce a `.mrpack` file that you can manually select to install from on MultiMC, PrismMC and other compatible launchers.

# Installation
You can install this pack in the MultiMC or PrismMC launchers through the Create Instance → Modrinth → Search: "Dogcraft Approved", then selecting the pack and installing it. A new instance will be created for you. For more details, and for other launchers, please consult Modrinth's documentation.