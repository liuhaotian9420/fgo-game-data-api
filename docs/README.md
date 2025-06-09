# Documentation

This project provides an HTTP API for retrieving and processing Fate/Grand Order game data. The API is built with FastAPI and exposes endpoints for raw and processed data.

## Quick Start
1. Install the dependencies using [Poetry](https://python-poetry.org/docs/):
   ```sh
   poetry install
   ```
2. Configure environment variables as described in the root `README.md`.
3. Start the development server:
   ```sh
   uvicorn app.main:app
   ```

Browse the running API at `http://127.0.0.1:8000` or visit the live API at `https://api.atlasacademy.io`.

## Development
- Lint the code with `./scripts/lint.ps1`.
- Format the code with `./scripts/format.ps1`.
- Run the test suite with `./scripts/test.ps1`.

## Project Structure
- `app/` – API implementation and supporting modules.
- `scripts/` – Helper scripts for linting, formatting, exporting data and more.
- `tests/` – Automated tests.

For additional information, refer to the root `README.md` and the `CHANGELOG.md` file.
