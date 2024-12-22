# AllStream Depin
挖掘数据，助力 AI，赚取奖励，加入 Stream AI 革命

![alt text](image-2.png)

- 网站：[https://app.allstream.ai/](https://app.allstream.ai/index?referralCode=FlGQxaTO)
- Twitter/X：[ @allstream_ai](https://x.com/allstream_ai)

## 功能

- **自动创建连接**
- **支持多账户**
- **支持代理**，格式 `http://ip:port` 或 `http://username:password@ip:port`

## 必要条件

- **Node.js**：确保已安装 Node.js。
- **NPM**：确保已安装 npm。
- **AiStream ID**：按以下步骤获取
  - 在此创建 AiStream： [https://app.allstream.ai/](https://app.allstream.ai/index?referralCode=FlGQxaTO)
  - 使用 F12 打开开发者工具，如果你已登录，找到网络中的 `MyInfo` 并复制你的 ID。
   ![uid](image-1.png)

## 安装步骤

1. 克隆代码仓库：
   ```bash
   git clone https://github.com/Zlkcyber/streamAi.git
   cd streamAi
   ```

2. 安装依赖：
   ```bash
   npm install
   ```

3. 设置：将你的 userId 粘贴到 `userIds.txt` 文件中，每行一个账户：
   ```bash
   nano userIds.txt
   ```

4. 设置：将代理信息粘贴到 `proxies.txt` 文件中，每行一个代理：
   ```bash
   nano proxies.txt
   ```

5. 运行脚本：
   ```bash
   npm run start
   ```
