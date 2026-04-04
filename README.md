# ZoyaChat Server

自建 ZoyaChat 服务器，3 分钟部署。

## 快速开始

```bash
git clone https://github.com/zoyachat/zoyachat-server.git
cd zoyachat-server
cp .env.example .env
# 编辑 .env，填写 JWT_SECRET（openssl rand -hex 32 生成）
npm install --production
npm start
```

## Docker 部署

```bash
docker-compose up -d
```

## 环境变量说明

见 .env.example
