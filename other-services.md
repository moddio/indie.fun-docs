# Indie.fun Additional Services

In addition to token creation and fundraising, indie.fun offers several optional tools and services to help you bring more utility, engagement, and growth to your project. These are designed to be plug-and-play — no extra coding or setup required.

---

## Indie Pay

**Accept your token for products, perks, and payments — on your site or in your game.**

[Indie Pay](https://pay.indie.fun) is a plug-and-play payment layer that allows you to accept your token with minimal setup. Whether you're selling digital goods, managing an online storefront, or integrating token-based payments into a game, Indie Pay provides the infrastructure to handle transactions, token holder gating, and real-time triggers.

---

### Overview

Indie Pay enables you to:

- Accept payments in your token, SOL, or USDC
- Automatically route payments to your designated treasury wallet
- Define token holder tiers for discounts or access control
- Track and manage sales across all products
- Integrate real-time payment data via webhooks and API

---

### Merchant Use Case

If you're building a storefront, membership platform, or selling digital/physical products:

- Create a merchant profile and link your token
- Add product listings with static or dynamic pricing
- Accept payments using your token or USDC (automatically converted to your token)
- Offer token-based discounts or gated perks
- View transactions, configure discounts, and manage inventory from the dashboard

Example: You run a merch store for your project and want holders of 10,000+ tokens to get 25% off. Indie Pay handles both the payment and the discount logic.

---

### Game Developer Use Case

Game developers can integrate Indie Pay directly into their games to create token-based economies without building their own payment backend.

Use cases include:

- Selling in-game items, cosmetics, or upgrades using your token
- Unlocking access to premium content or game modes
- Creating tiered experiences (e.g., Silver/Gold status based on token holdings)
- Triggering real-time in-game effects based on payment confirmation

Developers can use the API and webhooks to:

- Retrieve unprocessed payments (`GET /api/payments`)
- Mark purchases as fulfilled after delivery (`PUT /api/payments`)
- Monitor token trading activity (`GET /api/swaps`)
- Receive notifications when payments are processed (webhooks)

Example: A player purchases a battle pass using your token. The game listens for the payment webhook and automatically unlocks the pass in-game.

---

### Key Features

#### Create a Merchant

- Name your merchant and provide the token's contract address that you want to accept as payment
- Each merchant can have multiple products and token-based settings
- You can create and manage multiple merchants under one account

#### Add Products

- Create product listings or items you want to sell (digital or physical)
- Set static or dynamic pricing in your token or USDC
- Customers can pay with your token, SOL, or USDC
- Payments are automatically converted and sent to your treasury wallet

#### Token Holder Tiers

- Configure token-based discounts or access restrictions
- Define tiers (e.g., Bronze, Silver, Gold) based on wallet holdings
- Tiers can be used to incentivize holding and reward loyalty

#### Webhooks

- Receive real-time notifications when a payment is received
- Ideal for automating in-game item delivery, access unlocks, or membership systems

#### API Access

- Secure endpoints for retrieving and managing payment data
- Supports integration into custom apps, games, and dashboards
- Common endpoints include:
  - `GET /api/payments`
  - `PUT /api/payments`
  - `GET /api/swaps`

---

### Who Should Use Indie Pay

Indie Pay is built for:

- Game developers integrating token economies
- Merchants selling digital or physical products
- Communities offering gated perks to token holders
- Any project launching a token and looking for immediate utility

Indie Pay offers a complete, flexible infrastructure for adding utility to your token without requiring custom backend development.

---

## Competition Add-On (BountyHunt.fun)

**Host token-powered competitions to drive engagement and utility.**

The Competition Add-On, [BountyHunt.fun](https://bountyhunt.fun), was built by our team to allow you to create live competitions for your community using your Indie.fun token. These challenges are time-limited, reward-based, and fully automated. They can be embedded directly into your Indie.fun project under the **Leaderboard** tab.

---

### Overview

BountyHunt lets you:

- Create skill-based competitions that use your token or SOL
- Set a prize pool and entry fee
- Automatically distribute rewards to top players
- Display a live leaderboard directly on your Indie.fun project page
- Integrate your game using a simple score-submission API

Competitions are designed to be fast to launch and easy to manage, with no additional development required.

---

### How It Works

You define the game URL, entry fee, prize pool, and reward logic (e.g. Top 10 players get paid). Competitions run on a start/end schedule, and players must achieve a minimum score to qualify for rewards. All prize handling and distribution is automated through an embedded wallet system.

Each competition can be connected to your game using the provided API. You can submit player scores programmatically to update the leaderboard in real time.

---

### Integration with Indie.fun

Once your competition is created on BountyHunt.fun, you can embed it in your Indie.fun project by pasting the competition URL into the **Leaderboard** tab of your project dashboard. This will add a live leaderboard tab to your project page for players to track rankings and participate.

---

### Use Cases

- Launch competitive events during your token mint or release
- Add instant utility and interactivity to your token
- Run community tournaments and reward active players
- Create time-limited campaigns to boost visibility and engagement

Competitions are a powerful way to provide utility to your token and give players a reason to return, compete, and participate.

---

## Trench Game

By adding a **Trench Game**, you can add instant utility to your token with a playable game:

- Instantly deploy a playable minigame linked to your token
- Use your token as in-game currency, reward, or entry fee
- Add real-time speculation and utility while your token is trading
- Embedded directly into your Indie.fun project page
- No technical setup required — just plug in your token and go live

---

## More Coming Soon

We're constantly adding new utilities and integrations to make your token launch more successful and engaging.
