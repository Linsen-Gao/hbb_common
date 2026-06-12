# hbb_common

Shared Rust library for [RustDesk](https://github.com/rustdesk/rustdesk) — provides protobuf definitions, compression, configuration, cryptography, and platform abstractions.

## Modules

| Module | Description |
|--------|-------------|
| `protobuf` | Generated protobuf types for RustDesk protocol |
| `compress` | Zstd-based compression/decompression |
| `config` | Configuration management (via confy) |
| `crypt` | Sodium-based encryption/decryption |
| `platform` | Platform-specific abstractions (Linux/macOS/Windows) |
| `tcp` | TCP networking utilities with TLS support |
| `udp` | UDP hole-punching and relay |

## Dependencies

Key dependencies: tokio, protobuf, zstd, sodiumoxide, tokio-rustls/tokio-native-tls (platform-dependent TLS).

## License

Part of the RustDesk ecosystem.
