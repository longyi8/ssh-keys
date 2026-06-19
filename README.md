# ssh-keys

ED25519 SSH deploy key pair.

> 🔓 **公钥可以公开**：公钥的设计目的就是可以随意分享，攻击者拿到公钥无法反推出私钥。只有私钥需要保密。

## 一键查看公钥（raw 格式）

```bash
curl -sS https://raw.githubusercontent.com/longyi8/ssh-keys/main/id_ed25519_deploy.pub
```

## 添加公钥到 Linux

```bash
curl -sS https://raw.githubusercontent.com/longyi8/ssh-keys/main/id_ed25519_deploy.pub >> ~/.ssh/authorized_keys
chmod 700 ~/.ssh && chmod 600 ~/.ssh/authorized_keys
```

一行搞定：

```bash
curl -sS https://raw.githubusercontent.com/longyi8/ssh-keys/main/id_ed25519_deploy.pub >> ~/.ssh/authorized_keys && chmod 700 ~/.ssh && chmod 600 ~/.ssh/authorized_keys
```
