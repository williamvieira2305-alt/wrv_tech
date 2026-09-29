# WRV Tech API

## Rodar no Windows

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
uvicorn main:app --reload
```

## Rodar no Linux/macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

Abra http://127.0.0.1:8000/docs.

O endpoint de teste é `GET /api/v1/health`.
