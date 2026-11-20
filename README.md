# FormRecall 更新分发

完整安装包与便携包在 [FormRecall Releases](https://github.com/Industrial-Arcane-Society/form-recall/releases) 下载。

本仓库的每个版本提供一份签名更新清单和 OTA 附件。附件使用 `FormRecall-OTA-v来源_v目标-win-x64.zip`。内容相同时共享一个附件，适用来源列在发布说明和清单里。

应用可选择 Alpha、Beta、RC 或 Release，分别读取 `channels/alpha.json`、`channels/beta.json`、`channels/rc.json` 或 `channels/stable.json`。测试版从发布顺序上最近的八个可升级测试版计算差分。

**Publish update channel** 定时同步主仓库发布的版本，也可手动选择频道和版本。完整包和 OTA 通过校验后才更新渠道清单。首次使用新格式时，请用主仓库的完整包升级启动器。