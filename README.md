# Dist packages

Repository containing required files to build packages for linux distros.

All packages are currently built using [openSUSE Build Service](https://build.opensuse.org/) and can be found [here](https://build.opensuse.org/project/show/home:nenadalm).

Turorial on debian packages: https://en.opensuse.org/openSUSE:Build_Service_Debian_builds

Building of packages can be tested in docker by running
```
$ docker run -it --volume $PWD:/tmp/src <distribution> /bin/bash
```

Bundled scripts then help with the testing process.

## Scripts

Repository contains a few scripts to help building packages.

- [build-package](doc/build-package.md) - builds single package
- [prepare-build-env](doc/prepare-build-env.md) - prepares env for building packages
