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
    visible: false
---

# Local Player

## Members

{% hint style="info" %}
Access these members with LocalPlayer.\<member>\
For example: `LocalPlayer.hp` will return the players current health points
{% endhint %}

<table><thead><tr><th width="220.33333333333331">name</th><th width="120">return type</th><th>description</th></tr></thead><tbody><tr><td>hp</td><td>int</td><td>Current HP</td></tr><tr><td>hpMax</td><td>int</td><td>Maximum HP</td></tr><tr><td>hpPercent</td><td>int</td><td>Current HP percentage</td></tr><tr><td>adrenaline</td><td>int</td><td>Current adrenaline</td></tr><tr><td>name</td><td>string</td><td>Name</td></tr><tr><td>address</td><td>int</td><td>Memory address</td></tr><tr><td>orientation</td><td>int</td><td>Direction is facing</td></tr><tr><td>hoverProgress</td><td>int</td><td>Value of overhead progress bar</td></tr><tr><td>position</td><td>WPOINT</td><td>Current position</td></tr><tr><td>prayer</td><td>int</td><td>Current Prayer points</td></tr><tr><td>prayerMax</td><td>int</td><td>Maximum Prayer points</td></tr><tr><td>prayerPercent</td><td>int</td><td>Current Prayer points percentage</td></tr><tr><td>summoningPoints</td><td>int</td><td>Current summoning points</td></tr><tr><td>summoningPointsMax</td><td>int</td><td>Maximum summoning points</td></tr></tbody></table>

## Methods

{% hint style="info" %}
Access these methods using `LocalPlayer:<method>`\
To check if the player is moving `LocalPlayer:isMoving()` which will return `true` or `false`
{% endhint %}

<details>

<summary>isMoving()</summary>

Returns `true` if the player is moving

</details>

<details>

<summary>isAnimating()</summary>

Returns `true` if the player is animating

</details>

<details>

<summary>isInCombat()</summary>

Returns `true` if the player is in combat

</details>

<details>

<summary>isLoggedIn()</summary>

Returns `true` if the player is logged in

</details>

<details>

<summary>isAnimating()</summary>

Returns `true` if the player is animating state

</details>

<details>

<summary>isInteracting()</summary>

Returns `true` if the player is interacting with something

</details>

<details>

<summary>isQuickPrayOn()</summary>

Returns `true` if the quickpray is enabled

</details>

<details>

<summary>isRunOn()</summary>

Returns `true` if running is enabled

</details>



