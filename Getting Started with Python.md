# Getting Started with Python

Welcome to the Python beginner's guide! This document will walk you through the basic setup and usage of Python.

## Table of Contents
1. [Installation](#installation)
2. [Setting Up a Virtual Environment](#setting-up-a-virtual-environment)
3. [Installing Packages](#installing-packages)
4. [Sample Code](#sample-code)
5. [Resources](#resources)

---

## Installation

To install Python, visit the official website:

👉 [Download Python](https://www.python.org/downloads/)

Follow the instructions for your operating system.

## Setting Up a Virtual Environment

Use the following command to create a virtual environment:

```bash
python -m venv myenv
```

Activate it with:
- Windows:
  ```bash
  myenv\Scripts\activate
  ```
- macOS/Linux:
  ```bash
  source myenv/bin/activate
  ```

## Installing Packages

Once your environment is active, use `pip` to install packages:

```bash
pip install requests
```

## Sample Code

Here's a simple example using the `requests` package:

```python
import requests

response = requests.get("https://api.github.com")
print(response.json())
```

## Resources

- [Python Official Docs](https://docs.python.org/3/)
- [Real Python Tutorials](https://realpython.com/)
- ![Python Logo](https://www.python.org/static/community_logos/python-logo.png)

---

Happy Coding! 🐍

