# 使用cloudflare

1. 创建新隧道     `cloudflared tunnel create my-tunnel`

2. 查看隧道列表    `cloudflared tunnel list`

3. 配置 DNS 记录   `cloudflared tunnel route dns my-tunnel example.com`

4. 临时运行隧道（测试用） `cloudflared tunnel run --url http://localhost:3000 my-tunnel`

5. 使用配置文件运行    `cloudflared tunnel --config config.yml run`


# 项目启动方式
`npx wrangler pages deploy public`