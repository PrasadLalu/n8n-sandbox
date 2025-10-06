# N8N Sandbox

### Run N8N - Docker Compose
```
docker compose up
```

### Create Python Virtual Environment
- **Install `uv`:**

   ```bash
   pip install uv

   uv --version
- **Create a Virtual Environmen:**
    ```bash
    uv venv .venv --python=3.10
- **Active Virtual Environment:**
    ```bash
    .venv\Scripts\activate
- **Initialize the `uv` Project:**
    ```bash
    uv init
- **Add Dependencies (e.g. add `python-dotenv`):**
    ```bash
    uv add python-dotenv