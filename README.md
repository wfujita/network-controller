# network-controller
## Purpose
Control network devices via NETCONF and SSH.

（目的）
NETCONF および SSH を用いてネットワーク装置を制御する。

## Design Policy
- Prefer NETCONF over CLI
- Device-specific logic must be isolated

（設計方針）
- CLI より NETCONF を優先する
- ベンダ依存ロジックは分離する
