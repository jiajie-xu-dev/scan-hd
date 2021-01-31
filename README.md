# Scan HD
Application that collects system metrics (CPU, disk, network, RAM)

#### Instructions
Create your virtual env
```shell script
python3 -m venv /path/to/local/venv
``` 
Install all dependencies
```shell script
pip install -r requirements.txt
``` 

#### Improvements
To add new dependencies, after installing it inside the virtual env, execute:
```shell script
pip freeze > requirements.txt
```