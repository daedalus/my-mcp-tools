# My MCP Tools

A collection of MCP (Model Context Protocol) servers providing various utilities.

## Packages

| Package | Description |
|---------|-------------|
| [mcp-canbus](https://pypi.org/project/mcp-canbus/) | MCP server for CAN bus communication |
| [mcp-cryptography](https://pypi.org/project/mcp-cryptography/) | MCP server exposing cryptography library functionality |
| [mcp-ecdsa](https://pypi.org/project/mcp-ecdsa/) | MCP server for ECDSA cryptography |
| [mcp-epochs](https://pypi.org/project/mcp-epochs/) | MCP tool that provides current Unix timestamp |
| [mcp-exa](https://pypi.org/project/mcp-exa/) | MCP server exposing Exa websearch API |
| [mcp-external-memory](https://pypi.org/project/mcp-external-memory/) | An MCP server that gives LLMs persistent, searchable semantic memory |
| [mcp-gmpy2](https://pypi.org/project/mcp-gmpy2/) | MCP server exposing gmpy2 arbitrary precision arithmetic functions |
| [mcp-hashlib](https://pypi.org/project/mcp-hashlib/) | An MCP server that exposes hashlib functionality |
| [mcp-homeassistant](https://pypi.org/project/mcp-homeassistant/) | MCP server for Home Assistant integration |
| [mcp-llm-gateway](https://pypi.org/project/mcp-llm-gateway/) | MCP-compatible LLM gateway that proxies completion requests to downstream OpenAI-compatible providers |
| [mcp-lsp](https://pypi.org/project/mcp-lsp/) | MCP server that exposes pyright LSP functionality to AI assistants |
| [mcp-metar](https://pypi.org/project/mcp-metar/) | MCP server for METAR/TAF aviation weather data |
| [mcp-modelcontextprotocol-io](https://pypi.org/project/mcp-modelcontextprotocol-io/) | MCP server for modelcontextprotocol.io |
| [mcp-mysql](https://pypi.org/project/mcp-mysql/) | MCP MySQL Server providing database knowledge and data query capability |
| [mcp-mysql-connector](https://pypi.org/project/mcp-mysql-connector/) | MCP server for MySQL database connectivity |
| [mcp-number-theory](https://pypi.org/project/mcp-number-theory/) | MCP server exposing number theory functions and factorization algorithms from RsaCtfTool |
| [mcp-numpy](https://pypi.org/project/mcp-numpy/) | An MCP server that exposes NumPy functionality |
| [mcp-oeis](https://pypi.org/project/mcp-oeis/) | MCP server for the OEIS (Online Encyclopedia of Integer Sequences) API |
| [mcp-pcapy-ng](https://pypi.org/project/mcp-pcapy-ng/) | MCP server exposing pcapy-ng packet capture functionality |
| [mcp-parigp](https://pypi.org/project/mcp-parigp/) | MCP server exposing cypari2 (PARI/GP) number theory library |
| [mcp-psycopg2](https://pypi.org/project/mcp-psycopg2/) | MCP server exposing psycopg2 PostgreSQL database adapter functionality |
| [mcp-pymetasploit3](https://pypi.org/project/mcp-pymetasploit3/) | MCP server for Metasploit Framework via pymetasploit3 |
| [mcp-pyright](https://pypi.org/project/mcp-pyright/) | MCP server that exposes Pyright language server functionality |
| [mcp-pwntools](https://pypi.org/project/mcp-pwntools/) | MCP server exposing pwntools functionality for binary exploitation |
| [mcp-python-bitcoinlib](https://pypi.org/project/mcp-python-bitcoinlib/) | An MCP server that exposes the python-bitcoinlib API |
| [mcp-qiskit](https://pypi.org/project/mcp-qiskit/) | MCP server exposing Qiskit quantum computing functionality |
| [mcp-recon-ng](https://pypi.org/project/mcp-recon-ng/) | MCP server exposing full recon-ng OSINT framework functionality |
| [mcp-redis-server](https://pypi.org/project/mcp-redis-server/) | MCP server that exposes Redis API to AI models |
| [mcp-registry](https://pypi.org/project/mcp-registry/) | MCP server for interacting with the MCP Registry API |
| [mcp-reverse-engineering](https://pypi.org/project/mcp-reverse-engineering/) | A sandboxed MCP tool for reverse engineering with multiple tool integrations |
| [mcp-rfc-editor](https://pypi.org/project/mcp-rfc-editor/) | MCP server for editing RFC documents using rfc-editor library |
| [mcp-rpn](https://pypi.org/project/mcp-rpn/) | MCP server that exposes an RPN calculator |
| [mcp-rs232](https://pypi.org/project/mcp-rs232/) | An MCP server that exposes RS232 serial port connectivity |
| [mcp-rs485](https://pypi.org/project/mcp-rs485/) | An MCP server that exposes RS485 bus connectivity |
| [mcp-server-mssql](https://pypi.org/project/mcp-server-mssql/) | MCP server for Microsoft SQL Server |
| [mcp-server-nmap](https://pypi.org/project/mcp-server-nmap/) | MCP server that exposes the python-nmap API for network scanning |
| [mcp-shodan](https://pypi.org/project/mcp-shodan/) | MCP server exposing all Shodan API functionality |
| [mcp-smbmap](https://pypi.org/project/mcp-smbmap/) | MCP server exposing smbmap SMB enumeration functionality |
| [mcp-smart-proxy](https://pypi.org/project/mcp-smart-proxy/) | Token-efficient MCP server gateway with semantic tool search |
| [mcp-snap7](https://pypi.org/project/mcp-snap7/) | MCP server for python-snap7, enabling MCP clients to interact with Siemens PLCs |
| [mcp-sqlite3](https://pypi.org/project/mcp-sqlite3/) | MCP server exposing sqlite3 library functionality |
| [mcp-stl](https://pypi.org/project/mcp-stl/) | MCP server for editing STL 3D model files |
| [mcp-sympy](https://pypi.org/project/mcp-sympy/) | MCP server that exposes SymPy's symbolic mathematics functionality |
| [mcp-telegram-bot](https://pypi.org/project/mcp-telegram-bot/) | MCP server that exposes a Telegram bot |
| [mcp-whatsapp](https://pypi.org/project/mcp-whatsapp/) | MCP server exposing WhatsApp bot functionality |
| [mcp-z3-prover](https://pypi.org/project/mcp-z3-prover/) | MCP server exposing Z3 solver API |
| [mcp-zabbix](https://pypi.org/project/mcp-zabbix/) | MCP server for Zabbix API |
| [mcp-zmq](https://pypi.org/project/mcp-zmq/) | MCP server for ZMQ messaging |

## Installation

```bash
pip install -r requirements.txt
```

## Updating the List

To update the list of packages, run these commands:

```bash
# Get all mcp-* repos from daedalus user on GitHub
curl -s "https://api.github.com/search/repositories?q=user:daedalus+mcp-&per_page=100" | python3 -c "import json,sys; d=json.load(sys.stdin); [print(r['name']) for r in d.get('items',[])]"

# Check if packages exist on PyPI (returns 301 if exists)
for pkg in mcp-pkgname; do code=$(curl -s -o /dev/null -w "%{http_code}" "https://pypi.org/p/$pkg/"); echo "$pkg: $code"; done

# Get repo description from GitHub
curl -s "https://api.github.com/repos/daedalus/mcp-pkgname" | python3 -c "import json,sys; d=json.load(sys.stdin); print(d.get('description','MCP server'))"
```

