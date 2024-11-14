监控 Binance/Bybit 等新上币公告并通知

## 项目说明
监控交易所新上币公告并通知

## 目前支持的交易所
- binance
- Bybit 

## 支持的推送平台
- bark
- 钉钉
- 飞书机器人
- go-cqhttp
- gotify
- iGot
- server 酱
- PushDeer
- 微加机器人
- qmsg 酱
- 企业微信
- tg 机器人
- 智能微秘书
- 邮件
- PushMe
- 自定义通知webhook

## 使用说明

修改notify.py中的配置项


执行命令：

```bash
pip install -r requirements.txt
python main.py
```

## docker 运行

```bash
docker compose up -d
```

## docker部署镜像

```bash
生成本地镜像 docker pull docker账户/chole_cex_watcher

多平台镜像构成 docker buildx build --platform linux/amd64,linux/arm64 -t docker账户/chole_cex_watcher:latest --push .

```