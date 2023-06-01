# NetZIP

> ZIP file reader optimized for network access

## Development environment

1. Create a virtual environment:
   ```sh
   python3 -m venv --prompt netzip .venv
   ```

2. Activate virtual environment:
   ```sh
   source .venv/bin/activate
   ```

3. Install the project in editable mode:
   ```sh
   pip install --upgrade pip
   pip install --editable .
   pip install pytest black isort
   ```

4. Format source code:
   ```sh
   isort . && black .
   ```
