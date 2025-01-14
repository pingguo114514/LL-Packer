# LL-Packer

基于[LLBDS Packer](https://github.com/FTS427/llbds_packer)二次开发而成

一个使用Lip打包任意版本的 LeviLamina 和 LegacyScriptEngine **(不附带BDS)** 的 Github Action

## 食用方法

+ ### 自己打包

点击右上角的`Use this template`以此仓库为模板在您的帐户下建立一个新仓库

打开 `Action` 页面

点击右侧的 `Pack LeviLamina&LegacyScriptEngine`

打开 `Run workflow` 填入你需要的 LeviLamina 版本号以及 LSE 版本号

点击绿色的 `Run workflow` 后，等待 2-5 分钟，期间你可以关掉网页。随后，仓库会出现一个名为`LeviLamina-x.x.x&LSE-x.x.x`的 Release ， 下载`LeviLamina-x.x.x with LSE-x.x.x.zip`并解压即可

**注意:如果压缩包小于75MB，很可能是某样东西未成功安装，请删除该 Release 并重新安装**

+ ### 下载打包好的整合包

前往[Github Release](https://github.com/pingguo114514/LL-Packer/releases)或[MineBBS](https://www.minebbs.com/resources/levilamina-legacyscriptengine.7230/)下载

## Run workflow页中选项解释

| 名称                          | 解释                  |
| ---------------------------- | ---------------------|
| `LeviLamina version`         | 安装的`LeviLamina`版本 |
| `LegacyScriptEngine version` | 安装的`LSE`版本        |

## 贡献

如果您有任何问题，请开启一个 issue 来讨论。

欢迎 PR。

## 鸣谢

+ [ZH-Server/ll_easier](https://github.com/ZH-Server/ll_easier)
