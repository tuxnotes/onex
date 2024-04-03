## onex-toyblc

Launch a onex toy blockchain node

### Synopsis

The toy blc is used to start a naive and simple blockchain node.

```
onex-toyblc [flags]
```

### Options

```
      --accounts map                 Authentication username and password set for API interface. (default toyblc:onex(#)666,onex:onex(#)666)
      --address string               Wallet account to receive the block rewards. (default "0x210d9eD12CEA87E33a98AA7Bcb4359eABA9e800e")
  -c, --config FILE                  Read configuration from specified FILE, support JSON, TOML, YAML, HCL, or Java properties formats.
  -h, --help                         help for onex-toyblc
      --http.addr string             Specify the HTTP server bind address and port. (default "0.0.0.0:38443")
      --http.network string          Specify the network for the HTTP server. (default "tcp")
      --http.timeout duration        Timeout for server connections. (default 30s)
      --log.disable-caller           Disable output of caller information in the log.
      --log.disable-stacktrace       Disable the log to record a stack trace for all messages at or above panic level.
      --log.enable-color             Enable output ansi colors in plain format logs.
      --log.format FORMAT            Log output FORMAT, support plain or json format. (default "console")
      --log.level LEVEL              Minimum log output LEVEL. (default "info")
      --log.output-paths strings     Output paths of log. (default [stdout])
      --min-mine-interval duration   Specify the minimum mining interval. (default 2h0m0s)
      --miner                        Turn on mining mode.
      --mining-difficulty int        Specify the mining difficulty. (default 1)
      --p2p-addr string              The p2p server address. (default "0.0.0.0:6001")
      --peers strings                The initial peers. (default [ws://localhost:6001])
      --tls.ca-cert string           Path to ca cert for connecting to the server.
      --tls.cert string              Path to cert file for connecting to the server.
      --tls.insecure-skip-verify     Controls whether a client verifies the server's certificate chain and host name.
      --tls.key string               Path to key file for connecting to the server.
      --tls.use-tls                  Use tls transport to connect the server.
      --version version[=true]       Print version information and quit
```

###### Auto generated by spf13/cobra on 20-Jan-2024