# bea-manifest

This is an experiment of using kas and kas-container with yocto project. 

In order to use it

1. Install kas
```
pip3 install kas
```
2. Run
```
./kas-container --ssh-agent shell beaglebone.yml
```

3. Build image
```
bitbake bea-image-minimal
```

