# Shareable NFT Access and Dynamics NFT
### Setup


In the `minter/src/config/setup.ts` file, we define several key configurations for interacting with the Mintbase platform. This setup is crucial for ensuring that our application communicates correctly with Mintbase smart contracts.

## ENV Variables

To customize these configurations for different environments, you can set the following environment variables in your `.env` file:

`NOTE: the env variables need to have the NEXT_PUBLIC_ on the variable name due to be available for the browser to process`

- `NEXT_PUBLIC_PROXY_CONTRACT_ADDRESS`: Your proxy contract address on Mintbase.
- `NEXT_PUBLIC_MINT_CONTRACT_ADDRESS`: Your mint contract address on Mintbase.
- `NEXT_PUBLIC_NETWORK`: The network you want to interact with (`"testnet"` or `"mainnet"`).

## Run Project
after that you can run
```
pnpm install
```
and

```
pnpm dev
```

## Extending

This project is setup using Next.js + @mintbase/js + shadcn ui + react hook form
You can use this project as a reference to build your own, and use or remove any library you think it would suit your needs.

![Alt text](relative%20shareable-nft-access-dynamics-nft/images/Login.png?raw=true "Login")
![Alt text](relative%20shareable-nft-access-dynamics-nft/images/Dashboard.png?raw=true "Dashboard")
