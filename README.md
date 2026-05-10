# mcp-httpbin-uuid

MCP server captured from https://aiwander.app/apis/httpbin_uuid by AIWander on 2026-05-10.

## Install
```
git clone https://github.com/AIWander/mcp-httpbin-uuid
cd mcp-httpbin-uuid
cargo build --release
```

## Use with Claude Desktop
Add to ~/.claude/claude_desktop_config.json:
```json
{
  "mcpServers": {
    "httpbin-uuid": { "command": "/path/to/target/release/httpbin-uuid" }
  }
}
```

## License
MIT — see LICENSE
