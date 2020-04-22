# Minimum Python Envrionment

## Built docker image
run from main repository folder
```
docker built -t minimum-python-env docker
```

## Run the script
```
docker run -it --rm --name minimum-python-env -v "${PWD}:/usr/src/myapp -w /usr/src/myapp minimum-python-env python script2.py
```
