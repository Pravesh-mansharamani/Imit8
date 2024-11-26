# Imit8 - A SocialFi dApp on Avalanche
Built by [Tolga Cohce](https://github.com/tgcohce) and [Pravesh Mansharamani](https://x.com/imthebigp) for Avax MBC Hackathon
<div align="center">
    <a href="https://www.loom.com/share/5c4c813f9b7b4301beb090d4af0acf8b">
      <p>Imit8: Expressing Emotions through Emojis - Watch Demo</p>
    </a>
    <a href="https://www.loom.com/share/5c4c813f9b7b4301beb090d4af0acf8b">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/5c4c813f9b7b4301beb090d4af0acf8b-dc2c529cfcefacd7-full-play.gif">
    </a>
  </div>

## Project Description
Imit8 is a dApp built on a custom Avalanche L1 blockchain. The platform leverages blockchain technology to gamify user interactions by assigning ratings to users based on imitating given emojis. The dApp rewards users with native tokens (IMIT) for participation. 

The aim for Imit8 is to be a SocialFi platform, where users have their picture taken to imitate a given emoji in order to elevate their mood. An ML model evaluates their performance and assigns a rating out of 5. Based on this score, users are rewarded with tokens. The user's photo is posted on the social wall, adding a social element to the platform, gamifying the experience, and enabling friendly banter & cpmpetition.

## Technical Overview

- **Custom Avalanche L1 Blockchain**: We used AvaCloud to deploy our own L1 devnet. This allowed us to create a fully custom chain tailored to the needs of our dApp.
- **Smart Contract**: A native token distributor smart contract is deployed on our custom L1, which facilitates sending our native IMIT tokens to a given address on the chain. The smart contract ensures secure and transparent token distribution.
- **Frontend**: Built with React.js, the frontend enables users to interact with the platform by connecting their wallets, adding the custom network, and participating in the emoji imitation game.
- **Backend with ML Integration**: The backend leverages a machine learning model to evaluate user-submitted photos and assign ratings based on how closely they imitate the given emoji.

## Features

1. **Wallet Integration**: Users can connect their wallets to interact with the Imit8 platform.
2. **Custom L1 Integration**: The platform operates on a custom Avalanche L1, ensuring low-cost and fast transactions.
3. **Emoji Imitation Game**: Users imitate emojis, and their performance is rated by an ML model.
4. **Social Wall**: User photos are displayed on a social wall to promote engagement and friendly banter.
5. **Token Rewards**: IMIT tokens are rewarded based on user performance, adding a financial incentive to the gamified experience.

## How to Get Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Pravesh-mansharamani/Imit8.git
   cd Imit8/frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Deploy the smart contract on your custom L1 devnet using Remix IDE or Hardhat.

5. Add the custom Avalanche L1 network to your wallet with the following details:
   - **Network Name**: Imit8
   - **Chain ID**: 1117256
   - **Token Symbol**: IMIT
   - **RPC URL**: `https://subnets.avacloud.io/f42c253d-a0d9-4326-b568-2ea514391459`

6. Interact with the platform by imitating emojis, earning IMIT tokens, and enjoying the social features!

## Acknowledgments

- **Avalanche AvaCloud** for enabling the creation of our custom L1 devnet.
- **OpenZeppelin** for smart contract standards.
- **React.js** for frontend development.
- **Machine Learning** for gamified photo evaluations.
