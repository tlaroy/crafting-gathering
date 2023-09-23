# Crafting & Gathering

A CRAFTING SYSTEM for Foundry VTT and D&D 5e

## ( 22 ) Crafting Professions with ( 317 ) Recipes

- Alchemy ( 45 Recipes )
- Apothecary ( 7 Recipes )
- Brewer ( 0 Recipes )
- Calligrapher ( 0 Recipes )
- Carpenter ( 0 Recipes )
- Cartographer ( 0 Recipes )
- Cobbler ( 0 Recipes )
- Cooking ( 1 Recipes )
- Enchanting ( 38 Recipes )
- Glassblower ( 7 Recipes )
- Inscription ( 17 Recipes )
- Jewel Crafting ( 15 Recipes )
- Leather Working ( 9 Recipes )
- Mason ( 0 Recipes )
- Painter ( 0 Recipes )
- Poisoner ( 16 Recipes )
- Smelting ( 24 Recipes )
- Smith ( 60 Recipes )
- Tinker ( 15 Recipes )
- Weaving ( 14 Recipes )
- Wood Working ( 37 Recipes )

## ( 7 ) Gathering Professions ( 249 ) Ingredients

- Cloth ( 48 Cloths )
- Fishing ( 1 Fish )
- Herbalism ( 53 Herbs )
- Hunting ( 20 Game )
- Logging ( 23 Wood )
- Mining ( 20 Ores )
- Toxicology ( 17 Toxins )

## System & Module Dependencies

- Foundry VTT 11.309
- DND5e System 2.3.1
- Advanced Macros 1.19.6 (10)
- Compendium Folders 2.6.1 (11.298) no longer needed after v10 migration.
- Dynamic effects using Active Effects (DAE) 11.0.17 (11.308)
- Gatherer 1.4 (10)
- Item Containers 11.0.3 (11.308)
- Item Piles 2.7.13
- Mastercrafted 1.7.2 (10)

## Installation Instructions

Installation Manifest: https://raw.githubusercontent.com/tlaroy/crafting-gathering/main/module.json 

The module installs all the CRAFTING SYSTEM Compendiums.  It also downloads a spreadsheet design reference and Mastercrafted Recipe Book export JSON files.  Look in your Data\modules\crafting-gathering folder.

## Item Compendiums

- Crafting Features
- Crafting Tools
- Crafting Training
- Crafting Ingredients
- Crafting Recipes
- Crafting Results

NONE of the CRAFTING SYSTEM Item Compendiums need to be imported to your World Directories.  Features and Tools are manually placed into a player character sheet when a player acquires a Profession.  Initial starting Ingredients and Results can also be manually placed into a player character sheet.  Players can acquire Training, Ingredients, Recipes and Results from Merchants or by Gathering.

For my campaign I have player owned 'Crafting' containers in the Item Directory.  Players can put all their crafting ingredients, recipe books and tools in them instead of loading up their character sheet inventories with items that they’d very unlikely be dragging around with them all the time.  When it’s time to do crafting the necessary tools and ingredients are transferred to their character sheet inventories.  The 'Crafting' containers are really just extensions of the player character sheet inventories.
  
## Macro, Roll Table, Actor and Journal Compendiums

- Crafting Macros
- Crafting Roll Tables
- Crafting Merchants
- Crafting Journals

Import these CRAFTING SYSTEM Compendiums into your world directories.  <b>IMPORTANT - ALWAYS!</b> import CRAFTING SYSTEM Compendiums with 'Merge by name' and 'Keep ID' checked.  Exports of CRAFTING SYSTEM Compendiums were done using 'Export Folder Structure' with same options checked.

## Crafting Guide
The crafting journal <b>Crafting Guide</b> has all the details explaining each profession, their recipes, ingredients, costs and more.

## Mastercrafted
Import the Mastercrafted Recipe Book JSON files using Mastercrafted's Recipe Manager.  The files are in your Data\modules\crafting-gathering\exports folder.  Use Recipe Book permissions to limit overall access to only players who 'know' the profession.  Then default Recipe permissions for those that each player has learned so far; deny for those unlearned.

## Gatherer
Gatherer uses customized Journal Pages and Roll Tables both access controlled by standard FVTT methods.  A Gatherer Journal Page can be dropped on Scenes and it becomes a resource node, i.e. a Warcraft mining node.  And the page can be used directly for downtown activities.  Players get X rolls per Y workdays.

## Macros
Mastercrafted and Gatherer both use Macros to roll ability checks with DC determined by player level.

- Level 17-20 = DC 12
- Level 11-16 = DC 11
- Level 6-10 = DC 10
- Level 4-5 = DC 9
- Level 1-3 = DC 8

## Referencing
Mastercrafted Recipes, Gatherer and CRAFTING SYSTEM Recipes all use Ingredients and Results - ONLY - from CRAFTING SYSTEM compendiums - OR - the FVTT SRD compendiums.  Only core FVTT icons have been used. 
FVTT SRD Items were used for Results and miscellaneous items such as parchment, ink, etc. whenever possible.  The SRD is rather weak on Ingredients. 

## Merchants
All Merchants are linked to  Roll Tables.  Gatherer uses the same Roll Tables as Ingredient Merchants.

## Credits
Modules created by TheRipper93 - https://theripper93.com/#/

- Mastercrafted https://wiki.theripper93.com/premium/mastercrafted 
- Gatherer https://wiki.theripper93.com/premium/gatherer

<i>Nokturnel</i>