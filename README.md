# ssh-keys

Dedicated SSH deploy keys.

## 添加公钥到 Linux

```bash
echo 'ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIG1fSxq/Yw4zmMq7LfbRDfKWNDzIP3Kr4gabWDSIXukz imaginesea@github-deploy' >> ~/.ssh/authorized_keys
```

添加后确保权限正确：

```bash
chmod 700 ~/.ssh && chmod 600 ~/.ssh/authorized_keys
```
