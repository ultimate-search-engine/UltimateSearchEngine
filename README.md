# Ultimate Search Engine

This is a Maturita exam project, which is free and open-source.

## Installation

You need Git on your machine as well as Docker.

```bash
git clone --recursive https://github.com/ultimate-search-engine/UltimateSearchEngine.git
cd UltimateSearchEngine
git submodule update --init --recursive
git submodule foreach git pull origin main
docker compose up
```
