# Vulnerability Scanner & CVE Tracker

A command-line tool that scans a target host for open ports and running services, then
cross-references detected software versions against the [NVD](https://nvd.nist.gov/) CVE
database to flag known vulnerabilities.

Built as a learning project — Python fundamentals, networking, working with APIs, and
basic data storage, all in one build.

## Status

Work in progress. Current focus: **Phase 1 — port scanner**.

- [ ] Port scanner (socket-based)
- [ ] Service/banner detection
- [ ] CVE lookup via NVD API
- [ ] Local storage of scan results (SQLite)
- [ ] Report output (CLI, then HTML/JSON)
- [ ] CLI interface (argparse/click)

## Tech stack

- Python 3
- `socket` — port scanning
- `requests` — NVD API calls
- `sqlite3` — storing scan results and CVE data
- `argparse` / `click` — command-line interface

## Setup

```bash
git clone https://github.com/SabrinaB-uni/Vuln-Scanner.git
cd Vuln-Scanner
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

TBD — added as the CLI takes shape.

## Disclaimer

For use only against systems you own or have explicit permission to test.
