# OpenBB


## Setup Python Environment

```bash
cd openbb
python3.11 -m venv venv
source venv/bin/activate
```

## Install OpenBB

```bash
pip install "openbb[all]"
```

## Run OpenBB

You can run OpenBB using either of the following commands:

```bash
openbb-api
```
or
```bash
uvicorn openbb_core.api.rest_api:app --host 127.0.0.1 --port 8000 --reload
```

## Open API doc and Try It Out
```bash
http://127.0.0.1:6900/docs#/
```