# Getting Started with Lit SDK and Candide AbstractionKit

This is a simple example repository for getting started with a browser implementation of the Lit SDK and Candide AbstractionKit. The specifics of what this implementation does can be found in the docs pages:
- [Add a Google Account as Safe Recovery Method using Lit (Guide 1/2)](https://hackmd.io/TeFu2k56SgG4HCQQFZOqig)
- [Recover a Safe Account with Google using AbstractionKit (Guide 2/2)](https://hackmd.io/@sednaoui/BJiTAzG5C)

## Environment Variables

The following environment variables are required for the application to run properly:
- VITE_CHAIN_ID
    - The chain ID of the network you are using. Currently, set to Sepolia (11155111).
- VITE_BUNDLER_URL
    - The URL of the Candide Bundler RPC endpoint.
- VITE_OWNER_PRIVATE_KEY
    - Private key of the owner of the Smart Account.
- VITE_PAYMASTER_URL
    - Paymaster URL for Candide. This can be requested from their [Discord](https://discord.com/invite/AePAhztPJz).
- VITE_JSON_RPC_PROVIDER
    - JSON RPC provider URL for the network you are using. You can get one from [Alchemy](https://www.alchemy.com/).
- VITE_OWNER_PUBLIC_ADDRESS
    - Public address of the owner of the Smart Account.
- VITE_NEW_OWNER_PUBLIC_ADDRESS
    - Public address of the new owner of the Smart Account.
- VITE_LIT_API_KEY
    - API key for Lit Protocol Relayer. You can request them [here](https://docs.google.com/forms/d/e/1FAIpQLSeVraHsp1evK_9j-8LpUBiEJWFn4G5VKjOWBmHFjxFRJZJdrg/viewform).

## Using This Repository

After downloading this repository, you will need to install the necessary dependencies and run the environment setup with the following commands:

```
yarn install
```
```
yarn run dev
```

Afterward, your terminal should inform you that the application is being displayed at `http://localhost:5173/`. After logging in with (and verifying) your Google account, 



