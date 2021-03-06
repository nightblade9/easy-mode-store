# Easy Mode Store

Easy-mode store mod for Stardew Valley. Adds difficult-to-get and bundle items (e.g. irridium ore, truffle) to Pierre's store, at affordable prices. Also replaces JojaMart's inventory with three of the same items, randomly chosen, each day.

If you have any questions, comments, improvements, bugs, suggestions, etc. please open an issue [here](https://github.com/nightblade9/easy-mode-store/issues).

# Requirements

Requires the [Shop Tile Framework mod](https://www.nexusmods.com/stardewvalley/mods/5005) and all transitive dependencies / related mods (Json Assets, etc.)

# Installation

Simply download and unzip the mod to your `Mods` directory and you're good to go. I highly recommend you install the [Crops Anytime Anywhere](https://www.nexusmods.com/stardewvalley/mods/3000) mod so you can plant the seasonal crops without waiting ages for the right season to arrive.

# Customization

If you wish to add your own items to the store, open up `shops.json`. Simply copy/paste the second-last item to make a new item. The fields are self-explanatory: 

- `ItemNames` specifies the in-game name of the item (in square brackets)
- `StockPrice` is the price (in gold) for the item
- `Stock` is how many of that item Pierre has, per-day

If you're interested in more complex configuration, check the Shop Tile Framework readme. Note that these changes will be obliterated when you update. I highly recommend you copy/paste the entire folder, change the manifest.json fields, and make it your own mod.