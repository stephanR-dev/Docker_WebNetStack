# Docker_WebNetStack

WebNetStack/
├─ README.md
├─ .gitignore
├─ Makefile
├─ bootstrap.sh
├─ 01-build-custom-image/
│ ├─ app.py
│ ├─ requirements.txt
│ └─ Dockerfile
├─ 02-pull-existing-image/
│ ├─ website/
│ │ └─ index.html
│ └─ run-nginx.sh
└─ 03-frontend-backend-network/
├─ docker-compose.yml
├─ frontend/
│ ├─ Dockerfile
│ ├─ nginx.conf
│ └─ site/
│ └─ index.html
└─ backend/
├─ Dockerfile
├─ requirements.txt
└─ app/
└─ main.py