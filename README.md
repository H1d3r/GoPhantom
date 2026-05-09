# GoPhantom

> Archived security research prototype for Go-based Windows loader generation.

GoPhantom was an experiment in template-driven binary generation, deterministic
build material, and Windows security telemetry research. The project is no
longer actively developed.

This repository is kept as a snapshot of prior work, not as an operational
toolkit or a roadmap for future development.

## Status

- Maintenance: archived
- Target: `windows/amd64`
- Language: Go
- License: MIT

No new features are planned. Issues and pull requests may not be reviewed.

## Historical Snapshot

The original public README and release presentation are preserved in the
[`pre-archive-public-readme`](https://github.com/watanabe-hsad/GoPhantom/tree/pre-archive-public-readme)
tag for historical context.

## Scope

Use only in owned labs, authorized research environments, or defensive testing
contexts. Do not use this project against systems you do not own or explicitly
have permission to assess.

## Build

```bash
go test ./...
go build -o GoPhantom .
```

## Layout

```text
.
├── generator.go
├── generator_test.go
├── internal/
├── templates/
├── build/
└── VERSION
```

## Notes

The repository intentionally avoids detailed operational guidance. Historical
implementation details remain in the source for auditability, but the project is
not presented as production-ready software.

## License

MIT. See [LICENSE](LICENSE).
