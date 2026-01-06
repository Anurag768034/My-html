## GitHub Copilot Chat

- Extension Version: 0.29.1 (prod)
- VS Code: vscode/1.102.2
- OS: Mac

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 100.70.1.20 (1 ms)
- DNS ipv6 Lookup: ::ffff:100.70.1.20 (2 ms)
- Proxy URL: None (0 ms)
- Electron fetch (configured): HTTP 200 (141 ms)
- Node.js https: HTTP 200 (126 ms)
- Node.js fetch: HTTP 200 (130 ms)

Connecting to https://api.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 100.70.1.35 (2 ms)
- DNS ipv6 Lookup: ::ffff:100.70.1.35 (1 ms)
- Proxy URL: None (1 ms)
- Electron fetch (configured): HTTP 200 (995 ms)
- Node.js https: HTTP 200 (965 ms)
- Node.js fetch: HTTP 200 (1836 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).