# OS Project

**Operating Systems Project**  
**Subject Code:** 21CSC202J

This project is an interactive CPU scheduling simulator. It supports configurable process workloads, scheduling algorithm comparisons, Gantt chart visualizations, and performance metrics. The Python backend also provides an API for generating sample workloads.

## Requirements

- Python 3.9 or later
- A modern web browser

No third party Python packages are required.

## Run the project

From the project root, start the local server:

```bash
python Backend/server.py
```

Open **http://127.0.0.1:8080/** in your browser. Stop the server with `Ctrl+C`.

The server listens on `127.0.0.1` at port `8080`. The simulator's workload generation endpoint is available at `/api/workload`.

## Project structure

- `Backend/server.py` — local web server and workload generation API
- `Frontend/` — simulator pages, styles, and browser scripts
- `tests/` — project tests
