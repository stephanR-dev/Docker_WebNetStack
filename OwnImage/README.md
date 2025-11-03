# **Project 01 - Flask Backend mini app**

*Build an easy python backend with **flask** and **docker**

**files**

```
OwnImage/
├─ app.py
├─ Dockerfile
├─ requirements.txt

```

**context**

1. **Dockerfile** with image *python:3.12-slim*
2. python image fetches **flask** from requirements.txt
3. copies **app.py** into container
4. Localhost listens on port 8080; App listens on port 8000


**Start WebService**

````
*bash/ zsh*

docker build -t flaskimg .
docker run -d -p 8080:8000 flaskimg
curl http://localhost:8080

```