compass-susy
============

Compass + Susy + Breakpoint

Build the image:
```
docker build -t compass-susy github.com/ArtemT/compass-susy
```

Use it:
```
docker run -v $(pwd):/src compass-susy create --using susy /src
docker run -v $(pwd):/src compass-susy watch /src
```
