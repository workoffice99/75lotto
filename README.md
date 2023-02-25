# Candy Machine v3 UI Introduction
Hi! This is a production ready **Candy Machine V3** responsive UI which can be easily customized.
Major features of the CMv3 such as Candy Guards are implemented & auto-detected.

### Preview
![Desktop preview of Candy Machine V3](https://cdn.discordapp.com/attachments/1039648022516215919/1072170298398474250/cmv3.png)
— Desktop preview.

Preview it live [here](https://wearekite-cmv3-ui.vercel.app/).

### Deploy with Vercel *(recommended)*
Vercel is great to host your Candy Machine on, deploy it instantly by clicking the button below.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fwearekite%2Fcandy-machine-v3-ui&env=NEXT_PUBLIC_SOLANA_NETWORK,NEXT_PUBLIC_RPC_HOST,NEXT_PUBLIC_CANDY_MACHINE_ID&project-name=my-kite-cmv3&repository-name=my-kite-cmv3)

### Implemented features
- [x] Responsive UI
- [x] Single Mint UI
- [x] Multi Mint UI
- [x] Start Time Countdown
- [x] Preview Minted NFTs
- [x] Guards Supported
  - [x] Start Date
  - [x] End Date
  - [x] Sol Payment
  - [x] Token Payment
  - [x] Mint Limit
  - [x] Bot Tax
  - [x] Token Burn
  - [x] Token Gate
  - [x] NFT Payment
  - [x] NFT Burn
  - [x] NFT Gate
  - [x] Redeemed Amount
  - [x] Address Gate
  - [x] Allow List
  - [x] Gatekeeper

### Multi Group 
*For Multi-group functionality use cmv3-demo-initialization branch*

### Env Variables
```
NEXT_PUBLIC_SOLANA_NETWORK=mainnet/devnet
```
```
NEXT_PUBLIC_RPC_HOST=networkURL
```
```
NEXT_PUBLIC_CANDY_MACHINE_ID=candyMachineID
```
*If on Vercel or a similar host you need to add these as environmental variables in your project settings.*

### Quick customization
Want to customize the color scheme? This frontend uses 6 main colors that can be found in [globals.css](/styles/globals.css) change these values and the changes will apply globally.
```
:root {
  --main-background-color: #0E0E0E;
  --alt-background-color: #202020;
  --white: #fff;
  --black: #000;
  --primary: #4E44CE;
  --error: #D92D20;
}
```

### Preview alternative Candy Machine states
![Candy Machine V3 with Start Date](https://media.discordapp.net/attachments/1039648022516215919/1072171560288399440/startdatecmv3.png)
— Candy Machine V3 with Start Date

![Candy Machine V3 with Address Gate, Allow List or other similar guards](https://cdn.discordapp.com/attachments/1039648022516215919/1072171559520833656/privatecmv3.png)
— Candy Machine V3 with Address Gate, Allow List or other similar guards

### Credits
Thanks to [Solana Studio](https://github.com/Solana-Studio) for creating the original frontend. This repo is an addition onto theirs with more frontend features and dynamic functions.

## Feedback/Collaborating/Support
If you have any feedback, want to collaborate or need support, please reach out to us at hello@kite.studio
