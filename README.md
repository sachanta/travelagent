# Travel Agent

A smart travel planning assistant that helps users plan their trips efficiently.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/travelagent.git
cd travelagent
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Development

- Run tests: `pytest`
- Format code: `black .`
- Sort imports: `isort .`
- Lint code: `flake8`

## Project Structure

```
travelagent/
├── src/
│   └── travelagent/
│       ├── __init__.py
│       ├── api/
│       ├── core/
│       └── utils/
├── tests/
├── requirements.txt
└── README.md
```
