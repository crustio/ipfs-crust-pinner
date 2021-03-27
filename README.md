# Crust IPFS Pinner

This repo shows how to decentralized pin your site/file to IPFS by using [ipfs-upload-action](https://github.com/crustio/ipfs-upload-action) and [ipfs-crust-action](https://github.com/crustio/ipfs-crust-action).

## 🎉 Join to play

Please refer [template.yml](./.github/workflows/template.yml) to write your own Github Deploy workflow!

## 📌 Samples

- [Uniswap Interface](https://github.com/Uniswap/uniswap-interface): Using [uniswap-interface.yml](./.github/workflows/uniswap-interface.yml) to pin Uniswap on Crust;
- *More*

## 📄 Description

Crust IPFS Pinner's work flow is shown as below

![pinner flow](./docs/img/pinner-flow.png)

This flow consists of 2 components:

- **IPFS Uploader**: Replaceable action, can be replaced with all IPFS upload actions, like [Crust IPFS Uploader](https://github.com/crustio/ipfs-upload-action), [Pinata IPFS Uploader](https://github.com/anantaramdas/ipfs-pinata-deploy-action), [IPFS Cluster Uploader](https://github.com/marketplace/actions/add-to-ipfs) and other [uploaders](https://github.com/marketplace?type=actions&query=ipfs).
- **Crust Pin**: [Crust IPFS Pin](https://github.com/crustio/ipfs-crust-action), place a storage order on Crust Chain and decentralized pinned by Crust IPFS nodes.

## 👑 Contribution

Feel free to dive in! [Open an issue](https://github.com/crustio/ipfs-crust-pinner/issues/new) or send a PR.

To contribute to Crust in general, see the [Contribution Guide](https://github.com/crustio/crust/blob/master/docs/CONTRIBUTION.md).

## ☎️ Contact

Any questions, please contact:

1. Emailing <hi@crust.network>
2. Joining Crust [Discord Channel](https://discord.gg/D97GGQndmx)

## License

[MIT](LICENSE) @ Crust Network
