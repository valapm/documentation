## What is a prediction market?

Prediction markets are betting markets that enable participants to trade and speculate on the probability of event outcomes.
Through monetary incentives they aggregate information about the future, making it accessible to everyone.

## How do markets work?

All trades happen on-chain and are managed by an automated market maker implemented in Bitcoin Script, namely the logarithmic market scoring rule (LMSR).
You can inspect the script code [here](https://github.com/valapm/boilerplate/blob/master/contracts/valaPM.scrypt)

## When will a market resolve?

Whenever the market oracle decides to resolve it. The conditions for that can be laid out in the market details.
