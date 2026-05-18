# 创建新隧道
cloudflared tunnel create my-tunnel

# 查看隧道列表
cloudflared tunnel list

# 配置 DNS 记录
cloudflared tunnel route dns my-tunnel example.com

# 临时运行隧道（测试用）
cloudflared tunnel run --url http://localhost:3000 my-tunnel

# 使用配置文件运行
cloudflared tunnel --config config.yml run