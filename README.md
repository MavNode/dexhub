# 🚀 DEXHub - Shido DEX Explorer

**DEXHub** is the premier DEX (Decentralized Exchange) explorer built specifically for the Shido blockchain ecosystem.

## 📋 Features

- 📊 **Real-time Token Tracking**: Monitor token prices, volume, and market cap
- 🔄 **Transaction Analytics**: Track recent swaps
- 🔐 **Contract Verification**: View verified token contracts and their details

## 🔥 Trending Tokens by Volume

Track the hottest tokens on the Shido ecosystem with real-time data on price movements, market cap, and trading volume.

## ⭐ Featured Tokens

Discover hand-picked featured tokens verified on the Shido blockchain, including native tokens, meme coins, and ecosystem projects.

## 🤝 Contributing

We welcome contributions to improve DEXHub! Adding your token to the platform is straightforward and helps increase your project's visibility in the Shido ecosystem.

### Steps to Add Your Token

1. **Fork the Repository**
   ```bash
   git fork https://github.com/MavNode/dexhub.git
   cd dexhub
   ```

2. **Add Your Token Logo**
   - Place your token logo (PNG format, 512x512 recommended) in the `/images` directory
   - Name it `project.png` (or use a descriptive name)

3. **Update assets.json**
   - Open `/public/assets.json`
   - Add your token information using the following template:

   ```json
   {
     "name": "Your Token Name",
     "symbol": "TOKEN",
     "supply": "1000000000",
     "address": "0x...",
     "decimals": 18,
     "logo": "https://raw.githubusercontent.com/MavNode/dexhub/refs/heads/main/images/your-token-logo.png",
     "priceInfo": {
       "poolAddress": "0x...",
       "baseToken": {
         "symbol": "WSHIDO",
         "address": "0x8cbaffd9b658997e7bf87e98febf6ea6917166f7",
         "decimals": 18
       }
     },
     "website": "https://yourtoken.com",
     "X": "https://x.com/yourtoken",
     "telegram": "https://t.me/yourtoken",
     "verified": true,
     "cmcUrl": "https://coinmarketcap.com/currencies/your-token/",
     "coingeckoUrl": "https://www.coingecko.com/en/coins/your-token",
     "lockUrl": "https://gempad.app/locks/liquidity?id=...",
     "lockTimer": "2025-06-05T08:00:00Z"
   }
   ```

4. **Submit Pull Request**
   - Commit your changes: `git commit -m "Add [TOKEN_NAME] token"`
   - Push to your fork: `git push origin feature/add-[token-name]`
   - Create a Pull Request to the main repository

### Pull Request Guidelines

- Use a clear and descriptive title
- Include all required token information
- Ensure the logo is properly formatted and sized
- Verify all URLs are working and accurate
- Fill out the PR template with all requested information

## ✅ Example Token Submission

```json
{
  "name": "Kensei",
  "symbol": "KENSEI",
  "supply": "50000000000",
  "address": "0xfb889425b72c97c5b4484cf148ae2404ab7a13e7",
  "decimals": 18,
  "logo": "https://raw.githubusercontent.com/MavNode/dexhub/refs/heads/main/images/kensei.png",
  "priceInfo": {
    "poolAddress": "0x2f4cdf4ad2203d5bca9ccb5485727d89603e2e39",
    "baseToken": {
      "symbol": "WSHIDO",
      "address": "0x8cbaffd9b658997e7bf87e98febf6ea6917166f7",
      "decimals": 18
    }
  },
  "website": "https://kenseishido.com",
  "X": "https://x.com/kenseishido",
  "telegram": "https://t.me/kenseishido",
  "verified": true,
  "cmcUrl": "https://coinmarketcap.com/currencies/kensei/",
  "coingeckoUrl": "https://www.coingecko.com/en/coins/kensei",
  "lockUrl": "https://gempad.app/locks/liquidity?id=63&network=Shido",
  "lockTimer": "2025-06-05T08:00:00Z"
}
```

## 🙋‍♂️ Support

- **Issue Tracker**: [GitHub Issues](https://github.com/MavNode/dexhub/issues)
- **Telegram**: [@DEXHub_Support](https://t.me/MaverickCryptoz)
- **Website**: [https://dexhub.mavnode.io](https://dexhub.mavnode.io)

## 🌟 Acknowledgments

Built with ❤️ for the Shido ecosystem. Special thanks to all contributors and the Shido community for their support.

---

**Note**: Make sure to verify all token information before submission. Incorrect or outdated information will delay the review process.
