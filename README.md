# Architectus Calculonis (ARCA)

Computerized Architect - GSI's 2D/3D modelling toolkit

Part of the FAVI System: https://github.com/guild-st-isidore-TO/fabrica-virtualis

---

## USAGE

### Operating Systems

ARCA has been tested on:

MacOS Ventura 13.2.1

### Installation/Setup

Open this repo's directory in the terminal and run:

```
python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt
```

### Running/Deploying the Server

Building docker image

```
docker build -t architectus-calculonis .
```

Listing docker images

```
docker images
```

Run docker image

```
docker run -d -p 5050:5050 architectus-calculonis
```

Listing docker image/container status

```
docker ps -a
```
