Commands
cs-python-api:

python3 -m uvicorn app.main:app --reload --port 8000 --host 0.0.0.0

cs-admin

python3 -m uvicorn app.main:app --reload --port 8001

Local links:
http://localhost:8001/messages
http://192.168.87.77:8000/
