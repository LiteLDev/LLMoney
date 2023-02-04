# LiteLoaderMoney
[![status](https://img.shields.io/github/actions/workflow/status/LiteLDev/LLMoney/build-cmake.yml?style=for-the-badge)](https://github.com/LiteLDev/LLMoney/actions")  
[English](README.md) | 简体中文  
[LiteLoaderBDS](https://github.com/LiteLDev/BDSLiteLoader)的经济核心

# 用法

| 命令 | 说明 | 权限等级 |
| --- | --- | --- |
| /money query [玩家] | 查询你自己/他人的余额 | 玩家/OP |
| /money pay <玩家> <数量> | 转账给某人 | 玩家 |
| /money set <玩家> <数量> | 设置某人的余额 | OP |
| /money add <玩家> <数量> | 添加某人的余额 | OP |
| /money reduce <玩家> <数量> | 减少某人的余额 | OP |
| /money hist | 打印流水账 | 玩家 |
| /money purge | 清除流水账 | OP |
| /money top | 余额排行 | 玩家 |
| /money_s | 带有选择器支持的指令 | 玩家 |

# 配置文件

## LLMoney
```jsonc
{
    "language": "en-us", //语言，改为zh-cn为中文
    "def_money": 0, //默认金钱数
    "pay_tax": 0.0 //转账税率
}
```
