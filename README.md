# nginx-conf

nginx conf

## Deploy

```bash
ansible-playbook -u xxx-sa -i inventory/oversea deploy.yml
```

ansible tags:
- enable: 开机启动 openresty 服务
- restart: 重启 openresty 服务
- reload: 不重启, 只是 reload 服务
# ansible-demo
