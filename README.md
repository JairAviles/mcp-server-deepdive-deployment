## MCP Server Deepdive Deployment

### Installation

Add this to your MCP client's configuration:

```json
{
	"mcpServers": {
		"two_sums": {
			"command": "uvx",
			"args": [
				"--from",
				"git+https://github.com/JairAviles/mcp-server-deepdive-deployment.git",
				"mcp-server"
			]
		}
	}
}
```

