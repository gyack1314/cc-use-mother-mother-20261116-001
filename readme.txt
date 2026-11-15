Install locked dependencies before offline use.
Run API: uvicorn civic_flow.api:app --host 127.0.0.1 --port 8000
Test: python -m unittest discover -s tests -v
Build check: python -m compileall -q civic_flow tests
Local acceptance: python -m civic_flow.demo
