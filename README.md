# MIS-project
A small information system using FastAPI and MySQL

## Setup
Setup the environment with the following command
```bash
./setup.sh
```

## Run Server
First, source the virtual environment (it is not required if you ran the `setup.sh`)
```bash
source ./venv/bin/activate
```

Then start the server
```bash
uvicorn main:app --reload
```
