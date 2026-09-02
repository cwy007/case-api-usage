# README

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt

requirements.txt 文件需要手动维护

cd /Users/chanweiyan/Downloads/AI大模型应用第25期/1-AI大模型原理与API使用/CASE-API-USAGE
brew install uv
uv init
uv add dashscope==1.25.5
uv add openai==2.32.0
uv add python-dotenv
uv sync
uv run python "1-情感分析-Qwen.py"
