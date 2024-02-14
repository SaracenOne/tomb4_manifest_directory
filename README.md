# Tomb4Plus - Manifest Directory
## A community-sourced collection of config files to allow custom levels to be playable with Tomb4Plus.

This repository contains a collection of JSON files designed to allow Tomb Raider games based on the Tomb Raider 4 engine to be made playable with the community built open source [Tomb4Plus](https://github.com/saracenone/tomb4) engine and the various modernization and quality of life enhancements it brings. This includes Tomb Raider: The Last Revelation, Tomb Raider: The Times Exclusive level, and community-built levels created with the Tomb Raider Level Editor.

### Instructions
You can download custom Tomb Raider levels from sites such as (https://trle.net/) or (https://trcustoms.org/). If a corresponding level manifest is contained in this repository, copy its `game_mod_config.json` file into its game directory. Then either place the `tomb4plus.exe` file from Tomb4Plus into the corresponding directory or run it with the `PATH="path/to/directory/` command line argument.

If a manifest file for a corresponding level does not exist yet, it either simply hasn't been added or Tomb4Plus does not yet have the necessary features required to make it fully playable. If you believe the engine can run a particular custom level, use the [Tomb4 Feature Extractor](https://github.com/saracenone/tomb4_feature_extractor) to generate custom manifest file.

Be aware though, the manifest files contained in this repository come with a degree of confidence that their corresponding custom level should be both fully playable, completable, and be behaviourally accurate to the original version. For custom levels which make use of TREP/FLEP patches and advanced TRNG features, there is a high probability that while they will be functional, many features will be broken or inaccurate.

### Contributing
If you created a manifest file for a level and feel highly confident that Tomb4Plus fully supports it and is bug-free, feel free to submit a pull request to have the manifest added to the database. You can also submit updates or file issues for existing manifest files, but please provide as much information as possible.