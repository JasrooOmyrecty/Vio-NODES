```
git clone https://github.com/JasrooOmyrecty/Vio-NODES
```
```
cd Vio-NODES
```
```
apt install docker.io && apt install pip && apt install pip && apt install systemctl -y
```
```
systemctl start docker
```
```
pip install -r requirements.txt
```

```
docker build -t ubuntu-22.04-with-tmate .
```
```
docker build -t debian-12-with-tmate --build-arg BASE=debian:12 .
```
```
nano vio.py
```
```
python3 vio.py
```
