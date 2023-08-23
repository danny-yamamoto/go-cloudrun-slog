# go-cloudrun-slog
Check the slog in go 1.21.

## Usage
```bash
go get golang.org/x/exp/slog@latest
```

## Development
```bash
vscode ➜ /workspaces/go-cloudrun-slog (main) $ go run main.go 
2023/08/23 11:24:50 starting server...
2023/08/23 11:24:50 defaulting to port 8080
2023/08/23 11:24:50 listening on port 8080
{"time":"2023-08-23T11:24:54.135826638Z","level":"INFO","msg":"hello, world","user":"vscode"}
```
