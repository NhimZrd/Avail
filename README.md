# AvailSetupTheNode
Avail project description + instructions for setting up the node
![hF4a1-NCaYapF4MfsOims](https://github.com/Mozgiii9/AvailSetupTheNode/assets/74683169/e5a2243e-b754-4401-bb8a-6dfc47879233)

# Avail. Project breakdown + installing Light node + doing quests. Let's go!

**Avail** is a decentralized data availability layer designed to support next generation blockchain applications and sovereign Rollups.

**Invested: $27,000,000.**

**Investors: Founders Fund, DragonFly Capital, Balaji Srinivasan and more.**

**Server Specifications:** 
- *4CPU/8RAM/300SSD/Ubuntu 22.04 - recommended.
- *2CPU/4RAM/40SSD/Ubuntu 22.04 - minimum.

**References:**
- [Web-site](https://www.availproject.org/)
- [Discord](https://discord.com/invite/y6fHnxZQX8)
- [Twitter](https://twitter.com/AvailProject)

Recently announced the [Challenge **Avail's Light Client Lift-Off**](https://lightclient.availproject.org/). Now officially just participate and get a chance to win community rewards and smite the first NFT for completed quests.

### QUEST DEADLINE: APRIL 9TH! Don't delay, it is quite possible that this NFT is one of Avail's drop multipliers.

![image](https://github.com/Mozgiii9/AvailSetupTheNode/assets/74683169/a74887ed-b0f0-496a-ac08-08f9b4489033)

##### What we will need?

- A server of the desired configuration;
- An installed SubWallet or any other Polkadot related wallet. Link to download SubWallet - [GOOGLE](https://www.subwallet.app/downl).
- Discord, Telegram, Twitter - a typical set of cryptan;
- Patience, because [crane](https://faucet.avail.tools/) lags terribly.
**Let's start by installing the node.

**1. Update the contents of the server

```
sudo apt update && sudo apt upgrade -y
```

**2. Install screen:**

```
sudo apt install screen
```

**3. Install node with one command:**

```
curl -sL1 avail.sh | bash
```

Logs will appear, sooner or later there will be an error that the node was crashing. Create a script to automatically restart the node:

**4. Execute the commands one by one:**

```
rm -rf /root/.avail/data
```
