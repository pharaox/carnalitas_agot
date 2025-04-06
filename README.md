# Carnalitas AGOT Compatibility

This is a [Carnalitas](https://www.loverslab.com/files/file/14207-carnalitas-unified-sex-mod-framework-for-ck3/) compatibility patch for [A Game of Thrones](https://steamcommunity.com/sharedfiles/filedetails/?id=2962333032). It reconciles changes to the character window and other game files made by these two mods. It also adds AGOT lore-based slavery doctrines, similar to the *Carnalitas Historical Slavery Doctrines* mod. It can also be used with the [Legacy of Valyria](https://steamcommunity.com/sharedfiles/filedetails/?id=3403938445) AGOT submod.

The latest version is compatible with CK3 1.15.x, Carnalitas 2.9, AGOT 0.4.0+. **It is currently not compatible with LoV since there LoV is not yet compatible with AGOT 0.4.0.**

Load order:

* A Game of Thrones
* Carnalitas
* Carnalitas AGOT Compatibility (this mod)
* (other mods based on Carnalitas)

If you use the slavery system, it is strongly recommended to also use the [Carnalitas Slavery Reimagined](https://www.loverslab.com/files/file/25565-carnalitas-slavery-reimagined/) mod that also has a CSR AGOT compatibility patch available as a separate download. The load order in this case should be:

* A Game of Thrones
* Carnalitas
* Carnalitas AGOT Compatibility (this mod)
* Carnalitas Slavery Reimagined
* CSR AGOT Compatibility
* Legacy of Valyria (optional)

## Compatibility Fixes

### Character Window

All changes to the character window made by Carnalitas and AGOT have been reconciled, so that all additional interface elements introduced by both are present. Additional AGOT interface elements such as paramours, squires, and knights, as well as Carnalitas changes such as slaves at the bottom of the *Relations* tab, are all properly shown.

### Interactions and Events

All changes to other vanilla files made by Carnalitas and AGOT have been reconciled. The AGOT files have been taken as base, and Carnalitas changes have been applied on them. The effects are numerous and so are not listed here. One notable effect is that references to vanilla religions, faiths, culture, and titles present in the original Carnalitas no longer fill the logs with error messages.

## Integration with AGOT Slavery System

Starting with version 0.2.0, AGOT introduces its own slavery system. This system is still pretty rudimentary and mostly does not conflict with Carnalitas. This mod does not integrate of change any of its features. A better integration is available in the [CSR AGOT Compatibility](https://www.loverslab.com/files/file/25565-carnalitas-slavery-reimagined/) mod.

## Lore-based Slavery Doctrines

This mod introduces a *A Song of Ice and Fire Lore* game rules setting for Carnalitas slavery doctrines, and makes it the default. If this setting is active, all faiths have accurate doctrines for *Righteous Faith Slavery* and *Hostile Faith Slavery* based on A Song of Ice and Fire lore research. The effect is similar to using the *Carnalitas Historical Slavery Doctrines* mod (available as a separate [Carnalitas](https://www.loverslab.com/files/file/14207-carnalitas-unified-sex-mod-framework-for-ck3/) download) in vanilla.

### Overview

According to [Slavery](https://awoiaf.westeros.org/index.php/Slavery) and [R'hllor](https://awoiaf.westeros.org/index.php/R%27hllor) Wiki pages:

* Both the *Old Gods* and the *Faith of the Seven* hold slavery to be an abomination. I take this to mean that slavery should be criminal in *Faith of the Seven* and *Old Gods* faiths south of the Wall.
* The Ironborn (who are *Drowned God* adherents) keep thralls and salt wives, but don't regard them as slaves. I take this to mean that slavery should be either shunned or accepted in *Drowned God* faiths.
* Some of the wildling clans north of the Wall also practice thralldom. I take this to mean that slavery should be either shunned or accepted in *Old Gods* faiths north of the Wall.
* Slavery was widespread in Old Valyria and still is in the Free Cities, except for Braavos. I take this to mean that slavery should be accepted in *Valyrian* faiths.
* Servants of the Temple of the Lord of Light in Volantis are slaves who were bought as children and trained. I take this to mean that slavery should be accepted in *Dawnbringer* faiths.

There are no explicit mentions of slavery for *Rhyonish* faiths. On one hand they are of Eastern origin, on the other their adherents have historically suffered and fled from enslavement. I take this to mean that slavery should be shunned in *Rhyonish* faiths.

### AGOT Slavery Doctrines and Mechanics

The AGOT mod has its own slavery mechanics including slavery realm laws, slave buildings, and slave populations. The Free Cities of Lys, Myr, Pentos, and Tyrosh all start with realm laws allowing slavery. I regard this as a confirmation that that slavery should be accepted in religions that are widespread or originating from this part of Essos, which includes all *Valyrian* and *Dawnbringer* faiths.

In version 0.4.0, AGOT overhauled their faiths and introduced their own *Slavery* doctrines: *Criminal*, *Indentured Servitude*, *Thralls*, and *Accepted*. Currently they only influence if a ruler is allowed to pass the *Slavery Allowed* realm law.  This mod mostly maps the AGOT doctrines to the Carnalitas slavery doctrines, with some minor exceptions based on my own research. This mapping is very close to the doctrines seeded by this mod before version 0.4.0.

Note that the AGOT *Slavery* doctrines are currently missing for *Old Gods* and *The Others* faiths. This will likely be fixed in a future AGOT version. The Carnalitas doctrines are still seeded appropriately for these faiths by this mod, based on the research cited above.

### Righteous Faith Slavery

The mapping of AGOT *Slavery* doctrines to Carnalitas *Righteous Faith Slavery* doctrines is as follows:

* *Criminal*: *Criminal*
* *Indentured Servitude*: *Shunned*
* *Thralls*: *Shunned*
* *Accepted*: *Accepted*

### Hostile Faith Slavery

The mapping of AGOT *Slavery* doctrines to Carnalitas *Hostile Faith Slavery* doctrines is as follows:

* *Criminal*: *Criminal* (or *Shunned*, see below)
* *Indentured Servitude*: *Shunned*
* *Thralls*: *Accepted*
* *Accepted*: *Accepted*

Note that some religions or faiths have *Shunned* for this doctrine even though the AGOT doctrine is *Criminal*. Notably, these are *Lord of Light*, *Free Cities*, and *Valyrian*, faiths that are exceptions from the otherwise *Accepted* pattern (except the Braavosi faith since they are firmly anti-slavery).

Note that *Hostile Faith Slavery* can never be less accepted than *Righteous Faith Slavery*.

## Links

* [LoversLab](https://www.loverslab.com/files/file/32307-carnalitas-agot-compatibility/)
* [GitHub Repository](https://github.com/pharaox/carnalitas_agot)

If you like this mod, you may also consider my other mods:

* [Carnalitas Slavery Reimagined](https://www.loverslab.com/files/file/25565-carnalitas-slavery-reimagined/), a comprehensive rework of the Carnalitas slavery system.
* [Carnalitas Love Reimagined](https://www.loverslab.com/files/file/29200-carnalitas-love-reimagined/), a rework of the Carnalitas *Make Love* interaction and its related effects.
* [Search & Trade Artifacts](https://steamcommunity.com/sharedfiles/filedetails/?id=2962238514), search for artifacts, buy them from other characters, and sell them to other characters.
* [Travelers](https://steamcommunity.com/sharedfiles/filedetails/?id=3082182371), characters always travel to their home when it changes instead of teleporting.
* [Active Courtiers](https://steamcommunity.com/sharedfiles/filedetails/?id=3157170996), courtiers search for spouses themselves for less micromanagement, stronger AI, and immersion.
