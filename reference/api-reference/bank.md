# Bank



{% hint style="info" %}
Access these members using bank.`<method>`
{% endhint %}

| name         | type        | description                        |
| ------------ | ----------- | ---------------------------------- |
| bankContains | string, int | shows a list of what bank contains |
|              |             |                                    |
|              |             |                                    |

{% hint style="info" %}
Access these methods using bank`:<method>`\
To check if the bank is open Bank : isopen(`)`which will return `true` or `false`
{% endhint %}

<details>

<summary>isOpen ()</summary>

Returns `true` if the bank is open

</details>

<details>

<summary>contains(itemId | itemName)</summary>

Returns `true` if the bank contains X items

</details>

<details>

<summary>withdraw(itemId | ammount)</summary>

Withdraws `x` items with `x` ammount that is defined  `1-28`

</details>

<details>

<summary>WithdrawPreset(1-15)</summary>

Withdraw form Preset `1-15`&#x20;

</details>

<details>

<summary>deposit(itemId | ammount)</summary>

Deposit `x` items with `x` ammount that is defined  `1-28`

</details>

<details>

<summary>depositAll()</summary>

Deposits all items from Inventory

</details>

