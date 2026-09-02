# README

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt

requirements.txt 文件需要手动维护

brew install uv
uv init
uv add dashscope==1.25.5
uv add openai==2.32.0
uv add python-dotenv
uv sync
uv run python "1-情感分析-Qwen.py"
