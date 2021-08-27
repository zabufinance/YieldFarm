# Zabu Finance Farming Contract elements:

1. Zabu Token
- Zabu Token Contract is a fork of BAO Token (on Ethereum), with supply capped at 5 billions. All 5 billions was transferred to Zabu Farm for Distribution.
- Ownership was renounced to 0x0.

2. Zabu Farm
- Zabu Farm is a fork of Pancakeswap's Masterchef with some innovations: instead of mint() rewards and send to stakers, it transfer() rewards inside the contract to stakers.
- Zabu Farm Owner was set to Timelock.

3. Timelock
- Timelock was set as owner of Zabu Farm contract to make sure all actions are under delay of 12 hours.

Token Addresses on C-Chain Avalanche Mainnet:

ZABU Token Address: 0xDd453dBD253fA4E5e745047d93667Ce9DA93bbCF
Zabu Farm Contract Address: 0xf61b4f980A1F34B55BBF3b2Ef28213Efcc6248C4
Timelock (Owner of Zabu Farm):
0xEC9afD2De9ECAC7f8820BEe6f5B80ae614B6D1aa
