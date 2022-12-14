<h1>Crafting and Gathering</h1>

A CRAFTING SYSTEM for Foundry FVTT and D&D 5e.

<h2>System and Module Dependencies.<h2>
- Foundry FVTT 10.291
- DND5e System 2.0.3
- Advanced Macros 1.18.1
- Compendium Folders 2.5.6
- Gatherer 1.4
- Item Containers 10.0.4
- Item Piles 2.3.7
- Mastercrafted 1.5.3

Installation Manifest: https://raw.githubusercontent.com/tlaroy/crafting-gathering/main/module.json 

<p>The module installs all the CRAFTING SYSTEM Compendiums.  It also downloads a spreadsheet design reference and a zip of all the Mastercrafted export JSON files.  Look in your Data\modules\crafting-gathering folder.</p>

NONE of the CRAFTING SYSTEM Item Compendiums need to be imported to your World Directories.
  
<h2>Item Compendiums</h2>
- Crafting Features (Professions)
- Crafting Tools (SRD Supplements)
- Crafting Recipe Books (Empty)
- Crafting Ingredients
- Crafting Recipes
- Crafting Results

<p>Features, Tools and Recipe Books are manually placed into a PC character sheet when a player acquires a Profession.</p>

<p>Initial starting Ingredients, Recipes and Results can also be manually placed into a PC character sheet.  PC’s can acquire Ingredients, Recipes and Results from Merchants or by Gathering.</p>

<p>For my campaign I added player owned “Crafting” containers in the Item Directory.  Players can put all their crafting ingredients, recipe books and tools in them instead of loading up their character sheet inventories with items that they’d very unlikely be dragging around with them all the time.  When it’s time to do crafting the necessary tools and ingredients are transferred to PC sheet inventories.  They’re really just extensions of the player character sheet inventories.</p>

Import these CRAFTING SYSTEM Compendiums into your world directories.
  
<h2>Macro, Roll Table, Actor and Journal Compendiums</h2>
- Crafting Macros
- Crafting Roll Tables
- Crafting Merchants (Actor)
- Crafting Journals - Including a Crafting Guide.

<p><b>ALWAYS</b> import CRAFTING SYSTEM Compendiums with “Merge by name” and “Keep ID” checked.  Exports of CRAFTING SYSTEM Compendiums were done using “Export Folder Structure” with same options checked.</p>

<h4>Mastercrafted.</h4> 
<p>Import the Mastercrafted Recipe Book JSON files with Recipe Manager.  Then set player permissions for each Recipe.  Use Book permissions to control overall access by player.  Then use Recipe permissions to limit access to those Recipes that players have learned so far.  There are no automatic linkages between Mastercrafted Recipes and CRAFTING SYSTEM Recipes.</p>

<h4>Gatherer.</h4> 
<p>Uses customized Journal Pages and Roll Tables, both access controlled by standard FVTT methods.  A Gatherer Journal Page can be dropped on Scenes and it becomes a resource node, i.e. a Warcraft mining node.  And the page can be used directly for downtown activities.  Players get X rolls per Y workdays : )</p>

<p>Mastercrafted and Gatherer both use Macros to roll ability checks with DC determined by player level.</p>

<p>Mastercrafted Recipes, Gatherer and CRAFTING SYSTEM Recipes all use Ingredients and Results - ONLY - from CRAFTING SYSTEM compendiums - OR - the SRD compendiums.  Only core FVTT icons have been used.</p>

<p>FVTT SRD Items were used for Results and miscellaneous items such as parchment, ink, etc. whenever possible.  The SRD is rather weak on Ingredients.  Many FVTT SRD Items lack price, rarity or weight.  Consequently there are CRAFTING SYSTEM Items which supersede FVTT SRD Items.  CRAFTING SYSTEM Items will end up in circulation from Crafting, Gathering, purchase from Merchants, looting corpses and discovery of loot boxes all ending up in player inventories.  Mixing superseded FVTT SRD and CRAFTING SYSTEM Items should be avoided.  Nothing “breaks” per say.  Mastercrafted and Gatherer still work.  However some FVTT SRD Items when sold to a Merchant from a player’s inventory with no price are interpreted as being “free”.  Little things.  CRAFTING SYSTEM Ingredients are not “free” : )</p>

<h4>Ingredients.</h4> 
<p>Setting up Roll Tables for Gatherer lead to “Grouping” of ingredients so the odds of getting what you’re looking for are more reasonable than a random roll on a table of (50) herbs.  Result is (6) Ingredient Categories (Fish, Game, Herb, Ore, Toxin & Wood) with (5) Rarities (Common, Uncommon, Rare, Very Rare & Legendary) each.</p>

<h4>Merchants.</h4> 
<p>Ingredient Merchants are also organized by Category and Rarity and they’re linked to the same Roll Tables used by Gatherer.  Roll Tables are also provided for Recipe Merchants and Profession Merchants (i.e. those selling crafting related Results); all Merchants are linked to Roll Tables.</p>

<h4>Hybrids.</h4> 
<p>Poisoner and Mining are hybrids.  Poisoner, nominally a crafting profession, gathers toxins to make poisons.  Mining, nominally a gathering profession, crafts metals from ore.  Rather than mashing them together Poisoner now includes Toxicology and Mining includes Smelting.</p>

<i>Nokturnel 12/13/2022</i>
