# 这是什么

这是一个宠物领养的 Web3 App。来自 Truffle 官方的教程 https://trufflesuite.com/guides/pet-shop/ 。这里的项目代码是完成了这个教程后的完整程序。

你可以按照原本的教程一步步进行实验，也可以直接下载这里的代码，直接体验最终的结果。

我使用这个仓库来向学生快速体验一个简单的 Web3 App 的工作流程以及背后的原理。

# 实验准备

-   启动 Ganache，并创建一个临时的以太坊测试网络
-   配置 MetaMask 连接到这个网络，并导入其创建的账号（稍后会用到）

# 实验步骤

```
# 下载代码到本地
git clone https://github.com/Jianru-Lin/pet-shop.git

# 进入目录
cd pet-shop

# 安装依赖
npm install

# 启动
npm run dev
```

接下来浏览器会自动弹出，可以试着在这个页面里连接上我们配置好的 MetaMask 并且尝试领养宠物了。

这个过程会触发智能合约交易，可以通过 Ganache 观察到整个过程。

尝试去理解整个系统是怎么运行的。
