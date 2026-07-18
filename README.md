<p align="center"><img src="assets/banner.png" alt="Awesome MCP Servers 2026" width="100%"></p>

# Awesome MCP Servers 2026

A curated, link-checked collection of useful Model Context Protocol servers for Claude Code, Cursor, Windsurf and other MCP-compatible AI agents.

> **Verified:** 18 July 2026. A working repository link does not guarantee that a server is safe for your environment. Review permissions, source code, release activity and authentication requirements before installation.

## Status legend

- **Official** — maintained by the service or platform owner.
- **Reference** — maintained by the MCP project as an educational/reference implementation.
- **Community** — third-party project with a public source repository; evaluate it independently.
- **Demo** — example implementation, not a production recommendation.

## Start here

- [Official MCP documentation](https://modelcontextprotocol.io/)
- [Official MCP Registry](https://registry.modelcontextprotocol.io/)
- [MCP reference servers](https://github.com/modelcontextprotocol/servers)
- [MCP specification](https://github.com/modelcontextprotocol/modelcontextprotocol)

## Development tools

| MCP server | What it does | Status | Source |
|---|---|---:|---|
| GitHub MCP Server | Repositories, issues, pull requests, code and automation | Official | [github/github-mcp-server](https://github.com/github/github-mcp-server) |
| Filesystem | Controlled access to selected files and directories | Reference | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) |
| Git | Read, search and manipulate Git repositories | Reference | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/git) |
| Docker MCP Gateway | Run and manage MCP servers through Docker | Official | [docker/mcp-gateway](https://github.com/docker/mcp-gateway) |
| Playwright MCP | Browser automation using Playwright | Official | [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) |
| Firecrawl MCP | Search, crawl and extract web content | Official | [mendableai/firecrawl-mcp-server](https://github.com/mendableai/firecrawl-mcp-server) |
| OpenAI Deep Research sample | Example MCP server compatible with Deep Research | Demo | [openai/sample-deep-research-mcp](https://github.com/openai/sample-deep-research-mcp) |

## Search and research

| MCP server | What it does | Status | Source |
|---|---|---:|---|
| Brave Search MCP | Web and local search through Brave Search | Official | [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) |
| Kagi MCP | Kagi Search and related tools | Official | [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) |
| Jina AI MCP | Search, reading and fact-checking tools | Official | [jina-ai/MCP](https://github.com/jina-ai/MCP) |
| Tavily MCP | Search, extract, map and crawl | Official | [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) |
| SearXNG MCP | Private metasearch through a SearXNG instance | Community | [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) |
| Fetch | Fetch and convert web content for model use | Reference | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) |

## Databases and data platforms

| MCP server | What it does | Status | Source |
|---|---|---:|---|
| MongoDB MCP | MongoDB databases and Atlas clusters | Official | [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) |
| Redis MCP | Manage and search Redis data | Official | [redis/mcp-redis](https://github.com/redis/mcp-redis) |
| Supabase MCP | Connect AI assistants to Supabase projects | Official/community org | [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) |
| Pinecone MCP | Work with Pinecone vector databases | Official | [pinecone-io/pinecone-mcp](https://github.com/pinecone-io/pinecone-mcp) |
| Neo4j MCP | Neo4j graph database tooling | Labs | [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) |

## Knowledge, memory and collaboration

| MCP server | What it does | Status | Source |
|---|---|---:|---|
| Notion MCP | Access and update Notion workspaces | Official | [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) |
| Slack MCP plugin | Slack MCP server plus developer skills | Official | [slackapi/slack-skills-plugin](https://github.com/slackapi/slack-skills-plugin) |
| Memory | Persistent knowledge graph memory | Reference | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) |
| Sequential Thinking | Structured, dynamic reasoning workflow | Reference | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) |
| Time | Time and timezone conversion | Reference | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/time) |

## Cloud and infrastructure

| MCP server | What it does | Status | Source |
|---|---|---:|---|
| AWS MCP servers | Collection of MCP servers for AWS services | Official | [awslabs/mcp](https://github.com/awslabs/mcp) |
| Cloudflare MCP servers | Cloudflare account, developer and observability tools | Official | [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) |
| Cloudflare API MCP | Token-efficient access to the Cloudflare API | Official | [cloudflare/mcp](https://github.com/cloudflare/mcp) |
| Cloud Run MCP | Deploy applications to Google Cloud Run | Official | [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) |
| Grafana MCP | Query dashboards, metrics, logs and incidents | Official | [Grafana/mcp-grafana](https://github.com/Grafana/mcp-grafana) |

## Security checklist

Before enabling any MCP server:

1. Read its security notes, license, open issues and recent release history.
2. Grant the smallest possible filesystem, repository, API and cloud permissions.
3. Use short-lived or narrowly scoped tokens; never commit secrets to a repository.
4. Prefer read-only access until write operations are genuinely required.
5. Run third-party servers in an isolated account, container or sandbox when practical.
6. Review every tool capable of deleting data, sending messages, executing commands or changing infrastructure.

## Inclusion policy

A project may be added when it has:

- a public, reachable source or official documentation link;
- a clear MCP implementation and usage instructions;
- an identifiable maintainer and license;
- no unresolved placeholder or review marker in the catalog;
- a truthful status label: Official, Reference, Community or Demo.

Archived, missing or unverifiable projects are removed rather than linked to similarly named repositories.

## Contributing

Contributions are welcome. Open an [issue](https://github.com/KostZen/Production-Ready-MCP-Servers-for-Claude-Code/issues) or a [pull request](https://github.com/KostZen/Production-Ready-MCP-Servers-for-Claude-Code/pulls) and include:

- the canonical repository or documentation URL;
- maintainer/owner information;
- license;
- supported transport and authentication method;
- a short security note.

## License

[MIT](LICENSE)
