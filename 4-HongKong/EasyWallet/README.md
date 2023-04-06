# Easy-Wallet

## Proposal
Generally speaking there are currently three main types of crypto wallet implementations on the market: Externally Owned Account, Account Abstraction, and Multi-Party Computation. They all provide acceptable levels of security, while all come with their own flaws. AA being more recently introduced, is still in its early stages, and has compatibility issues. EOA and MPC both offer excellent compatibility. However, EOA requires the user to remember randomized mnemonic – which is quite a hassle, and MPC is essentially an upgraded version of full custodial solution, which would mean users could found it difficult to recover their wallets by themselves. 

We are proposing a novel solution in wallet implementation which aims to improve the user friendliness of traditional EOA wallets by allowing customized mnemonic, all the while maintaining the level of security and compatibility that an EOA wallet offer. To achieve such goal, we will modify the process in which an EOA wallet generates mnemonic by creating a custom mapping of words on a per-user basis. The mapping, in the form of a file, would then be stored by the user himself. This way a user can only retrieve his wallet seed with both his (customized) mnemonic and his mapping file. The user would only need to securely store his customized mnemonic words – rather than completely senseless word combinations -- while being able to store the mapping file in unsafe locations like cloud drives.

For a more detailed plan, please refer to:
https://lizard-celery-a7b.notion.site/HAPATHON-2023-8b2fd7382d0c48378a464e79272e01c3

### Code Link
https://github.com/Adamlixi/Easy-Wallet

### Demo
https://www.youtube.com/watch?v=psAW50W__hc