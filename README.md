compass-susy
============

Compass + Susy + Breakpoint + Normalize

Build the image:
```
docker build -t compass-susy github.com/ArtemT/compass-susy
```

Use it:
```
docker run -v $(pwd):/src compass-susy create --using susy --require normalize-scss /src
docker run -v $(pwd):/src compass-susy watch /src
```
