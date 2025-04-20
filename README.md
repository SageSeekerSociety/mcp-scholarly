# SageSeekerSociety/mcp-scholarly MCP server

A MCP server based on [the official Scholarly MCP](https://github.com/adityak74/mcp-scholarly), with some extra optimizations.

## How to use?

Use docker to quick start:

```bash
sudo docker run -d \
    --name mcp-scholarly \
    -p 8000:8000 \
    -e API_KEY=top_secret \
    ghcr.io/sageseekersociety/mcp-scholarly:main
```
