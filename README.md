

```
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Run tests manually
```
$ python -m pytest -v tests/test_generator.py
```

Build docker
```
docker build -t cicd-buzz .
docker run -p 5000:5000 --rm -it cicd-practice
```

To launch a Docker image from Docker Hub
```
docker run -p 5000:5000 --rm -it daivinhtran/cicd-practice
```
