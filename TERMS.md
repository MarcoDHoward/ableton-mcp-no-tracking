# Data use

This fork of [ahujasid/ableton-mcp](https://github.com/ahujasid/ableton-mcp) collects no data.

- No telemetry, no analytics, no install or session IDs.
- No dataset recording: prompts, MIDI, project snapshots and device settings never leave your machine.
- No outbound network connections. The MCP server talks only to the Ableton Remote Script on `127.0.0.1:9877`.
- Nothing is written to disk by the server or the Remote Script.

The code is MIT-licensed; see [LICENSE](LICENSE). Upstream's data terms do not apply to this fork, because none of the collecting code is present.
