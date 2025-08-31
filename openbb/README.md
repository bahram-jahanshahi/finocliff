# OpenBB


## Setup Python Environment

```bash
python3.11 -m venv ~/venvs/openbb
source ~/venvs/openbb/bin/activate
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

