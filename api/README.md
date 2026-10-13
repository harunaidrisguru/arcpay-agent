ArcPay Agent
Send USDC on Arc mainnet by chatting. Say "pay ada 5" or "give ada ten dollars", confirm in your wallet, done.
How it works
Simple commands are parsed in the browser (free, instant).
Free-text messages go to /api/parse, where Claude turns them into a validated JSON command.
The agent never holds keys. Every payment needs your wallet's confirmation, and a per-payment limit applies.
Payments are ERC-20 USDC transfers on Arc mainnet (chain ID 5042)

