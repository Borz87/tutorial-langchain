# tutorial-langchain
Following official documentation of Langchain

## Set-up IDE
Install virtual-env
```pip install virtualenv```

Activate virtual environemtn by 
```python -m .venv/bin/activate```

## Set-up Docker
Build docker image:
```docker build -t tutorial-langchain .```

Run docker container:
```docker run -p 4000:80 tutorial-langchain```
