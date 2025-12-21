# Coding Agent From Scratch

Simple teaching/demo project for a minimal interactive coding assistant loop using the OpenAI Python client.

**Contents**

- `coding_agent_from_scratch_lecture.py`: Main interactive agent loop and tool implementations (`read_file`, `list_files`, `edit_file`).
- `requirements.txt`: Python dependencies (`openai`, `python-dotenv`).
- `.env.example`: Example environment variable file (copy to `.env` and add your API key).

**Quickstart**

- Create or activate a Python virtual environment (recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

- Install dependencies:

```bash
python -m pip install -r requirements.txt
```

- Provide your OpenAI API key. Either copy `.env.example` to `.env` and edit, or export the key inline:

```bash
cp .env.example .env
# edit .env and replace YOUR_OPENAI_API_KEY_HERE
```

or

```bash
export OPENAI_API_KEY="sk-..."
```

- Run the interactive agent (quote the venv path if it contains spaces):

```bash
python "coding_agent_from_scratch_lecture.py"
```
