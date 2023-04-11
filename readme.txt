================================================================
Poker Playing Cards Resource Pack
================================================================

How to use the pack
================================================================
Resource pack works on the "CustomModelData" NBT tag basis.
To use textures provided by this pack, you need to assign
an NBT tag {CustomModelData: xx}, where 'xx' is the number
to be assigned. Resource pack is registered in the MC Datapacks
registry (https://mc-datapacks.github.io/en/index.html),
and its assigned ID is number '22', which is the start of all
the model numbers. Numbers chart table can be seen in the
'numbers.txt' file.

Wthout a datapack, you need /give command permission. Then you
perform command /give @s minecraft:item{CustomModelData:num}
where 'num' is the number of the the texture and 'item' is
the corresponding item you need to get. Refer to the chart.

Examples:
- /give @s minecraft:paper{CustomModelData:221411}
  gives you Queen of Hearts card
- /give @s minecraft:sunflower{CustomModelData:222101}
  gives you a poker chip

Remember that the resource pack only changes the model, not
the item name. If you want to give the item a name, use anvil
or code your datapack that assigns the necessary data
to the items for certain conditions. Poker pack is a resource
pack for map builders and server owners.

WARNING!
Since it's been registered in the datapack registry (despite
being a resource pack), you still need to check for any
possible collisions! Reason is that not everyone is using
this registry to somehow prevent collisions. They may not
use any registry at all, or use another registry I don't know
about. If there are collisions, you need to make necessary
changes to eliminate them. Resource pack is designed for map
makers and server owners and as such I assume you have some
technical knowledge and skills with datapack and resourcepack
handling and editing. If not, check out YouTube for tutorials.
