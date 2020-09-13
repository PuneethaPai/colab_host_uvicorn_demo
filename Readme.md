## [Colab Host](https://github.com/PuneethaPai/colab_host) Demo: FastApi App with Uvicorn

## Install Colab Host:

```bash
$ pip install colab_host
```

## Use Colab Host to run your FastAPI App:

```python
from colab_host import UvicornApp

UvicornApp(
    port=3000,
    app="main:app",
    git_url="https://github.com/PuneethaPai/colab_host_uvicorn_demo.git",
    requirements_file="requirements.txt"
)
```

## Testing FastApi App:

```bash
$ pip install -r requirements.txt
$ uvicorn --host 0.0.0.0 --port 1000 main:app
```
