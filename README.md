# Mongo-Tools - Docker mod for unifi-controller

This mod adds the `mongodb-org-tools` package to unifi-controller, to be installed/updated during container start.

In unifi-controller docker arguments, set an environment variable `DOCKER_MODS=mattberther/unifi-controller-mod:latest`. If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=mattberther/unifi-controller-mod:latest|mattberther/unifi-controller-mod:mod2`.

