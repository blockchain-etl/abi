# abi
EVM public good - pull requests welcome for any ABI from any EVM

## repository structure

[raw](raw) - contains 1b prefixed (00..ff) tab-separated text files, which in turn contain:

- Column 1: Keccak-256 hash of the contract bytes
- Column 2: JSONL-formatted ABI

For example, see record `93134f51be7080424794d99461bad41972bc9917057454045972a1bfded8a2c8` in [raw/93.tsv](raw/93.tsv) for ETH Mainnet contract for USDC, deployed at `0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48`
