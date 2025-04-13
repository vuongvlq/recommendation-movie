# Using `uv` to Manage the Python Project
This project uses `uv` to manage dependencies and the Python environment. Follow the steps below to set up and use the project:

## Prerequisites
- Ensure you have Python 3.7 or higher installed.
- Install `uv` by running:
  ```bash
  pip install uv
  ```

## Setting Up the Project
1. Clone the repository:
  ```bash
  git clone https://github.com/your-username/recommendation-movie.git
  cd recommendation-movie
  ```

2. Initialize the `uv` environment:
  ```bash
  uv venv
  ```

3. Activate the virtual environment:

   - **Linux/Mac**:
     ```bash
     source .venv/bin/activate
     ```

   - **Windows**:
     ```bash
     .venv\Scripts\activate
     ```

4. Install dependencies:
  ```bash
  uv sync
  ```

## Running the Project
To run the project, use:
```bash
uv run main.py
```

## Deactivating the Environment
To deactivate the `uv` environment, simply exit the terminal or run:
```bash
deactivate
```

For more information, refer to the [uv documentation](https://uv-py.readthedocs.io/).