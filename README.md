# 🥞 Pancakeswap/Uniswap Prediction Bot v2.03 🥞

![alt PancakeSwap Frot](png_3.jpeg)




## ℹ️ Information 

This bot wins almost evey 5 minute BNB-USD option on PancakeSwap Prediction.

**Scroll down for more Details.**

## 📈 Updates 

[Available soon]: supports [Uniswap] & [ApeSwap]. Change strategy.

[Update 2.03]: Fixed some Bugs. Update 2.1 Available soon. 

[Update 2.02]: Now supports Strategy Choice (start the bot with `--exp` flag) | Now it works with PancakePredictionV2.

[Update 2.01]: Now supports [Candle Genie](https://candlegenie.io/prediction) BTC Price Option

![alt PancakeSwap Prediction Bot-Winner Screenshot](png_1.png)
![alt Candle Genie Bot-Winner Screenshot](png_2.png)

## 💡 How to use

1. Rename **.env.example**file to **.env**
2. Provide your private key to **.env** PRIVATE_KEY field (PLease let me know in Issues section if you are having trouble in finding your wallet's private key)
3. Enter betting amount in BET_AMOUNT field (In BNB)
4. Install dependencies `npm i` or `yarn` **If you dont know How to Use npm, Use this!**          https://phoenixnap.com/kb/install-node-js-npm-on-windows
5. Start THIS BEAST `npm run start` or `yarn start`
6. Enjoy winning!



P.S. If you want to play Candle Genie instead of Pancake, start THIS BEAST with `npm run cg` or `yarn cg`

P.S.S. NEW STRATEGY: Start THIS BEAST `npm run start -- --exp` or `yarn start --exp`, to use with Candle Genie – `npm run cg -- --exp` or `yarn cg --exp`

### Feel free to contribute. Good Luck


## Strategy

The strategy can be found in [src/lib.ts](https://github.com/AssaEmpireToken/Pancakeswap-Prediction-Bot-NEW-v2.03/blob/main/src/lib.ts#L38). The base strategy looks at the bull and bear total bet amounts at the time the bet is made.

It bets bear if (bull > bear and bull / bear < 5) OR (bull < bear and bear / bull > 5) otherwise bet bull.

Experimental option just flips the bets.

## ⚠️ Beware of clones!!

Beware of forks. I do not give any guarantee that the fork may turn out to be a scam. I'm coding this stuff on a pure open source. I do my best to publish       constant updates and bug fixes. the bot has a very small tax in the claim function, so we both win. At the same time you support me, this project and the following projects. 

Love you all and thank you to use my Script ☺️❤️


## 🌈 Disclaimer

All investment strategies and investments involve risk of loss.
**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not,
and should not be construed as, a recommendation or as a guarantee of
any specific outcome or profit.
By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.

