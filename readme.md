# Advancify

In order to test the app, you need to generate your own openai token and verbwire token. For privacy reasons, I have removed those token from the code

## Introduction 

Do you ever struggle to stay motivated to achieve your goals? Do you need some extra incentive to push yourself toward success?  Almost 78% people fail to maintain consistency while starting a new habit and quit midway If so, then I have an exciting new app that will help you achieve your goals and earn some extra cash while doing it.

In Advancify,  we combine the power of blockchain with the thrill of achieving your aspirations. Each step you take towards success will be immortalized as a unique NFT, making your journey truly exceptional and rewarding.

## Core idea

You choose a challenge to join by investing a specific amount of money. You set a goal for yourself and work towards achieving it within the challenge period. If you successfully complete your goal, you'll receive your initial investment back plus a portion of the common pool money. But if you fail to complete your goal, your invested money will be reduced, and the money goes to the common pool.
At the end of the challenge, the common pool money is randomly awarded to one lucky winner who completed their goal. It's a win-win situation! You'll either achieve your goal and earn some extra cash or motivate yourself to try harder next time.

This app not only incentivizes you to achieve your goals but also creates a supportive community of individuals who are striving towards the same objectives. You can connect with others, share your progress, and motivate each other to achieve your goals together.

## How does it work? 

1. Create and Join Battles:  In Advancify, each challenge is a battle and in each battle you defeat a monster: Users can initiate a battle or join existing ones. Each battle comes with a specific goal, duration, and a bet amount to be pledged by all participants.
2. Challenge Accepted: Players lock in their commitment by pledging the bet amount. The bet amount serves as a financial incentive to stay committed, making the battle even more thrilling and meaningful.
3. Mint Your Achievements: Every day you submit image proofs of completing your tasks, and guess what? Each proof is minted as an exclusive NFT on the blockchain! Your achievements become valuable digital assets, showcasing your progress like never before.
4. Rewarding the Victors: At the end of the battle, participants who successfully completed the challenge wins the pledged bet amounts from those who didn't. 

## How blockchain is used
- Whenever a new challenger/battle is created the app creates a new token
- Whenever a user checks in for the daily challenge progress update, it mints the image added by the user as proof for completing the challenge
- All the minted NFT's can be viewed in the /nft route
- Once a challenge is completed, 1 person is randomly selected as the winner and the fund is withdrawn from the smart contract to the user
- Users can also exchange NFTS

## The Blockchain Advantage:
1. Immutability: With blockchain, your NFTs are forever etched in history, representing your dedication and accomplishments. No alterations, no doubts, just undeniable proof of your journey.
2. Enchanced security; Blockchain provides an added layer of security to the app. It can enable secure and tamper-proof transactions by creating a distributed ledger that records all transactions made within the app. The decentralized nature of blockchain ensures that no single entity can alter or manipulate the records, making it a secure platform for users to join challenges and make transactions.
3. Ownership and Value: Each NFT you earn is a testament to your hard work and commitment. As unique digital assets, they hold inherent value and can even be traded in the blockchain ecosystem.

## How I built it
Django, Verbwire, chatgpt, bootstrap, javascript
Verbwire is used for implementing the NFT blockchain. It provides a REST interface and omnichain support for any blockchain
I have used bsc-testnet as my test network


