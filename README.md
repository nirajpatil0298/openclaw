# 1. Install Ollama 

### Linux Command

`curl -fsSL https://ollama.com/install.sh | sh`

### Windows Powershell Command

`irm https://ollama.com/install.ps1 | iex`

--- 

# 2. Download LLM Model
ollama pull minimax-m2.7:cloud

# 3. Launch OpenClaw with minimax-m2.7:cloud in one command
ollama launch openclaw --model minimax-m2.7:cloud --yes

