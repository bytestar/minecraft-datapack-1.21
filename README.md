# Minecraft-datapack-1.21
Minecraft 1.21 Datapacks customize template

There are two main functions in datapack 
- **demo/data/demo/function/load.mcfunction**
  - execute once when loading a world
- **demo/data/demo/function/tick.mcfunction**
  - execute 20 times in a second

Unzip datapacks-demo.zip  in **%appdata%\.minecraft\saves\<World Name>\datapacks\\**

Unzip resourcepacks-demo.zip in **%appdata%\.minecraft\resourcepacks\\**

**Customized emerald**
/give @s minecraft:emerald[item_name="RedEmerald",minecraft:custom_model_data=1,attribute_modifiers=[{id:"attack_damage",type:"generic.attack_damage",amount:85,operation:"add_value"}]] 1

**Customized diamond sword**
/give @s minecraft:diamond_sword[item_name="HeroSword",minecraft:custom_model_data=1,attribute_modifiers=[{id:"attack_damage",type:"generic.attack_damage",amount:85,operation:"add_value"}]] 1

**Customized sword model**
/give @s minecraft:diamond_sword[item_name="KingSword",minecraft:custom_model_data=2,attribute_modifiers=[{id:"attack_damage",type:"generic.attack_damage",amount:85,operation:"add_value"}]] 1
This sword model is created by BlockBench

**Reference**
https://www.youtube.com/watch?v=dndzP97UL4M
https://youtu.be/tTawouLtCfU?si=PCSihmsDM2Qag_VD
https://youtu.be/E0BLq5Ll37c?si=_7t84EYFc2RUxMgO
