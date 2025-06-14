---
sidebar_position: 5
---

# Farming

:::note Disclaimer
Our skills system is quickly evolving, this article may become outdated. You can check skill perks in game by running: \
`/skill_perks <Skill Type>`. You can also check the `#changelog` in our Discord Server [(Click Here)](https://discord.gg/zcWwHgQyjN).
:::

The farming skill can be progressed by harvesting crops. Food is a scarce resource in Colony Craft and farmers are a very useful asset to all players in the server.

Crops can be farmed on your own land or found randomly across the map:
<img src="/img/crop.png" width="700" />

<br />
<br />

Harvesting any **fully grown** crop will give you XP (See [XP Table](#xp-table)). Cocoa is the most common crop found across the map which spawns in jungles.

### Creating a Farm

Seeds can only be planted on claimed land, follow our [Claiming Land](/docs/claims/claims.md) tutorial to find out how to claim land. Once these have been planted, and your crops have fully grown, you can harvest them for XP.

**Growth Rates** \
Crops that are placed inside a claim grow 2x slower than usual rates in Minecraft. This is increased to the usual rate when reaching Level 3. When you are offline, crops grow 4x slower, no matter what level the player is.

### Animal Farming (beta)

:::warning Discalimer
This feature is in beta, while it is safe to use, it may cause unexpected behaviour. Please report any bugs found in the `#bug-report` channel in our Discord Server.
:::

Animal farming requires Farming Level 2 to be started ([See Level Perks](#levels)).

We have completely overhauled the way that farming animals working in Minecraft!

You can assign animals to your claim, which can be grown by using animal feeders. The more an animal has grown, the more meat and other materials will be dropped when it is killed. Note that each claim can have a **maximum of 10 animals**.

The following animals can be farmed in Colony Craft:

- Cow
- Pig
- Chicken
- Sheep

To start your farm:

1. Craft Animal Feeders & Place on your Claim ([See Animal Feeder Recipe](/docs/recipes/animal-feeder.md))
2. Fill Animal Feeders with Food (you can use any crop/plant)
3. Lure an animal to your claim (see [Claims Guide](/docs/claims/claims.md))
4. Feed it its preferred food by right-clicking (ensure animal is hungry first)
5. Refill Feeders as Needed
6. Wait for Animals to Grow

:::info Tips

- Animals will eat from a feeder every minute, and each feed will give them 1% growth
- A feeder will become empty after it has been eaten from 35 times (35 minutes), and will need refilling
- Ensure feeders are not placed too far away, otherwise animals will not be able to find them
- Place more feeders in the claim so that they take longer to empty, and so that animals don't fight for the same feeder
- Ensure animals have no way to escape your claim, or walk outside of your claimed area, otherwise they will automatically lose their growth progress
  :::

<img src="/img/animalfarming.gif" />

When an animal is killed, they will drop a meat and any materials associated with that animal. The growth of the animal determines how much meat & materials they will drop:
<img src="/img/animaldrops.gif" />

An animal will have a green "Fully Grown" indicator when they have grown to their maximum potential, their maximum growth will depend on your [Farming Level](#levels):
<img src="/img/fullygrown.png" width="80%" />

### Bees

:::warning Disclaimer
Our map does not spawn Bees nests naturally, you must get these to spawn yourself using Oak, Birch or Cherry Saplings.
:::

Bees can be used to accelerate crop growth on your farm. You first need a bees nest to spawn nearby your claim. The [Minecraft Wiki](https://minecraft.wiki/w/Bee_Nest#Post-generation) addresses how to spawn bees nests post world generation:

> _Oak, birch, or cherry trees grown from saplings that are within 2 blocks (including diagonally) of a flower on the same Y-level have a 5% chance to grow with a bee nest containing 2–3 bees. This holds true in any biome in any dimension, and for any flower including wither roses and flowering azaleas._

Bees carrying pollen can be used to accelerate the growth of your crops:

<div style={{ display: "flex" }}>
    <div>
        <img src="/img/bee.webp" width="250" />
        Bee without necter.
    </div>

    <div>
        <img src="/img/bee_nectar.webp" width="250" />
        Bee with necter.
    </div>

</div>

If a bee with necter is lured (using a flower), or flies over your crops, it has a chance of pollenating them, if this happens you will gain XP and your crop's growth will be accelerated:

<img src="/img/bees.gif" />

<br />
<br />

### Harvesting Honey

At Level 3 you can also harvest honey from bees nests which can be an excellent food source for players. At Level 4 you can craft bee hives to place directly in front of your farms (to pollenate crops faster).

You can use a bottle/shears to harvest honey from a bees nest or hive. Harvesting honey from either of these will give you [XP](#xp-table)!

### Bonemeal

At level 1 you are able to craft bonemeal. This can be used to accelerate the growth of your crops. Bones are required to craft bonemeal, however, which can only be obtained by players with the Combat Skill [(Learn More)](/docs/skills/combat.md#bones).

### Levels

#### Level 1

- 20 Crops Per Claim
  Can Use Bonemeal

#### Level 2

- 40 Crops Per Claim
- Can Farm Animals (Max 20% Growth)
- Can Cook Food

#### Level 3

- Can Harvest Honey
- Crops Grow 2x Faster
- Max Animal Growth to 45%

#### Level 4

- 60 Crops Per Claim
- Can Craft Bee Hive ([Vanilla Recipe](https://minecraft.fandom.com/wiki/Beehive#Crafting))
- Max Animal Growth to 70%

#### Level 5

- 100 Crops per Claim
- Max Animal Growth to 100%

### XP Table

XP gained for harvesting crops/food sources:

|         Harvest          | XP Amount |
| :----------------------: | :-------: |
|          Honey           |    100    |
| Wheat, Carrots, Potatoes |    80     |
|  Melon, Pumpkin, Cocoa   |    25     |

You can also gain XP from the following:

- Cooking Meat in a Furnace: **8XP per Cooked Meat**
- Growing Animals: **50XP per 20% Growth**
