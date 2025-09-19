---
sidebar_position: 3
---

# Creating & Leading a Colony

Before reading this guide, it's highly recommended to read the [Colonies](/docs/colonies/colonies.md) guide first.

## Start a Colony

In order to create a colony, you must first craft a colony core. See [Colony Core Recipe](/docs/recipes/colony-core.md).

:::info Tips

- Once you have placed a colony core, you cannot move or destroy it. Ensure you have chosen a safe place before placing it.
- Colony members are also able to raid your colony core, ensure the core is hidden from colony members and protected in claimed land
  :::

Once you have a Colony Core, place it where you want your colony to start! You will then prompted to provide a name, access level and color:
<img src="/img/colonycreate.gif" />

<br />
<br />

By default your colony will have 1 hour before it begins to decay. After you have created your colony, you need to place a community chest in your colony's land so that you can add resources to it and increase the decay time. See the [Community Chest Guide](/docs/colonies#community-chest) for more info.

<img src="/img/communitychest.gif" />

## Colonising Land

:::info Tips

- Colony chunks must be connected together to be saved
- To unlock more slots, you must level up your colony in the community chest
- Your colony's time until decay will decrease when expanding your colony
- Expanding your colony will increase the upkeep cost, likewise shrinking the colony size will decrease the upkeep cost
  :::

By default your colony only spans the chunk in which you placed the Colony Core. To claim more land you can use the "Colony Expansion Mode" which allows you to add more chunks to your colony.

To do this, run the `/colony_expand_mode` command to enter colony expansion mode.

It is recommended to press `F3+G` to display the chunks in the world. To claim a new chunk, punch the ground of the new chunk and it will be added to your colony expansion. Ensure that the chunks are connected so that your expansion is valid. You can also remove chunks that you have claimed by punching the ground of that claimed chunk.

When you are finished editing your colony expansion, you can run `/colony_expand_confirm` to confirm your expansion:

<img src="/img/colonyexpansion.gif" />

## Colony Access

#### Public Colonies

If your colony is public, this means that anyone can join your colony with `/colony_join <name>`. If you would like to prevent specific players from joining, you can [banish](#banishunbanish-players) them from your colony.

#### Invite Only Colonies

Invite only colonies require all members to be invited, meaning no one can just join the colony. You can invite members to your colony with the `/colony_invite <playername>` command.

#### Changing Colony Access

If you would like to change the access of your colony you can use the `/colony_set_access access=<public | invite_only>` command.

## Member Count

You can check the number of members in your colony by running `/colony_member_count`. This command is available to all colony members.

## Check Player Skills

As a colony leader, you can check what skills another player has by using the `/skills <playername>` command.

## Banish/Unbanish Players

You can banish a player from your colony no matter if they are already in your colony or not. This can be done with the `/colony_banish <playername>`. A player does not need to be online to be banished, just ensure you specify the correct username.

If a player is banished they will:

- Be removed from your colony (if a member)
- Not be able to join your colony again (regardless of access level)

You can however unbanish a player which will allow them to rejoin your colony with the `/colony_unbanish <playername>` command.

## Transfer Leadership

:::warning
If you transfer leadership to another player, you will not be able to lead this colony again.
:::

You can transfer the leadership of your colony to another player if you are stepping down from your position. The other player does not have to agree to be assigned the leader position.

In order to do this you must:

- Be standing within 10 blocks of the other player
- Run `/colony_transfer_leader <playername>`

## Delete Colony

:::warning
When deleting a colony, you will not be able to create another one for 3 days.
:::

Deleting a colony will remove all members, claim whitelists & notify all players that the colony has been deleted.

You can do this by running the `/colony_delete` command and `/confirm delete`.
