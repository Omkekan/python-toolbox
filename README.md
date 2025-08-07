# The Essential Python Library Collection 🐍

A curated collection of the most popular and useful Python libraries, categorized by domain. This repository is designed to be a quick reference and a starting point for any Python project.

## 📦 How to Use

This repository is structured with multiple `requirements.txt` files inside the `requirements/` directory, categorized by their domain (e.g., `web.txt`, `data_science.txt`).

### ✅ Install a Specific Category

To install libraries for a specific domain, like web development, run:

```
pip install -r requirements/web.txt
```

### 🧩 Install All Libraries

To install all the libraries listed in this collection, run:

```
pip install -r requirements_all.txt
```

## 📚 Libraries by Category

### 🌐 Web Development & Networking

- **django**: A high-level "batteries-included" web framework for rapid, secure, and scalable development.
- **flask**: A lightweight and flexible microframework for building web applications.
- **fastapi**: A modern, high-performance web framework for building APIs with automatic interactive documentation.
- **requests**: A simple, elegant HTTP library for making network requests.
- **beautifulsoup4**: A library for pulling data out of HTML and XML files (web scraping).
- **scrapy**: A powerful, asynchronous framework for web crawling and scraping.
- **aiohttp**: An asynchronous HTTP client/server framework for asyncio.
- **httpx**: A fully featured async-capable HTTP client, seen as the successor to requests.
- **websockets**: A library for building WebSocket clients and servers.
- **gunicorn**: A robust WSGI HTTP server for UNIX, commonly used to serve Flask/Django apps.
- **uvicorn**: A lightning-fast ASGI server, built on uvloop and httptools, for serving FastAPI apps.

### 🔬 Data Science & Machine Learning

- **numpy**: The fundamental package for numerical computing, providing powerful N-dimensional array objects.
- **pandas**: A fast, powerful, and flexible open-source data analysis and manipulation tool.
- **polars**: A lightning-fast DataFrame library implemented in Rust, designed as a modern alternative to pandas.
- **scikit-learn**: A simple and efficient tool for data mining and data analysis (classification, regression, clustering).
- **tensorflow**: An end-to-end open-source platform for machine learning developed by Google.
- **torch**: An open-source machine learning library used for deep learning applications such as computer vision and NLP.
- **keras**: A high-level neural networks API, capable of running on top of TensorFlow, PyTorch, or JAX.
- **xgboost**: A highly efficient, flexible, and portable optimized distributed gradient boosting library.
- **lightgbm**: A fast, distributed, high-performance gradient boosting framework.
- **catboost**: A gradient boosting on decision trees library with categorical features support out of the box.
- **transformers**: State-of-the-art machine learning for PyTorch, TensorFlow, and JAX (from Hugging Face).
- **spacy**: A library for advanced Natural Language Processing (NLP) in Python.
- **nltk**: A leading platform for building Python programs to work with human language data.
- **matplotlib**: A comprehensive library for creating static, animated, and interactive visualizations.
- **seaborn**: A statistical data visualization library based on matplotlib, providing a high-level interface.
- **plotly**: An interactive, open-source graphing library that makes publication-quality graphs.
- **streamlit**: The fastest way to build and share data apps.
- **gradio**: A library for creating customizable UI components for your ML model, function, or API.
- **mlflow**: An open-source platform to manage the ML lifecycle, including experimentation, reproducibility, and deployment.

### 🧪 Scientific & Numerical Computing

- **scipy**: A library of algorithms and mathematical tools built on NumPy for scientific and technical computing.
- **sympy**: A Python library for symbolic mathematics (symbolic algebra).
- **numba**: A JIT (just-in-time) compiler that translates a subset of Python and NumPy code into fast machine code.

### 🖼️ Image, Video & Audio Processing

- **Pillow**: The friendly PIL (Python Imaging Library) fork, for opening, manipulating, and saving many different image file formats.
- **opencv-python**: The go-to library for computer vision tasks.
- **scikit-image**: A collection of algorithms for image processing.
- **moviepy**: A library for video editing: cutting, concatenations, title insertions, etc.
- **pydub**: A library to manipulate audio with a simple and easy high-level interface.

### 🗄️ Databases

- **SQLAlchemy**: The Python SQL Toolkit and Object Relational Mapper (ORM).
- **psycopg2-binary**: The most popular PostgreSQL database adapter for Python.
- **asyncpg**: A fast PostgreSQL database client library for use with Python's asyncio.
- **redis**: A Python client for the Redis key-value store.

### ✅ Testing

- **pytest**: A framework that makes it easy to write small, readable tests, and scales to support complex functional testing.
- **pytest-cov**: A plugin for pytest to produce coverage reports.
- **hypothesis**: A library for property-based testing, which generates test cases automatically.
- **tox**: A tool for automating testing in multiple environments (e.g., against different Python versions).

### 🖥️ CLI & GUI Development

- **PyQt6**: A comprehensive set of Python bindings for the Qt application framework.
- **pygame**: A set of Python modules designed for writing video games.
- **click**: A package for creating beautiful command-line interfaces in a composable way.
- **typer**: A library for building CLIs, based on Python type hints, built by the creator of FastAPI.
- **rich**: A library for rendering rich text and beautiful formatting in the terminal.
- **tqdm**: A fast, extensible progress bar for loops and CLI.

### ⚙️ Utilities, DevOps & Automation

- **python-dotenv**: Reads key-value pairs from a `.env` file and sets them as environment variables.
- **celery**: An asynchronous task queue/job queue based on distributed message passing.
- **pydantic**: Data validation and settings management using Python type annotations.
- **selenium**: A powerful tool for automating web browsers.
- **ruff**: An extremely fast Python linter and code formatter, written in Rust.
- **pre-commit**: A framework for managing and maintaining multi-language pre-commit hooks.
- **loguru**: A library that aims to bring enjoyable logging to Python.
