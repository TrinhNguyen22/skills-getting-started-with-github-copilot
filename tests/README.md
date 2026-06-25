# Tests

Run the backend test suite for this project.

Setup

```bash
python -m pip install -r requirements.txt
```

Run tests

```bash
pytest -q
```

Notes

- Tests are located in `tests/test_app.py` and use the Arrange-Act-Assert pattern.
- The FastAPI app is imported from `src.app`; tests reset the in-memory state between cases.
