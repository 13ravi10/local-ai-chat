 HEAD
# local-ai-chat
=======
# Local AI chat (Ollama + Open WebUI)

Self-hosted chatbot for the university network.

## Setup
1. Install Ollama: `curl -fsSL https://ollama.com/install.sh | sh`
2. Pull the model: `ollama pull qwen2.5:1.5b`
3. Create the lite model: `ollama create qwen-lite -f modelfiles/qwen-lite.Modelfile`
4. Apply service settings: `sudo systemctl edit ollama` and paste `ollama-override.conf`
5. Start Open WebUI: `./run-openwebui.sh`
6. Open http://localhost:8080
 0cc7942 (Initial setup: Ollama + Open WebUI)
