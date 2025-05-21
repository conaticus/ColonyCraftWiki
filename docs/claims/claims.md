---
sidebar_position: 1
---

# Claiming Land

Claims allow you to protect a piece of land from being interacted with or destroyed by other players. This means anything inside your plot is safe from griefing/being destroyed from other players who do not have a Raid Pickaxe (see [Raids](/docs/raids.md) for more info).

Claims can also be used by farmers to plant their crops.

:::warning Important
Items kept inside containers (such as chests) in your land are not safe from being stolen, please read **[Protecting your Items](/docs/claims/protecting_items.md)** to learn how to protect your items.
:::

### Create a Claim

:::note Note
To begin with you can only create one claim, see the [Engineer](/docs/skills/engineer.md) skill for how to claim more land.
:::

1. Run the `/claim_mode` command to enter claim mode
2. Punch the two corners to define the dimensions of the claim
3. Run `/claim_confirm` command to save the claim

Demonstration:
<img src="/img/claims.gif" />

### Build Mode

You run the `/claim_toggle_build_mode` command to assist in building safely inside your claims. This will prevent you from placing/breaking any blocks outside of your claimed land. This works across all claims. You can run this command again to disable it.

### List Claims

The `/claims` command can be used to list the coordinates of all of your claims.

### Edit a Claim

:::warning Warning
Editing a claim will destroy all crops inside it.
:::

#### Edit Dimensions

1. Stand over an existing claim
2. Run `/claim_mode` command
3. Define the new dimensions of your plot
4. Run `/claim_confirm` & `/confirm edit` commands to save

#### Edit Height

The default height of claims in Colony Craft is 10 blocks up, 4 blocks down.

When editing a claim's height, it will add (blocks up) or subtract (blocks down) from the height of the dimensions you defined for the claim (on the ground).

1. Stand over an existing claim
2. Run `/claim_edit_height blocks_up=[number] blocks_down=[number]`
3. Run `/confirm edit`

### Delete a Claim

:::warning Warning
Deleting a claim will destroy all crops inside it.
:::

1. Stand over an existing claim
2. Run `/claim_delete`
3. Run `/confirm delete`
