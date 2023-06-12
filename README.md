# Decentralized Finance 

Welcome to defi project, A Decentralized Bank Web Application which Runs on Dinfinity's ICP Blockchain.

If you want to see the working of the project, you might want to try the following commands:

```bash
cd dbank/
dfx help
dfx config --help
```

## Running the project locally

##To start the BackEnd:
```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://localhost:8000?canisterId={asset_canister_id}`.

##To start the FrontEnd:

```bash
npm start
```

Which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 8000.
