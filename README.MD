# Only docker Project

This is a project to test how to run a simple node project without any node installation.

*there is one point to keep in mind: **I'M USING LATEST NODE:ALPINE IMAGE VERSION.** If you are going "live/production" use versioned DOCKERFILE.*

## How to run:

``` PowerShell
docker build -t onlydockerenv
docker run --rm -it -v ${PWD}:/usr/app onlydockerenv
```

**This is it! Go and try**