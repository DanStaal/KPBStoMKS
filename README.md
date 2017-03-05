# MKS (and OSE) addons for Kerbal Planetary Base Systems

This is a simple set of compatablity patches enabling MKS support in Kerbal Planetary Base Systems.  Currently it focuses on two specific MKS mechanics: Wear and Logistics.  In addition it enables rudimentary support for OSE Workshops, and enables Kolonization bonuses when using KPBS parts, as well as tying in to some other MKS niceties.  (Weight transfer in applicable places, and support for intertial tethering, for instance.)

Of course, Kerbal Planetary Base Systems is required, as is Module Manager.  Technically nothing else is - but this patch set won’t do much without MKS, Konstruction, USI-LS, or OSE Workshops installed.  (Mostly MKS - but minimal requirements are applied to each part.)

## IMPORTANT NOTE FOR PATHFINDER USERS!!!

Pathfinder supplants many of the KPBS parts with it’s own variants, which aren’t particularly well suited to MKS, and would be a pain to work around.  Therefore:

**_This mod removes most Pathfinder support for KPBS._**

If you dislike this, the Pathfinder removal is collected into one file, and removing it will leave Pathfinder active - but note that parts may produce strange behavior, have multiples of the same resources, or behave poorly in other ways.  A better option is to choose which system you want KPBS parts to support: Pathfinder or MKS.  If you want them to support Pathfinder, it’s better to just remove this patchset.

## Additional Parts:

These patches add the following parts:

- An inline workbench
- An end-unit workbench
- Switchable Kontainers for all MKS resources, in four sizes.
- Construction-port compatible docking port variants of both KPBS docking ports.
- A short-range power distribution block in the KPBS container format.
- A long-range power distribution block in the KPBS container format.

Both workbenches are simple clones of the airlocks, and have OSE workshop support, as well as MKS autorepair support.  The end-units are slightly more productive than the inline units.

For users of the older versions of this patchset, the older containers of MaterialKits and SpecializedParts have been depreciated, but are still present.  Expect them to be removed at some point in the future.

The new containers are clones of the fuel tanks, and get appropriate logistics.  (See below.)

## Logistics:

The following logistics are added:

- Warehouses to all container tanks.
- Consumer support to FuelCell, Algae, and Greenhouse tanks.
- Local logistics extension to both the Central Hub and the Planetary Command Module.
- Planetary Logistics to the Central Hub.

## Future Plans

A complete MKS production chain is planned.

## Acknowledgements and Thanks

This has been a team effort.  Part models and textures are by dboi88.  Merkov has provided balance suggestions, configs, and help with the .version file.

Gracious thanks goes to Nils277 for access to original model files and textures.

Thanks also to RoverDude for his creation of a balance spreadsheet to help make sure parts aren’t over- or under-powered compared to MKS parts.

## Changelog

    - 0.9.5 beta: New version for MKS 0.50+.  New features include:
        - Fully functional Kontainers (The old tanks are depreciated)
        - Ground Construction support
        - Construction Ports in KPBS form-factors
        - Power distribution parts that fit in KPBS racks.
        - Logistics Rebalance
        - Weight Transfer for the KPBS racks and containers.
        - Probably more I've forgotten.
