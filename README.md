# ModifierDataset
The dataset of 62,464 smart contracts with modifiers used in our ISSTA'23 paper

**Beyond “Protected” and “Private”: An Empirical Security Analysis of Custom Function Modifiers in Smart Contracts**

Paper link and bib reference: link

```
@INPROCEEDINGS{SoMo2023,
  author = {Fang, Yuzhou and Wu, Daoyuan and Yi, Xiao and Wang, Shuai and Chen, Yufan and Chen, Mengjie and Liu, Yang and Jiang, Lingxiao},
  booktitle = {Proc. ACM ISSTA},
  title = {Beyond ``Protected'' and ``Private'': An Empirical Security Analysis of Custom Function Modifiers in Smart Contracts (To appear)},
  year = {2023}
}
```

##  How to use the dataset?

- Directly obtain the contract address from the `dataset` file under the root dir of this repo.
- Fetch contract source code via [EtherScan](https://etherscan.io) API.
- Note that we have confirmed that all the contract source code is publicly available on `etherscan.io`

### How to obtain vulnerable contracts?

For ethics considerations, we would not disclose the details of the vulnerabilities as we declared in the paper. However, to facilitate the comparison with `SoMo`, we make the vulnerable contract list **on request**. Please send an email to the corresponding author for the request.
