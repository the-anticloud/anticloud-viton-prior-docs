# Command Line Interface — VITON

**Upstream:** https://github.com/xthan/VITON

## Anticloud CLI

```bash
# Install
pip install anticloud-viton

# Run offline with PAX inference
anticloud-viton --offline --pax-local

# Run with AIOSS logging
anticloud-viton --aioss-log ./ledger.jsonl

# Single binary (after build)
./viton --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
