# Clause API

Run the API from this directory so its relative data and Qdrant paths resolve
correctly. Use the project environment managed by `uv` rather than a global
Python interpreter:

```powershell
cd clause\api
uv sync
uv run python -m app.main
```

In VS Code, select `api\.venv\Scripts\python.exe` as the Python interpreter when
running the API. The global interpreter may not have the API's dependencies
installed.
