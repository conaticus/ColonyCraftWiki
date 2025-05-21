---
sidebar_position: 3
---

# Creating & Leading a Colony

:::warning
Colony names can only be **one word**. We are intending to improve this in an upcoming update.
:::

Creating a Colony requires [Engineer](/docs/skills/engineer.md) Level 2. You can create a colony by running `/colony_create access=<public | invite_only> name=<name (one word only)>.`

**If you are killed by another player as a colony leader, your colony will be deleted and all members will be removed.**

Once you have created a colony, you will be attributed with the LEADER tag and have the colony name next to your username:
<img src="/img/colonytagleader.png" width="50%" />

### Colony Access

#### Public Colonies

If your colony is public, this means that anyone can join your colony with `/colony_join <name>`. If you would like to prevent specific players from joining, you can [banish](#banishunbanish-players) them from your colony.

#### Invite Only Colonies

Invite only colonies require all members to be invited, meaning no one can just join the colony. You can invite members to your colony with the `/colony_invite <playername>` command.

#### Changing Colony Access

If you would like to change the access of your colony you can use the `/colony_set_access access=<public | invite_only>` command.

### Member Count

You can check the number of members in your colony by running `/colony_member_count`. This command is available to all colony members.

### Check Player Skills

As a colony leader, you can check what skills another player has by using the `/skills <playername>` command.

### Banish/Unbanish Players

You can banish a player from your colony no matter if they are already in your colony or not. This can be done with the `/colony_banish <playername>`. A player does not need to be online to be banished, just ensure you specify the correct username.

If a player is banished they will:

- Be removed from your colony (if a member)
- Not be able to join your colony again (regardless of access level)

You can however unbanish a player which will allow them to rejoin your colony with the `/colony_unbanish <playername>` command.

### Transfer Leadership

:::warning
If you transfer leadership to another player, you will not be able to lead this colony again.
:::

You can transfer the leadership of your colony to another player if you are stepping down from your position. The other player does not have to agree to be assigned the leader position.

In order to do this you must:

- Be standing within 10 blocks of the other player
- Run `/colony_transfer_leader <playername>`

### Delete Colony

Deleting a colony will remove all members, claim whitelists & notify all players that the colony has been deleted.

You can do this by running the `/colony_delete` command and `/confirm delete`.
