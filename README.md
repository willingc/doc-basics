# doc-basics
A minimal Sphinx documentation structure

Uses:
- Python 3
- Sphinx >= 1.6
- docs: the root directory for documentation
- intersphinx using Python 3

## Installation

1. Clone the repo from GitHub

```bash
git clone https://github.com/willingc/doc-basics.git
```

2. Change directory to `doc-basics`.

```bash
cd doc-basics
```

3. Create and activate a virtual environment

```bash
python3 -m venv mydocenv
source mydocenv/bin/activate
```

4. Install requirements.

```bash
python3 -m pip install -r docs/requirements_docs.txt
```

## Build documentation

Clean out prior doc builds: `make clean`

Build docs (in html format): `make html`

View docs: `open _build/html/index.html`

