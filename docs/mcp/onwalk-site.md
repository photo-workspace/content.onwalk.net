~/.config/xxx/mcp.toml     → MCP 连接定义（机器/环境级）
.env                       → 身份与密钥（仓库级）
docs/mcp/*.md              → 使用约定（人 & agent 级）
*.skill                    → 声明“我需要这个能力”

[mcp_servers.onwalk-site]
url = "https://www.onwalk.net/mcp"
bearer_token_env_var = "WEB_SITE_MCP_ACCESS_TOKEN"
auth = "Bearer"
status = "enabled"
