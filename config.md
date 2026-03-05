# ZeroClaw Config Reference

All top-level config sections available in `config.toml`. Based on upstream v0.1.7.

| Section | Description | In template? |
|---------|-------------|:---:|
| `api_key` / `api_url` | Provider API credentials | no (via env) |
| `default_provider` | LLM provider | yes |
| `default_model` | Default model | yes |
| `default_temperature` | Temperature | yes |
| `provider` | Provider-specific overrides | no |
| `observability` | Logging/tracing | no |
| `autonomy` | Permissions, approvals, risk | yes |
| `security` | Security policy | no |
| `runtime` | Native vs Docker execution | no |
| `research` | Proactive info gathering | no |
| `reliability` | Retries, fallback providers | no |
| `scheduler` | Periodic task execution | no |
| `agent` | Orchestration settings | no |
| `skills` | Skills loading | no |
| `model_routes` | Route hints to provider+model | no |
| `embedding_routes` | Embedding routing | no |
| `query_classification` | Auto-classify messages | no |
| `heartbeat` | Health pings | yes |
| `cron` | Cron jobs | no |
| `goal_loop` | Goal loop | no |
| `channels_config` | Channel enablement | yes |
| `memory` | Memory backends | no |
| `storage` | Storage providers | no |
| `tunnel` | Tunneling | no |
| `gateway` | Webhook/gateway server | yes |
| `composio` | OAuth tool integrations | yes |
| `secrets` | Secret encryption | no |
| `browser` | Browser automation | yes |
| `http_request` | HTTP requests | yes |
| `multimodal` | Image/audio handling | no |
| `web_fetch` | Web page fetching | no |
| `web_search` | Web search | yes |
| `proxy` | Proxy settings | no |
| `identity` | Identity config | no |
| `cost` | Cost tracking | no |
| `economic` | Token pricing | no |
| `peripherals` | Hardware peripherals | no |
| `agents` | Delegate sub-agents | no |
| `coordination` | Multi-agent coordination | no |
| `hooks` | Lifecycle hooks | no |
| `plugins` | Plugin system | no |
| `hardware` | Hardware config | no |
| `transcription` | Audio transcription | no |
| `agents_ipc` | Inter-agent comms | no |
| `mcp` | Model Context Protocol | no |
| `wasm` | WASM runtime | no |
