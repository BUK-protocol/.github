# BUK Protocol

![BukProtocol](https://buk-s3-bucket.s3.ap-south-1.amazonaws.com/images/buk-module.webp)

> Modular solution stack for all assets that expire aka dynamic assets

BUK Protocol is a solution stack of modular components which can be used to mint, trade and perform DeFi transactions for all assets that expire aka dynamic assets. The protocol consists of multiple layers:

- `Smart contracts` - Dynamic assets require unique provisions such as validity, burn / discount rate etc. in them across the lifecycle of tokenization, transfers, trading and monetization. These functionalities are not a part of standard ERC721 or ERC1155 contracts. BUK Protocol provides template contracts for various classes of dynamic assets.
- `Oracles` - dynamic assets change their value not just based on market events (price volatility) but also inherently due to the nature of perishability. Hence price feed Oracles are key to operating an ecosystem for dynamic assets. BUK protocol provides Oracles with inbuilt capability to establish provenance, provide price-feeds, and control burn down and backhaul to web2 systems.
- `Marketplace features` - BUK smart contracts include ability for producers to create new closed-loop marketplaces, as well as an aggregated marketplace with cross-marketplace liquidity. Thus asset creators can operate closed loop marketplaces or allow their dynamic assets to be traded on aggregated marketplaces directly. They can also choose a combination of having their closed marketplaces, but allow their assets to be listed on aggregated marketplace.
- `Connectors` - BUK Protocol’s smart contracts have pre-built connectors with other web3 services such as DeFi staking protocols or game development protocols which developers to leverage to extend functionalities and utility of dynamic NFTs.

### Dynamic (Perishable) Assets

Assets which expire - event tickets, perishable in-game props (ex potions, elixirs, fuel, Power-ups etc.) or hotel or airline bookings, memberships and subscriptions etc. - differ fundamentally from perpetual assets such as tokens, PFP NFTs, vehicle or land asset NFTs, gaming avatars etc. Some of the differences are:

- Perpetual assets hold value for the owner for unlimited time. Their value can be retained or escalate / fall persistently but never completely erode. Perishable assets however, have limited purpose - their value erodes over time, or based on usage. Think of:
  - Ammunition in a battle game - it loses value as you use it. Or power-ups which last 4 weeks.
  - Hotel or airline tickets which have value only until the travel date.
  - Subscriptions which erode every month in value whether you use it or not.
- Trading in perpetual assets can continue for unlimited periods, but perishable assets must be traded within their lifespan.
- Perpetual assets can be staked or collateralized without consideration of expiry. Perishable assets on the other hand have expiry and hence additional rules and operations will be necessary to ensure that action is taken on the asset before its value expires.
- Given their ephemeral nature, perishable assets present unique opportunities. Perishable assets can have dynamic market values influenced by factors such as demand, in-game events, or real-world economic conditions.
- Proof of ownership - even though the asset itself expires, the proof of (past) ownership is valuable and can open newer applications. For example - community of gamers who have owned a particular Power Up in past, or loyalty programs for travelers who have stayed in a hotel.
- Cross-chain / Cross-game applicability - perishable assets like fuel, food or ammunition can also be used across games. Perishable RWAs shall require cross-chain movement for better liquidity and utility.

## Community

Join the BUK Protocol community to stay up-to-date on the latest news and updates:

- [Twitter](https://twitter.com/bukprotocol)
- [Telegram group](https://t.me/bukprotocol)
- [Discord](https://discord.com/invite/U24CDdFkqC)
- [LinkedIn](https://www.linkedin.com/company/bukprotocol/)
- [Docs](https://docs.bukprotocol.io/buk-protocol-v2)

## License

Buk Protocol is licensed under the [MIT License](https://chat.openai.com/LICENSE).
