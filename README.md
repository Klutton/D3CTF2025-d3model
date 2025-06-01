# D3CTF2025-d3model

clone this repository

```bash
git clone https://github.com/Klutton/D3CTF2025-d3model.git
```

build and run the `Dockerfile`:

```bash
# enter the directory
cd ./D3CTF2025-d3model
# build
docker build -t d3ctf2025-d3model:latest .
# run on port 5000
docker run -d -p 5000:5000 --name d3ctf2025-d3model d3ctf2025-d3model:latest
```
