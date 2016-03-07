# PoEFilter
A lightweight filter which remains close to the default filter scheme.
Check out this guide if you'd like to install or learn more about item filters: http://pathofexile.gamepedia.com/Item_filter

* Currency
    * High tier currency is highlighted (#786446)
    * Mid tier currency untouched
    * Low tier currency (shards/scrolls) font decreased
* Gems
    * Support gems are highlighted
    * Quality %10+ gems (active/support) are bordered
* Recipe Highlighting
    * Quality %10+ flasks are bordered
    * RBG items are bordered (#FF8C8C)
    * 6 sock items are bordered (#FF6464)
    * Chisel recipe is NOT enabled
* Basetypes
    * Items with droplevel <= 20 are filtered 8 levels below the zone
    * Items with droplevel <= 50 are filtered 10 levels below the zone
    * Items with droplevel > 50 are filtered 12 levels below the zone
    * Best in slots are never filtered
    * Rare caster weapons are never filtered (even low bases)
    * Rare rings, amulets, and belts are never filtered
    * Flasks are filtered heavily, and will all be hidden in endgame

Filtered items are given smaller font and reduced background opacity, no items are hidden.

Now supports ascendancy (keys and supplements are highlighted as quest items) and perandus coins.
