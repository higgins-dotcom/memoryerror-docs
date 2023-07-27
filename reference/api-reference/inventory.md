---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Inventory

## Members

{% hint style="info" %}
Access these members using Inventory.`<method>`
{% endhint %}

| name       | type | description           |
| ---------- | ---- | --------------------- |
| emptySlots | int  | Amount of empty slots |

## Methods

{% hint style="info" %}
Access these methods using Inventory`:<method>`\
To check if the player is moving Inventory`:isEmpty()`which will return `true` or `false`
{% endhint %}

<details>

<summary>isEmpty()</summary>

Returns `true` if the inventory is empty

</details>

<details>

<summary>isFull()</summary>

Returns `true` if the inventory is full

</details>

<details>

<summary>isOpen()</summary>

Returns `true` if the inventory is open

</details>

<details>

<summary>isItemSelected()</summary>

Returns `true` if **any** item is selected in the inventory

</details>

<details>

<summary>contains(itemId | itemName)</summary>

Checks if the inventory contains a specific item\
Accepts `int itemId` or `string itemName`

</details>

<details>

<summary>containsAny(itemIds)</summary>

Checks if the inventory contains a specific item\
Parameter `itemids` table of item ids `{123, 321}`

</details>

<details>

<summary>quantity(itemId | itemName)</summary>

Returns the quantity of a specific item in the inventory\
Accepts `int itemId` or `string itemName`

</details>

<details>

<summary>items()</summary>

Returns `table<IInfo>`of inventory items

</details>
