# Syrup Pool FAQ & Troubleshooting

## Troubleshooting

### **I can't find the Syrup Pool I was staking in!**

You should be able to find the Syrup Pool under the “Finished” tab on the Syrup Pools page. 

By selecting “Staked Only”, it will make it easier to find your assets.

### **Why can’t I unstake my tokens from a Syrup Pool?**

If you are unable to unstake from the Stake INI, Earn INI pools, please check to make sure that you haven’t sold the SYRUP tokens in your wallet. This token acts as a \`proof of ownership\` over your INI in the Manual INI pool. 

### **Why did my earned tokens go to zero after staking/unstaking?**

Don’t worry! They’re in your wallet already.

Whenever you stake or unstake from a Syrup Pool or farm, your earned tokens get harvested and sent to your wallet at the same time.

## **General Questions**

### How is APR for Syrup Pools calculated?

> Syrup Pool APR = Annualized rewards \(USD\) / User funds staked in Syrup Pool \(USD\) \* 100

As a basic example, let's take a 60-day pool with 300,000 USD worth of rewards, and 3,000,000 USD worth of INI staked in it.

The APR fluctuates as more INI is staked by users, and as the price of INI, and the reward token, vary.

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"><b>Calculation</b>
      </th>
      <th style="text-align:left">Amount</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Total rewards to distribute (USD value)</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">300,000 USD</td>
    </tr>
    <tr>
      <td style="text-align:left">Distribution period</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">60 days</td>
    </tr>
    <tr>
      <td style="text-align:left">Daily distribution</td>
      <td style="text-align:left">300,000 / 60 =</td>
      <td style="text-align:left">5,000 USD daily</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Annualised rewards (USD value)</b>
      </td>
      <td style="text-align:left">5,000 * 365 =</td>
      <td style="text-align:left"><b>1,825,000 USD</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Value of INI staked by users in pool (USD value)</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>3,000,000 USD</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>APR</b>
      </td>
      <td style="text-align:left">(1,825,000 / 3,000,000) * 100 =</td>
      <td style="text-align:left">
        <p></p>
        <p><b>60.833% APR</b>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### **What does the “End” number on my Syrup Pool refer to?**

This shows the amount of blocks left until the rewards for that pool stop being distributed. Once the pool has reached that block, you should unstake your tokens, because you won’t be receiving any rewards after that.

### **Where do the rewards from Syrup Pools come from?**

There are three main types of Syrup Pools.

1. Stake INI, earn INI
2. Stake INI, earn other tokens. 
3. Stake other tokens, earn INI

The rewards for the "Stake INI, earn INI" Syrup Pools come from the [INI emissions](https://docs.iniswap.finance/tokenomics/INI/INI-tokenomics). Each block, a number of INI tokens are allocated as rewards for these pools.

The rewards for the "Stake INI, earn other tokens" type are provided by the project teams who sponsor a Syrup Pool.

For the "Stake other tokens, earn INI" type, the Iniswap treasury buys back INI from the market to distribute as rewards. These pools are funded by iniswap, not by the projects themselves.

### What’s SYRUP Token?

iniswap’s SYRUP Token is deposited in your wallet when you interact with the **Manual** “Stake INI, Earn INI” Syrup Pool. It's not staked for 

It’s basically an IOU that shows how much INI you’ve staked in the pool.

It’ll be returned automatically when you unstake your INI from that pool.

{% hint style="warning" %}
Don’t sell your SYRUP tokens! You need to return your SYRUP to unstake your INI from the Manual INI pool. The amount of SYRUP you return must be the same as the amount of INI you unstake.
{% endhint %}

