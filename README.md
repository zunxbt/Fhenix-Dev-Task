<h2 align=center> Fhenix Dev Task </h2>

## Join Discord
- First join [Fhenix Discord](https://discord.gg/fhenix-io)
- Visit `#🤖|bot-commands` and write `/quests` and select the popped up `/quests` option and then press `Enter`

![Img-1](https://github.com/user-attachments/assets/30f7abde-4ab0-4d7b-9b53-4101a7028e7e)

- You will see 10 different quests, here I will show how to do only dev tasks (`Quest 4`,`Quest 6`)

---

## Network Set Up
- Visit [Chainlist](https://chainlist.org/?testnets=true&search=Fhenix+Helium)
- Click on `Connect wallet` and then add the network in your preferred wallet (Metamask or Rabby or OKX)

---

## Faucet (Bridge)
- Right now you can get tFHE faucet by mining [here](https://get-helium.fhenix.zone/)
- You can also get tFHE by bridging from the below website

1. [Native Bridge](https://bridge.helium.fhenix.zone/) [Sepolia Ethereum -> Fhenix Helium]
2. [Pheasant Bridge](https://testnet.pheasant.network/) [Many other testnet networks supported]

## Quest 4 : Deploy Contract on Fhenix
- Visit [Remix Website](https://remix.ethereum.org)
  
![Img-2](https://github.com/user-attachments/assets/f186a74b-3287-478a-a14b-7ca267aa9f18)

- Give it any name but at the last part u need `.sol` as this is a solidity file [Example : `zun.sol`] and then press `Enter`
- After that you will an interface like this 

![image](https://github.com/user-attachments/assets/b9a9a624-2733-4393-b014-b4e995e01c0c)

- You need copy the below mentioned codes and paste it there

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.26;

contract SimpleStorage {
    uint256 public storedData;

    function set(uint256 x) public {
        storedData = x;
    }

    function get() public view returns (uint256) {
        return storedData;
    }
}
```
- Click on `Solidity Compiler` icon

![Img-4](https://github.com/user-attachments/assets/1e25afbb-183a-4630-bab4-887cfd6a940d)

- Then click on `Compile YOUR_CONTRACT_NAME.sol`

![Img-5](https://github.com/user-attachments/assets/aa054f1a-94e4-4fec-b7e9-989002752728)

- Afterthat, click on `Deploy and run transactions` icon in the left slide bar

![Img-5](https://github.com/user-attachments/assets/8e5a154a-e415-4805-b1d3-5e157b990b04)

- Open your wallet and then switch to `Fhenix Helium` network if you have not switched it yet
- Now choose `Injected Provider` in environment section and then choose your wallet
- Then click on `Deploy` button to deloy a contract

![Img-6](https://github.com/user-attachments/assets/39a4b675-0a83-4f1c-9948-3d56f5f41ec4)

- Congrats, you have successfully deployed a contract on `Fhenix Helium`
- You can check your deployed contract address here

![Img7](https://github.com/user-attachments/assets/74fdd356-6104-4c6e-8574-bfa32227b41b)


- Right now, you can deploy max 5 contract and can earn 150 points
- To deploy more contracts,click on `Deploy` button again and again
- Do this process 4 times to deploy 4 contracts

## Quest 6 : Contract Verification
- If you use above contract code, It will be verified automatically, You don't need to do anything

![image](https://github.com/user-attachments/assets/6131b98d-c88e-4308-ae52-acbfddb0ef3f)

- Also, there contract verification tool is defective, if you use other than the above code, your contract will not be verified now
