# MCP Server

MCP Server to integrate with Weather API and connect to Claude Desktop.

git clone <https://github.com/ankitkjha/mcp-server-api.git>

cd mcp-server-api

Install uv package
windows
powershell -ExecutionPolicy ByPass -c "irm <https://astral.sh/uv/install.ps1> | iex"

macos/linux
curl -LsSf <https://astral.sh/uv/install.sh> | sh

Create virtual environment

uv venv

Activate the virtual environment
Linux/macOS:

source .venv/bin/activate

Windows:

.venv\Scripts\activate

install required dependencies

uv add -r requirements.txt
