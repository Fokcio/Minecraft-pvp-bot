# Give yourself a command block:
`/give @s minecraft:command_block`
 
# Put in 1st commandblock:
`/summon minecraft:skeleton ~ ~1 ~ {CustomName:Sub_to_SureGG,CustomNameVisible:1,Attributes:[{Name:"generic.followRange",Base:80}],HandItems:[{id:"minecraft:diamond_sword",tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},Count:1,AttributeModifiers:[{AttributeName:"generic.attackSpeed",Name:"generic.attackSpeed",Amount:999999999,Operation:0,UUIDLeast:1,UUIDMost:1}]},{}],ArmorItems:[{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},id:"minecraft:diamond_boots",Count:1},{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},id:"minecraft:diamond_leggings",Count:1},{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},id:"minecraft:diamond_chestplate",Count:1},{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},id:"minecraft:diamond_helmet",Count:1}]}`
 
# Put in 2nd commandblock:
`/give @p spawn_egg 1 0 {display:{Name:"Sub_to_SureGG"},EntityTag:{id:"minecraft:skeleton",CustomName:Sub_to_SureGG,CustomNameVisible:1,Attributes:[{Name:"generic.followRange",Base:80}],HandItems:[{id:"minecraft:diamond_sword",tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},Count:1,AttributeModifiers:[{AttributeName:"generic.attackSpeed",Name:"generic.attackSpeed",Amount:999999999,Operation:0,UUIDLeast:1,UUIDMost:1}]},{}],ArmorItems:[{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound"]}},id:"minecraft:diamond_boots",Count:1},{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},id:"minecraft:diamond_leggings",Count:1},{tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}},id:"minecraft:diamond_chestplate",Count:1},{id:"minecraft:diamond_helmet",Count:1,tag:{display:{Name:"Sub to SureGG",Lore:["This item is soulbound!"]}}}]}}`
 
# Put in 3rd commandblock (optional): 
`/effect @e[type=skeleton,name=Sub_to_SureGG] speed 500 0 true
4th commandblock`
 
# Put in 4th commandblock (optional):
`/effect @e[type=skeleton,name=Sub_to_SureGG] strength 500 0 true`
