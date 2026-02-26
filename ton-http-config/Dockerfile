FROM python:3.10-slim@sha256:6a5861123aa815f92e5d20ce8372a8ba6668540c1081e5c4c44933cc1ba4fd3a

WORKDIR /var/ton-work/
ADD ./simple_server.py ./

ENTRYPOINT ["python3", "simple_server.py"]
