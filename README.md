# Cadmus Minerva API

Cadmus API for the Minerva lexicon editor.

🐋 Quick Docker image build:

  docker buildx build . --platform linux/amd64,linux/arm64,windows/amd64 -t vedph2020/cadmus-minerva-api:0.0.1 -t vedph2020/cadmus-minerva-api:latest --push

(replace with the current version).

This is a Cadmus API layer customized for the PRJ project. Most of its code is derived from [shared Cadmus libraries](https://github.com/vedph/cadmus-api).

## History

- 2026-02-10: updated packages.
- 2026-01-27: updated packages.

### 1.0.0

- 2025-11-24: ⚠️ upgraded to NET 10.
