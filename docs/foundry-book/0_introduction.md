# Foundry 简介

Foundry是一个快速、便捷和模块化的智能合约开发的框架/工具链, 使用Rust语言开发, 最大的特点是除了合约开发之外, 测试、部署、脚本和交互都用Solidity一种语言完成. 

Foundry由Paradigm开发维护([官网](https://github.com/foundry-rs/foundry)), 由以下几部分组成:

1. Forge: 智能合约的测试框架
2. Cast: 和区块链交互、发送交易、模拟交易、读取链上数据等
3. Anvil: 本地运行的以太坊节点, 类似于Ganache、Hardhat Network
4. Chisel: 命令行中的一个快速、详细的Solidity的交互式解释器(REPL)


## 优点
- 对智能合约开发者来说, 不再需要学习和使用其他语言
- 测试运行速度大幅快过Hardhat等框架
- 有多个模块化的配合开发的工具(Cast, Anvil等)