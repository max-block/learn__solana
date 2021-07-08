--> Install / upgrade on macOS
sh -c "$(curl -sSfL https://release.solana.com/v1.5.8/install)"

--> Links
https://explorer.solana.com/
https://solscan.io/
https://solanabeach.io

--> Generate a new account
clear && solana-keygen new --no-passphrase -f && cat ~/.config/solana/id.json && echo

--> RPC urls
https://api.testnet.solana.com
https://api.mainnet-beta.solana.com