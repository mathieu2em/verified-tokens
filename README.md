## How to verify your token

1. Create Pull Request with following information to `tokens.json` file:

```ts
{
  "$policyId": {
    "project": string,
    "categories": string[], // some of the following: "DeFi", "RealFi" |  "GameFi" |  "Meme" |  "Bridge" |  "Metaverse" |  "Wallet" |  "NFT" |  "Oracle" |  "AI" |  "Launchpad" |  "DAO" | "Other"
    "socialLinks"?: {
      "website"?: string,
      "twitter"?: string,
      "discord"?: string,
      "telegram"?: string,
      "coinMarketCap"?: string,
      "coinGecko"?: string
    }
  }
}
```

If you don't know how to create pull request, create an issue with above information and our team will update. A PR will be processed faster.

2. Post your policy ID on Twitter or display your policy ID on your landing page.
3. Our team will verify and approve in first-in-first-out order.

Advice : Please make sure to read this page before applying for token registration https://docs.minswap.org/faq/token-launching-and-farming/1.-token-listing
