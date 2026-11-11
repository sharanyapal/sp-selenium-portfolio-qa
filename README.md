<div align="center">

# Python + Selenium / Portfolio End-to-End QA

**Browser automation for portfolio quality checks.**

`Python` · Research / engineering project · Source-first

</div>

---

## Mission

Parameterized Chrome UI smoke tests for the four polyglot companion websites, plus a behavior assertion for attribution-model switching. Designed for local or CI headless Chrome via Selenium Manager.

## Run / reproduce

```bash
pip install -r requirements.txt
# From the parent directory of the four website project folders:
python -m http.server 8080
# In a second terminal:
APP_BASE_URL=http://127.0.0.1:8080 pytest -q
```

## Files and responsibilities

| Path | Description |
| :--- | :--- |
| [`README.md`](./README.md) | Project documentation |
| [`requirements.txt`](./requirements.txt) | Supporting project asset |
| [`test_sites.py`](./test_sites.py) | Test scripts |

## What to investigate

- Inspect the data, assumptions and program entry point.
- Modify inputs and observe the effect on behavior.
- Look for error cases and compare results with any included tests.

## Responsible interpretation

This is an educational demonstration, not a production-grade analytics, security or financial advice system. Use synthetic or permitted test data; review dependencies and limitations before reusing the implementation.

<details><summary><strong>Preserved original project notes</strong></summary>

# Python + Selenium / Portfolio End-to-End QA

Parameterized Chrome UI smoke tests for the four polyglot companion websites, plus a behavior assertion for attribution-model switching. Designed for local or CI headless Chrome via Selenium Manager.

```bash
pip install -r requirements.txt
# From the parent directory of the four website project folders:
python -m http.server 8080
# In a second terminal:
APP_BASE_URL=http://127.0.0.1:8080 pytest -q
```

Requires Chrome and Selenium; these E2E tests are **not automatically run** when browser drivers are unavailable.

</details>

---

<sub>Browse the [rest of the project collection](https://github.com/sharanyapal?tab=repositories).</sub>
