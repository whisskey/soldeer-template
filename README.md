# Foundry Template

This is a template for Solidity projects that runs on top of Foundry. It is ready to use, so you can clone it and start building your Solidity projects right away.

## Usage

### Build

To compile your Solidity contracts, run:

```shell
forge build
```

### Test

To run the tests for your contracts, execute:

```shell
forge test
```

### Format

To format your Solidity code, use:

```shell
forge fmt
```

The formatter is preconfigured, and you can change its configuration in the `foundry.toml` file under the `fmt` section.

### Deploy

To deploy your contracts, make sure you have the `DEPLOYER_PK` and RPC URL environment variables set in your `.env` file. Then run the following command:

```shell
forge script script/Deploy.s.sol
```

## Dependency Management with Soldeer

To install dependencies using Soldeer, you can use the following command example:

```shell
forge soldeer install solmate~6.7.0
```

If you've just cloned the repository and want to download the pre-configured dependencies listed in `foundry.toml`, run:

```shell
forge soldeer update
```

## License

This project is licensed under MIT.
