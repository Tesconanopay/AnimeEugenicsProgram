# AnimeEugenicsProgram
A staking contract which allows users to stake their high quality genetic specimen NFT to allow other users to pay to mint Warrior Spirits for use in the upcoming Limit Break games. Basically if your female is low-tier and you want to improve the genetic quality of your NFT - use this program.

### Testing
Tests for this contract run on a fork of mainnet which requires you to provide an RPC.  There are shell scripts in the `test` folder which facilitate these if you provide the RPC in a `.env` file.

1. Create a `.env` file in the root of the project with `ETH_RPC_URL=` and assign an RPC link to this using alchemy, infura or your RPC provider of choice.
2. To run tests, run `./test/test-mainnet.sh`
3. To run tests with verbose outputs run `./test/test-mainnet-verbose.sh`
