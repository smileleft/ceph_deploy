# Install Ceph with cephadm

## On Ubuntu 22.04

```
sudo apt update
sudo apt install -y cephadm
```

## After install, bootstrap

```
sudo cephadm boostrap --mon-ip {your host ip}
```
