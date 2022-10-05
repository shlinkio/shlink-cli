# shlink-cli
A standalone CLI tool to interact with Shlink's API

## Supported Systems
- macOS
- Any Linux

## Usage
**Modify Line 4 and 5 to your Shlink `Host` and `apiKey`**

### Quick Command
```bash
shlink https://www.google.com
```

### Specify the output type
```bash
shlink https://www.google.com -f json
```

### Shorten a URL and receive JSON output, for instance to display with `jq` :
```bash
shlink https://www.baidu.com -f json | jq
```

## LICENSE
MIT LICENSE
