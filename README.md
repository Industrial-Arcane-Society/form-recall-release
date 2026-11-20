# FormRecall 更新分发

完整安装包与便携包在 [FormRecall Releases](https://github.com/Industrial-Arcane-Society/form-recall/releases) 下载。

这里提供应用内更新使用的签名频道清单和按版本归档的 OTA。应用可选择 Alpha、Beta、RC 或 Release。对应清单分别为 `channels/alpha.json`、`channels/beta.json`、`channels/rc.json` 和 `channels/stable.json`。每个目标版本最多发布同一渠道最近五个旧版本的直达 OTA。

**Publish update channel** 定时同步主仓库已发布的版本，也可以手动选择频道和版本重试。完整便携包和 OTA 通过校验并可下载后，工作流才更新频道清单。更新器源码和构建脚本位于 [主仓库](https://github.com/Industrial-Arcane-Society/form-recall)。
