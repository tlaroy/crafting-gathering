# Crafting & Gathering

A CRAFTING SYSTEM for Foundry VTT and D&D 5e

## (14) Crafting Professions with (237) Recipes

- Alchemy (40 Recipes)
- Apothecary (8 Recipes)
- Brewer (0 Recipes) 
- Cooking (0 Recipes)
- Enchanting (59 Recipes)
- Engineering (1 Recipe)
- Inscription (10 Recipes)
- Jewel Crafting (17 Recipes)
- Leather Working (4 Recipes)
- Poisoner (20 Recipes)
- Smelting (13 Recipes)
- Smith (44 Recipes)
- Weaving (3 Recipes)
- Wood Working (18 Recipes)

## (7) Gathering Professions (112 Types)

- Cloth (4 Cloths)
- Fishing (1 Fish)
- Herbalism (52 Herbs)
- Hunting (9 Game)
- Logging (22 Wood)
- Mining (10 Ores)
- Toxicology (14 Toxins)

## System & Module Dependencies

- Foundry VTT 10.291
- DND5e System 2.0.3
- Advanced Macros 1.18.1
- Compendium Folders 2.5.6
- Gatherer 1.4
- Item Containers 10.0.4
- Item Piles 2.3.7
- Mastercrafted 1.5.3

## Installation

Installation Manifest: https://raw.githubusercontent.com/tlaroy/crafting-gathering/main/module.json 

The module installs all the CRAFTING SYSTEM Compendiums.  It also downloads a spreadsheet design reference and a zip file of all the Mastercrafted Recipe Book export JSON files.  Look in your Data\modules\crafting-gathering folder.

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
Import the Mastercrafted Recipe Book JSON files from the zip file using Mastercrafted's Recipe Manager.  The zip file is in your Data\modules\crafting-gathering\exports folder.  Use Recipe Book permissions to limit overall access to only players who 'know' the profession.  Then default Recipe permissions for those that each player has learned so far; deny for those unlearned.

## Gatherer
Gatherer uses customized Journal Pages and Roll Tables both access controlled by standard FVTT methods.  A Gatherer Journal Page can be dropped on Scenes and it becomes a resource node, i.e. a Warcraft mining node.  And the page can be used directly for downtown activities.  Players get X rolls per Y workdays.

## Macros
Mastercrafted and Gatherer both use Macros to roll ability checks with DC determined by player level.

- Level 17-20 = DC 12
- Level 11-16 = DC 11
- Level 9-10  = DC 10
- Level 5-8   = DC 9
- Level 1-4   =	DC 8

## Referencing
Mastercrafted Recipes, Gatherer and CRAFTING SYSTEM Recipes all use Ingredients and Results - ONLY - from CRAFTING SYSTEM compendiums - OR - the FVTT SRD compendiums.  Only core FVTT icons have been used.

FVTT SRD Items were used for Results and miscellaneous items such as parchment, ink, etc. whenever possible.  The SRD is rather weak on Ingredients.  Many FVTT SRD Items lack price, rarity or weight.  Consequently there are CRAFTING SYSTEM Items which supersede FVTT SRD Items.  CRAFTING SYSTEM Items will end up in circulation from Crafting, Gathering, purchase from Merchants, looting corpses and discovery of loot boxes all ending up in player inventories.  Mixing superseded FVTT SRD and CRAFTING SYSTEM Items should be avoided.  Nothing “breaks” per say.  Mastercrafted and Gatherer still work.  However some FVTT SRD Items when sold to a Merchant from a player’s inventory with no price are interpreted as 'free'.  Little things.  CRAFTING SYSTEM Ingredients are not 'free'.

## Ingredients
Setting up Roll Tables for Gatherer lead to 'Grouping' of ingredients so the odds of getting what you’re looking for are more reasonable than a random roll on a table of (50) herbs.  Result is (7) Ingredient Categories (Cloth, Fish, Game, Herbs, Ore, Toxins & Wood) with (5) Rarities (Common, Uncommon, Rare, Very Rare & Legendary) each.

## Merchants
Ingredient Merchants are also organized by Category and Rarity and they’re linked to the same Roll Tables used by Gatherer.  Roll Tables are also provided for Recipe Merchants and Profession Merchants (i.e. those selling crafting related Results); all Merchants are linked to Roll Tables.

## Hybrid Professions
Poisoner and Mining are hybrid professions.  Poisoner, nominally a crafting profession, gathers toxins to make poisons.  Mining, nominally a gathering profession, crafts metals from ore.  Rather than mashing them together Poisoner includes Toxicology and Mining includes Smelting.

## Design Considerations
Primary requirement was to stay within D&D 5e Rules As Written (RAW) as defined by the Standard Reference Document (SRD).  One result is high-end item costs which seem excessive.  High costs can be balanced with an appropriate in-game economy.  And it gives players something to earn and spend their gold on.  My intended usage for my campaign is primarily for downtime activities.  However a random resource node may occasionally appear in some Scenes too.

Mastercrafted Recipes exist in parallel to CRAFTING SYSTEM Recipes.  There are no automatic linkages between Mastercrafted Recipes and CRAFTING SYSTEM Recipes.  CRAFTING SYSTEM Recipes provide value and rarity so they can be purchased from Merchants.  They also provide convenient player viewing in their Recipe Books.  Merchants and CRAFTING SYSTEM Recipes are optional.

## Credits
Modules created by TheRipper93 - https://theripper93.com/#/

- Mastercrafted https://wiki.theripper93.com/premium/mastercrafted 
- Gatherer https://wiki.theripper93.com/premium/gatherer

<i>Nokturnel 12/13/2022</i>
