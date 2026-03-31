# 1. Install Ollama 

### Linux Command

`curl -fsSL https://ollama.com/install.sh | sh`

### Windows Powershell Command

`irm https://ollama.com/install.ps1 | iex`

--- 

# 2. Download LLM Model
ollama pull qwen3.5 --yes

# 3. Launch OpenClaw with qwen3.5 in one command
ollama launch openclaw --model qwen3.5 --yes

